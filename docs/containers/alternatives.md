---
sidebar_position: 4
---

# Alternatives

This section outlines alternative containerization tools and platforms that can be used in place of Docker. Each tool has its own unique features and use cases, and understanding these alternatives can help platform engineers make informed decisions when selecting the right containerization tool for their applications.

## Podman

Podman is a daemonless container engine for developing, managing, and running OCI Containers on your Linux system. It is fully compatible with Docker but doesn't require a running daemon. This makes it more secure and easier to integrate into various system setups.

Key Features:

- Daemonless architecture
- Rootless containers for enhanced security
- Direct integration with Kubernetes through pod definitions
- Compatible with Docker command-line interface

:::info
If you are new to Podman, refer to the [official Podman documentation](https://podman.io/).
:::

## Containerd

Containerd is an industry-standard core container runtime that provides a reliable and high-performance container runtime with an emphasis on simplicity, robustness, and portability. It is available as a daemon for Linux and Windows, and it is designed to be embedded into larger systems.

Key Features:

- Industry-standard core container runtime
- Emphasis on simplicity, robustness, and portability
- Fully integrates with the Kubernetes ecosystem
- Designed to be embedded into larger systems

:::info
If you are new to Containerd, refer to the [official Containerd documentation](https://containerd.io/).
:::

## Buildah

Buildah is a tool for building OCI container images. It is designed to work with containers without requiring a daemon, and it can be used to build images from scratch or to modify existing images.

Key Features:

- Daemonless architecture
- Build images from scratch
- Modify existing images
- Compatible with Dockerfiles

:::info
If you are new to Buildah, refer to the [official Buildah documentation](https://buildah.io/).
:::

## CRI-O

CRI-O is an implementation of the Kubernetes Container Runtime Interface (CRI) to enable using OCI-compatible runtimes. It is a lightweight alternative to using Docker as the runtime for Kubernetes.

Key Features:

- Lightweight and minimal runtime
- Fully compatible with Kubernetes
- Supports OCI-compatible runtimes

:::info
If you are new to CRI-O, refer to the [official CRI-O documentation](https://cri-o.io/).
:::
