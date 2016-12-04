Docker Compose - Prometheus & Consul & Grafana & Zipkin
======================================

# Install

``` bash
$ cp ./prometheus/prometheus.dist.yml ./prometheus/prometheus.yml
$ sudo ifconfig lo0 alias 10.200.10.1/24
```

*Your service is listening on this address or 0.0.0.0 (ie not 127.0.0.1). 
Then containers can connect to this address.*

Add your services debug address to targets, use host:port.

*host is equal 10.200.10.1*


Run:

``` bash
$ docker-compose up -d
```
