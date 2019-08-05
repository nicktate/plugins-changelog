# CSI - Amazon Web Services Changelog

## Versions

- [v0.3.0+1](#v0301)
  - [Bug Fixes](#bug-fixes-for-v0301)
- [v0.3.0](#v030)
  - [Features](#features-for-v030)
- [v0.2.0](#v020)
  - [Features](#features-for-v020)

## v0.3.0+1

### Bug Fixes for v0.3.0+1

* Update `livenessprobe` image to 1.0.2 to fix high memory usage
  * See https://github.com/kubernetes-csi/livenessprobe/issues/45 for more details

## v0.3.0

### Features for v0.3.0

* Added support for [AWS CSI v0.3.0](https://github.com/kubernetes-sigs/aws-ebs-csi-driver/releases/tag/v0.3.0)
* Supports Kubernetes v1.13.x - v1.14.x

## v0.2.0

### Features for v0.2.0

* Added support for [AWS CSI v0.2.0](https://github.com/kubernetes-sigs/aws-ebs-csi-driver/releases/tag/v0.2.0)
* Basic support for interfacing with AWS Elastic Block Store
* Supports Kubernetes v1.13.x - v1.14.x
