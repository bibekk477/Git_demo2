# Useful commands:

```bash
helm install mysql-exporter prometheus-community/prometheus-mysql-exporter \
  --namespace database-monitoring \
  --values mysql-exporter/mysql-exporter-values.yaml

It installs a MySQL Exporter in Kubernetes so Prometheus can monitor MySQL.
```md
**Explanation:**
- `helm install` → Installs a Helm chart
- `mysql-exporter` → Release name
- `prometheus-community/prometheus-mysql-exporter` → MySQL exporter chart
- `--namespace database-monitoring` → Target namespace
- `--values mysql-exporter/mysql-exporter-values.yaml` → Custom values file
