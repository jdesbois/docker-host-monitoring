# docker-host-monitoring

Simple docker-compose to set up four containers in order to monitor the host and the containers running on the host via grafana dashboard.
Dashboard and datasource are pre-configured in Grafana
Prometheus config set to scrape data from cadvisor and node_exporter.

## Instructions
Simply clone the repo, CD into folder and run docker-compose up
