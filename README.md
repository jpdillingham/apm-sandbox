# apm-sandbox
Quick stack for APM (Application Performance Monitoring) using Prometheus for metrics ingestion, Loki for log ingestion, and Grafana for aggregation/visualization.

Includes a .NET Core template app with Prometheus metrics and Serilog with a Loki sink.

# Running

Build the dotnetAPM container with `./bin/build-app`

Start everything with `docker-compose up`

Log in to Grafana at http://localhost:3000 with admin/admin

Add Prometheus as a data source at http://localhost:9090

Add Loki as a data source at http://localhost:3100

Look around!