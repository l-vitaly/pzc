Docker Compose - Prometheus & Consul & Grafana & Zipkin
======================================

# Install

``` bash
$ cp ./prometheus/prometheus.dist.yml ./prometheus/prometheus.yml
$ sudo ifconfig lo0 alias 10.200.10.1/24
```
Add your services debug address to targets, use 0.0.0.0:port.

Run:

``` bash
$ docker-compose up -d
```
