# Helm / Unifi

This defines any extra config we need to deploy our internal Unifi setup.

Deploy this for the first time using Helm:

```bash
cd ./helm/unifi/

helm install unifi -f values.yaml stable/unifi
```

To upgrade, you can use the Helm upgrade tool:

```bash
helm upgrade unifi stable/unifi -f values.yaml
```