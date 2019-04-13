# Prometheus-Grafana-in-one-container
3 components in one-stop, and `very useful for local monitoring development`:
- Grafana
- Prometheus
- Prometheus-pushgateway
- Prometheus-alertmanager

# Installation
1. make sure you have [docker-compose](https://docs.docker.com/compose/) installed
2. execute commands next:
    ```bash
    git clone https://github.com/morganwu277/docker-app-grafana-prometheus
    # create and start container
    docker-compose up -d 
    # stop containers
    docker-compose stop
    # start the created containers again
    docker-compose start 
    ```
3. open `http://127.0.0.1:3000/` for local grafana, it's up and a default `prometheus-2-0-overview` dashboard is installed there.

