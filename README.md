# helm-charts

# Status

[![Release Charts](https://github.com/kode-lib/helm-charts/actions/workflows/release.yml/badge.svg)](https://github.com/kode-lib/helm-charts/actions/workflows/release.yml)
[![Artifact HUB](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/kodelib)](https://artifacthub.io/packages/search?repo=kodelib)

## Development environment

All the charts are developed and teste locally using minikube, so before everything you need to start minikube on your local machine.

    minikube start

Once the service started you can use the werk definition on any of the charts to install/uninstall an instance of the Helm chart

    cd charts/[name]
    werk run install
    werk run test
    werk run uninstall