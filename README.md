# dotnetAPM
Quick WebAPI for testing APM with AppMetrics and Prometheus

# Running

Build the dotnetAPM container with `./bin/build-app`

Start everything with `docker-compose up`

Log in to Grafana at http://localhost:3000 with admin/admin
Add Prometheus as a data source at http://localhost:9090
Add Loki as a data source at http://localhost:3100

Look around!