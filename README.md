# Learn Prometheus

This spins up Prometheus server and a Podman Exporter (as a Prometheus target).

```console
# spin up Prometheus server and the target(s)
$ podman compose up

# open up Prometheus UI
$ open http://localhost:9090

# or, open up Grafana
$ open http://localhost:3000/explore
```

You can then explore the metrics available, or run some PromQL queries.
