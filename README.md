## The saashousekeeper rabbitmq-chart test Library for Kubernetes
```
helm repo add my-repo https://saashousekeeper.github.io/rabbitmq-chart/
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
<alias>` to see the charts.

To install the <chart-name> chart:

```
 helm install my-repo my-repo/<chart-name>
```

To uninstall the chart:
```
    helm delete my-<chart-name>
```
