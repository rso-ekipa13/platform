# platform

Everything the services run on. Terraform for the Azure resources (AKS, storage, Functions), and the shared pieces inside the cluster: the Envoy API gateway, NATS, PostgreSQL (CloudNativePG), ScyllaDB and monitoring with Prometheus, Grafana and Loki. It also has the Docker Compose setup for running the whole system locally.

Owner: Tibor Koderman. Status: planned.

## Where this fits

This is one of the repositories of [Pretty Good Pigeon](https://github.com/rso-ekipa13), an end-to-end encrypted messenger built by ekipa 13 for the Cloud Computing course at UL FRI (2026/27). The architecture, plan and decisions live in [docs](https://github.com/rso-ekipa13/docs).

`main` only changes through pull requests; day-to-day work goes to `dev`.
