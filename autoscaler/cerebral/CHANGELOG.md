# Autoscaler - [Cerebral](https://github.com/containership/cerebral) Changelog

## Versions

- [v0.6.1-alpha](#v061alpha)
  - [Security](#security-for-v061alpha)
  - [Features](#features-for-v061alpha)
- [v0.5.0-alpha](#v050alpha)
  - [Features](#features-for-v050alpha)
- [v0.3.2-alpha](#v032alpha)
  - [Features](#features-for-v032alpha)
- [v0.1.0-alpha](#v010alpha)
  - [Features](#features-for-v010alpha)

## v0.6.1-alpha

### Security for v0.6.1-alpha

* Update go version to 1.12.9a to cover https://github.com/Netflix/security-bulletins/blob/master/advisories/third-party/2019-002.md

### Features for v0.6.1-alpha

* Support for Kubernetes v1.15

## v0.5.0-alpha

### Features for v0.5.0-alpha

* Support for Kubernetes v1.14

## v0.3.2-alpha

### Features for v0.3.2-alpha

* Support for Kubernetes v1.13

## v0.1.0-alpha

### Features for v0.1.0-alpha

* Kubernetes cluster autoscaler with pluggable metrics backends and scaling engines
* Support for Kubernetes v1.11 - v1.12
* Requires `containership` cluster-management and `prometheus` metrics plugins
  * `containership` cluster-management plugin >= v4.2.0
  * `prometheus` metrics plugin >= v1.0.0
* Prometheus metrics backend with cpu percent utilization, memory percent utilization and custom queries
