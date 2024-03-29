# Helm Chart

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add mirror520 https://mirror520.github.io/charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
mirror520` to see the charts.

To install the identity chart:

    helm install identity mirror520/identity

To uninstall the chart:

    helm delete identity
