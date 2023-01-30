# Vechr App
Vehcr Observability to monitoring the application

## TL;DR;
```
# Install vechr
helm repo add vechr https://vechr.github.io/vechr-observability/helm/charts/
helm repo update
helm install vechr-observability vechr/vechr -n monitor --create-namespace
```