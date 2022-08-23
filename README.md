## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```
$ helm repo add lokalise https://lokalise.github.io/helm-charts
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages. You can then run `helm search repo
lokalise` to see the charts.

To install the <chart-name> chart:

    helm install <chart-name> lokalise/<chart-name>

To view the default values for a chart:

    helm show values lokalise/<chart-name>

To uninstall the chart:

    helm delete <chart-name>
