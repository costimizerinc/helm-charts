# Helm Charts
Usage

Helm must be installed to use the charts. Please refer to Helm's documentation to get started.

Once Helm has been set up correctly, add the repo as follows:

helm repo add costimizer https://costimizerinc.github.io/helm-charts

If you had already added this repo earlier, run helm repo update to retrieve the latest versions of the packages. You can then run helm search repo costimizer to see the charts.

To install the chart:

helm install <chart-name> costimizerinc/<chart-name>

To uninstall the chart:

helm uninstall <chart-name>
