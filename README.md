# Helm chart for netbox-kubernetes

Forked from https://github.com/vishnoisuresh/netbox-kubernetes.

Caveat: upgrade to v2.11 before upgrading to v3.0.

## Usage

```
git clone https://github.com/jiegec/netbox-kubernetes
cp netbox-kubernetes/values.yaml .
vim values.yaml
helm upgrade netbox netbox-kubernetes --install -f values.yaml
```
