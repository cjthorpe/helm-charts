# prometheus-thanos-helm-chart
-------------

Deploys Prometheus along with a Thanos sidecar using a Helm chart.

-------------
## Prerequisites

  - Kubernetes 1.14.9+
  - Helm 3.0+

-------------
## Installing the Chart

Clone this repository and run the following commands from root.

```console
$ cd prometheus-thanos-helm-chart
$ helm upgrade --install prometheus-thanos-sidecar --values ./prometheus-thanos-sidecar/values.yaml ./prometheus-thanos-sidecar --debug -n <namesapce>
```

Note it is important that you configure your values file first.

-------------
## Uninstalling the Chart

To uninstall/delete the `my-release` deployment:

```console
$ helm delete my-release -n <namespace>
```
