# Monitoring 
This is to collect and visualize metrics from your servers and applications

# Components

 - Prometheus | It collects metrics from configured targets.
 - Grafana | Use to query and visualize metrics
 - Node Exporter | Prometheus exporter for hardware and operating system metrics 
 - Alertmanager | This is to collect and visualize metrics from your servers and applications.

# Prerequisites

- Make sure **Docker** is installed. *Checkout installation here* [Docker](https://www.docker.com/ "Docker")
- Make sure **Docker Compose** is installed. *Checkout installation here* [Docker](https://docs.docker.com/compose/ "Docker Compose")

# Endpoint Checks
- Grafana | http://localhost:3000
- Prometheus | http://localhost:9090
- Prometheus(Metrics) | http://localhost:9090/metrics
- Node Exporter | http://localhost:9100
- Node Exporter(Metrics) | http://localhost:9100/metrics
- Cadvisor | http://localhost:8080
- Cadvisor(Metrics) | http://localhost:8080/metrics

# Start Server
```sh
$ docker-compose up
```




