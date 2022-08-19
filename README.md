## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add https://github.com/cristiancalugaru/airflow-helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run 

`helm search repo https://github.com/cristiancalugaru/airflow-helm-charts/tree/main/charts/airflow` to see the charts.

To install the airflow chart:

    helm install airflow https://github.com/cristiancalugaru/airflow-helm-charts/tree/main/charts/airflow

To uninstall the chart:

    helm delete airflow
