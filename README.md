# Helm chart for netbox-kubernetes

## Usage

```
git clone https://github.com/jiegec/netbox-kubernetes
cp netbox-kubernetes/values.yaml .
vim values.yaml
helm upgrade netbox netbox-kubernetes --install -f values.yaml
```