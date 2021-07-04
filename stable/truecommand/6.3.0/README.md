# Introduction

![Version: 6.2.9](https://img.shields.io/badge/Version-6.2.9-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: nightly](https://img.shields.io/badge/AppVersion-nightly-informational?style=flat-square)

Aggregated management of TrueNAS devices

TrueCharts are designed to be installed as TrueNAS SCALE app only. We can not guarantee this charts works as a stand-alone helm installation.
**This chart is not maintained by the upstream project and any issues with the chart should be raised [here](https://github.com/truecharts/apps/issues/new/choose)**

## Source Code

* <https://hub.docker.com/r/ixsystems/truecommand>

## Requirements

Kubernetes: `>=1.16.0-0`

## Dependencies

| Repository | Name | Version |
|------------|------|---------|
| https://truecharts.org/ | common | 6.4.6 |

## Installing the Chart

To install the chart with the release name `truecommand`

- Open TrueNAS SCALE
- Go to Apps
- Click "Install" for this specific Apps
- Fill out the configuration form

## Uninstalling the Chart

To uninstall the `truecommand` deployment

- Open TrueNAS SCALE
- Go to Apps
- Go to "Installed Apps"
- Expand the menu in the top-right corner of this App
- Click "Remove" for this specific Apps

The command removes all the Kubernetes components associated with the chart **including storage volumes** _(Except hostPath Storage)_ and deletes the release.

## Support

- See the [Wiki](https://truecharts.org)
- Open a [issue](https://github.com/truecharts/apps/issues/new/choose)
- Ask a [question](https://github.com/truecharts/apps/discussions)


----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.5.0](https://github.com/norwoodj/helm-docs/releases/v1.5.0)
All Rights Reserved - The TrueCharts Project