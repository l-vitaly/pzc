Docker - Prometheus & Consul & Grafana & Zipkin
======================================

# Install

``` bash
$ cp ./prometheus/prometheus.dist.yml ./prometheus/prometheus.yml
$ sudo ifconfig lo0 alias 10.200.10.1/24
```
Add your services debug address to targets, use host.machine:port.

Run:

``` bash
$ docker-compose up -d
```
