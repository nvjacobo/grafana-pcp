
# Grafana with grafana-pcp plugin

Performance Co-Pilot Grafana Plugin

Performance Co-Pilot (PCP) provides a framework and services to support system-level performance monitoring and management. It presents a unifying abstraction for all of the performance data in a system, and many tools for interrogating, retrieving, and processing that data.

Grafana

Grafana is a multi-platform open source analytics and interactive visualization web application. It provides charts, graphs, and alerts for the web when connected to supported data sources.

## Grafana with grafana-pcp in docker compose

```
git clone https://github.com/nvjacobo/grafana-pcp.git
docker-compose up -d
```

## Grafana with grafana-pcp and Caddy proxy in docker compose

```
git clone https://github.com/nvjacobo/grafana-pcp.git
cd caddy
edit config.env
docker-compose up -d
```

## Requeriments 
- docker
- docker-compose
