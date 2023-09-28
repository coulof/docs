# CSI external-attacher

## Status and Releases

**Git Repository:** [https://github.com/kubernetes-csi/external-attacher](https://github.com/kubernetes-csi/external-attacher)

**Status:** GA/Stable

### Supported Versions

Latest stable release | Branch | Min CSI Version | Max CSI Version | Container Image | [Min K8s Version](project-policies.md#minimum-version) | [Max K8s Version](project-policies.md#maximum-version) | [Recommended K8s Version](project-policies.md#recommended-version) |
--|--|--|--|--|--|--|--
[external-attacher v4.4.0](https://github.com/kubernetes-csi/external-attacher/releases/tag/v4.4.0) | [release-4.4](https://github.com/kubernetes-csi/external-attacher/tree/release-4.4) | [v1.0.0](https://github.com/container-storage-interface/spec/releases/tag/v1.0.0) | - | registry.k8s.io/sig-storage/csi-attacher:v4.4.0 | v1.17 | - | v1.27
[external-attacher v4.3.0](https://github.com/kubernetes-csi/external-attacher/releases/tag/v4.3.0) | [release-4.3](https://github.com/kubernetes-csi/external-attacher/tree/release-4.3) | [v1.0.0](https://github.com/container-storage-interface/spec/releases/tag/v1.0.0) | - | registry.k8s.io/sig-storage/csi-attacher:v4.3.0 | v1.17 | - | v1.22
[external-attacher v4.2.0](https://github.com/kubernetes-csi/external-attacher/releases/tag/v4.2.0) | [release-4.2](https://github.com/kubernetes-csi/external-attacher/tree/release-4.2) | [v1.0.0](https://github.com/container-storage-interface/spec/releases/tag/v1.0.0) | - | registry.k8s.io/sig-storage/csi-attacher:v4.2.0 | v1.17 | - | v1.22
[external-attacher v4.1.0](https://github.com/kubernetes-csi/external-attacher/releases/tag/v4.1.0) | [release-4.1](https://github.com/kubernetes-csi/external-attacher/tree/release-4.1) | [v1.0.0](https://github.com/container-storage-interface/spec/releases/tag/v1.0.0) | - | registry.k8s.io/sig-storage/csi-attacher:v4.1.0 | v1.17 | - | v1.22

### Unsupported Versions

Latest stable release | Branch | Min CSI Version | Max CSI Version | Container Image | [Min K8s Version](project-policies.md#minimum-version) | [Max K8s Version](project-policies.md#maximum-version) | [Recommended K8s Version](project-policies.md#recommended-version) |
--|--|--|--|--|--|--|--
[external-attacher v4.0.0](https://github.com/kubernetes-csi/external-attacher/releases/tag/v4.0.0) | [release-4.0](https://github.com/kubernetes-csi/external-attacher/tree/release-4.0) | [v1.0.0](https://github.com/container-storage-interface/spec/releases/tag/v1.0.0) | - | registry.k8s.io/sig-storage/csi-attacher:v4.0.0 | v1.17 | - | v1.22
[external-attacher v3.5.1](https://github.com/kubernetes-csi/external-attacher/releases/tag/v3.5.1) | [release-3.5](https://github.com/kubernetes-csi/external-attacher/tree/release-3.5) | [v1.0.0](https://github.com/container-storage-interface/spec/releases/tag/v1.0.0) | - | registry.k8s.io/sig-storage/csi-attacher:v3.5.1 | v1.17 | - | v1.22
[external-attacher v3.4.0](https://github.com/kubernetes-csi/external-attacher/releases/tag/v3.4.0) | [release-3.4](https://github.com/kubernetes-csi/external-attacher/tree/release-3.4) | [v1.0.0](https://github.com/container-storage-interface/spec/releases/tag/v1.0.0) | - | registry.k8s.io/sig-storage/csi-attacher:v3.4.0 | v1.17 | - | v1.22
[external-attacher v3.3.0](https://github.com/kubernetes-csi/external-attacher/releases/tag/v3.3.0) | [release-3.3](https://github.com/kubernetes-csi/external-attacher/tree/release-3.3) | [v1.0.0](https://github.com/container-storage-interface/spec/releases/tag/v1.0.0) | - | registry.k8s.io/sig-storage/csi-attacher:v3.3.0 | v1.17 | - | v1.22
[external-attacher v3.2.1](https://github.com/kubernetes-csi/external-attacher/releases/tag/v3.2.1) | [release-3.2](https://github.com/kubernetes-csi/external-attacher/tree/release-3.2) | [v1.0.0](https://github.com/container-storage-interface/spec/releases/tag/v1.0.0) | - | registry.k8s.io/sig-storage/csi-attacher:v3.2.1 | v1.17 | - | v1.17
[external-attacher v3.1.0](https://github.com/kubernetes-csi/external-attacher/releases/tag/v3.1.0) | [release-3.1](https://github.com/kubernetes-csi/external-attacher/tree/release-3.1) | [v1.0.0](https://github.com/container-storage-interface/spec/releases/tag/v1.0.0) | - | registry.k8s.io/sig-storage/csi-attacher:v3.1.0 | v1.17 | - | v1.17
[external-attacher v3.0.2](https://github.com/kubernetes-csi/external-attacher/releases/tag/v3.0.2) | [release-3.0](https://github.com/kubernetes-csi/external-attacher/tree/release-3.0) | [v1.0.0](https://github.com/container-storage-interface/spec/releases/tag/v1.0.0) | - | registry.k8s.io/sig-storage/csi-attacher:v3.0.2 | v1.17 | - | v1.17
[external-attacher v2.2.0](https://github.com/kubernetes-csi/external-attacher/releases/tag/v2.2.0) | [release-2.2](https://github.com/kubernetes-csi/external-attacher/tree/release-2.2) | [v1.0.0](https://github.com/container-storage-interface/spec/releases/tag/v1.0.0) | - | quay.io/k8scsi/csi-attacher:v2.2.0 | v1.14 | - | v1.17
[external-attacher v2.1.0](https://github.com/kubernetes-csi/external-attacher/releases/tag/v2.1.0) | [release-2.1](https://github.com/kubernetes-csi/external-attacher/tree/release-2.1) | [v1.0.0](https://github.com/container-storage-interface/spec/releases/tag/v1.0.0) | - | quay.io/k8scsi/csi-attacher:v2.1.0 | v1.14 | - | v1.17
[external-attacher v2.0.0](https://github.com/kubernetes-csi/external-attacher/releases/tag/v2.0.0) | [release-2.0](https://github.com/kubernetes-csi/external-attacher/tree/release-2.0) | [v1.0.0](https://github.com/container-storage-interface/spec/releases/tag/v1.0.0) | - | quay.io/k8scsi/csi-attacher:v2.0.0 | v1.14 | - | v1.15
[external-attacher v1.2.1](https://github.com/kubernetes-csi/external-attacher/releases/tag/v1.2.1) | [release-1.2](https://github.com/kubernetes-csi/external-attacher/tree/release-1.2) | [v1.0.0](https://github.com/container-storage-interface/spec/releases/tag/v1.0.0) | - | quay.io/k8scsi/csi-attacher:v1.2.1 | v1.13 | - | v1.15
[external-attacher v1.1.1](https://github.com/kubernetes-csi/external-attacher/releases/tag/v1.1.1) | [release-1.1](https://github.com/kubernetes-csi/external-attacher/tree/release-1.1) | [v1.0.0](https://github.com/container-storage-interface/spec/releases/tag/v1.0.0) | - | quay.io/k8scsi/csi-attacher:v1.1.1 | v1.13 | - | v1.14
[external-attacher v0.4.2](https://github.com/kubernetes-csi/external-attacher/releases/tag/v0.4.2) | [release-0.4](https://github.com/kubernetes-csi/external-attacher/tree/release-0.4) | [v0.3.0](https://github.com/container-storage-interface/spec/releases/tag/v0.3.0) | [v0.3.0](https://github.com/container-storage-interface/spec/releases/tag/v0.3.0) | quay.io/k8scsi/csi-attacher:v0.4.2 | v1.10 | v1.16 | v1.10

## Description

The CSI `external-attacher` is a sidecar container that watches the Kubernetes API server for `VolumeAttachment` objects and triggers `Controller[Publish|Unpublish]Volume` operations against a CSI endpoint.

## Usage

CSI drivers that require integrating with the Kubernetes volume attach/detach hooks should use this sidecar container, and advertise the CSI `PUBLISH_UNPUBLISH_VOLUME` controller capability.

For detailed information (binary parameters, RBAC rules, etc.), see [https://github.com/kubernetes-csi/external-attacher/blob/master/README.md](https://github.com/kubernetes-csi/external-attacher/blob/master/README.md).

## Deployment

The CSI `external-attacher` is deployed as a controller. See [deployment section](deploying.md) for more details.
