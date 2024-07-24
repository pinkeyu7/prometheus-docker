# Prometheus setup on Docker Compose

## Components

| Name                   | Port | Link                                             |
| ---------------------- | ---- | ------------------------------------------------ |
| Prometheus             | 9090 | [http://localhost:9090/](http://localhost:9090/) |
| Prometheus Pushgateway | 9091 | [http://localhost:9091/](http://localhost:9091/) |
| Grafana                | 9092 | [http://localhost:9092/](http://localhost:9092/) |
| Docker Stats Exporter  | 9093 | [http://localhost:9093/](http://localhost:9093/) |

## Run

```bash
docker-compose up
```

## Data

Store in docker volume
