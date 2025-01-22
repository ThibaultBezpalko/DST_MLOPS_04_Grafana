# DST_MLOPS_04_Grafana
Datascientest Cursus MLOPS - Sprint 4 - Grafana

# Architecture
├── alertmanager
│   └── config.yml
├── docker-compose.yml
├── grafana
│   ├── config.monitoring
│   └── provisioning
│       ├── dashboards
│       │   ├── Docker_Prometheus_Monitoring.json
│       │   ├── System_Monitoring.json
│       │   ├── Datascientest_System_Monitor.json
│       │   └── dashboard.yml
│       └── datasources
│           └── datasource.yml
├── prometheus
│   ├── alert.rules
│   └── prometheus.yml