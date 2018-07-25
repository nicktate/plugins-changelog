# Cluster Management - Containership Changelog

## Versions

- [v3.0.0](#v300)
  - [Features](#features-for-v300)
  - [Bug Fixes](#bug-fixes-for-v300)
- [v2.1.0](#v210)
  - [Features](#features-for-v210)
  - [Bug Fixes](#bug-fixes-for-v210)
- [v2.0.1](#v201)
  - [Misc](#misc-for-v201)
- [v2.0.0](#v200)
  - [Features](#features-for-v200)
  - [Bug Fixes](#bug-fixes-for-v200)
- [v1.0.3](#v103)
  - [Features](#features-for-v103)

## v3.0.0

### Features for v3.0.0

* Support for Kubernetes v1.9 - v1.11
* Adds `pre` and `post` jobs for plugin upgrade events
* Auth middleware for coordinator routes

### Bug Fixes for v3.0.0

* Prevent segfault on bad configuration of coordinator or agent

## v2.1.0

### Features for v2.1.0

* Add `ENABLE_CLUSTER_UPGRADE` option
* Strip leading v for upgrade request versions // not strictly needed, covered by matching fix on cloud side
* Post node cloud status to cloud

### Bug Fixes for v2.1.0

* Fix bug where current file not being created atomically
* Properly mark upgrade as Success if upgraded version is current version of node

## v2.0.1

### Misc for v2.0.1

* Remove extraneous containership service account yaml from manifests

## v2.0.0

### Features for v2.0.0

* Support for Kubernetes v1.8 - v1.10

### Bug Fixes for v2.0.0

* Fix plugin sync bug where error was not checked before firing event

## v1.0.3

### Features for v1.0.3

* Support for Kubernetes v1.7 - v1.9
