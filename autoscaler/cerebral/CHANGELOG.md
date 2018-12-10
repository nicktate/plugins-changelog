# Autoscaler - [Cerebral](https://github.com/containership/cerebral) Changelog

## Versions

- [v0.1.0-alpha](#v010alpha)
  - [Features](#features-for-v010alpha)

## v0.1.0-alpha

* Kubernetes cluster autoscaler with pluggable metrics backends and scaling engines
* Support for Kubernetes v1.11 - v1.12
* Requires `containership` cluster-management and `prometheus` metrics plugins
  * `containership` cluster-management plugin >= v4.2.0
  * `prometheus` metrics plugin >= v1.0.0
* Prometheus metrics backend with cpu percent utilization, memory percent utilization and custom queries
