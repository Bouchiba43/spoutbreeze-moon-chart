# SpoutBreeze Broadcaster Helm Chart

This Helm chart deploys the **SpoutBreeze Broadcaster** component to your Kubernetes cluster.

---

## Prerequisites

- [Helm](https://helm.sh/docs/intro/install/) 3.x installed
- A Kubernetes cluster
- A namespace named `moon` (create it if it doesn't exist):
  ```bash
  kubectl create namespace moon
  ```

##  Installation

To install the chart with the release name `spoutbreeze-broadcaster` into the `moon` namespace:

```bash
helm install spoutbreeze-broadcaster . -n moon
```

**Note:** Run the above command from the root directory of this Helm chart (where the `Chart.yaml` file is located).

##  Upgrade

To upgrade the release with new changes:

```bash
helm upgrade spoutbreeze-broadcaster . -n moon
```

##  Uninstall

To delete the Helm release and its associated resources:

```bash
helm uninstall spoutbreeze-broadcaster -n moon
```
