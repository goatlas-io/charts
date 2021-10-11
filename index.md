# Atlas Helm Repository

Add Atlas repository to Helm repos:

```bash
helm repo add atlas https://charts.goatlas.io
```

## Install Atlas

```bash
helm upgrade -i flux atlas/atlas --namespace monitoring 
```
