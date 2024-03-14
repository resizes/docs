---
sidebar_position: 3
---

# Open Container Initiative (OCI)

The Open Container Initiative (OCI) specifications, particularly the OCI Image Specification, have paved the way for OCI registries to store a variety of artifacts beyond traditional container images. This flexibility is critical for supporting a wide range of use cases in modern software development and deployment processes. Here are several notable types of artifacts that can be stored in OCI-compliant registries apart from container images.

## 1. Helm Charts

Helm, the package manager for Kubernetes, uses charts to describe a set of Kubernetes resources. OCI registries can store Helm charts as artifacts, enabling versioning, sharing, and management of Kubernetes applications alongside container images.

## 2. Singularity Images

Singularity is a container solution created for scientific and high-performance computing environments. Singularity images (SIF files) can be stored in OCI registries, allowing for versioned storage and distribution within scientific and research communities.

## 3. WASM Modules

WebAssembly (WASM) modules, which enable high-performance applications to run in web browsers and other environments, can be stored in OCI registries. This storage solution facilitates versioning, sharing, and deploying WASM modules in a manner similar to container images.

## 4. OPA Policies

Open Policy Agent (OPA) policies, which provide a high-level declarative language to specify policies as code, can be distributed through OCI registries. This capability allows for centralized management and distribution of policies across different environments.

## 5. Machine Learning Models

Machine learning models can be packaged and distributed as OCI artifacts. This approach offers a standardized way to version, share, and deploy models across various stages of the machine learning lifecycle, from development to production.

## 6. Configuration Files

Configuration files, such as those used for infrastructure as code (IaC) or application configurations, can be versioned and stored in OCI registries. This enables consistent deployment and management of configurations alongside the applications they support.

## 7. Serverless Functions

Artifacts related to serverless computing, such as function code and dependencies, can be stored in OCI registries. This facilitates the versioning, sharing, and deployment of serverless functions in a cloud-native environment.

## 8. Custom Application Artifacts

Developers can leverage OCI registries to store custom application artifacts that adhere to the OCI Image Specification. This flexibility allows for innovative uses of OCI registries beyond their initial intent, supporting a broad range of applications and workflows.

The ability to store these diverse artifacts in OCI registries highlights the flexibility and potential of the OCI specifications to support a wide array of cloud-native technologies and workflows. This versatility is instrumental in fostering a unified, standardized approach to artifact storage and distribution in the software development lifecycle.