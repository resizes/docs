---
sidebar_position: 1
---

# What is Argo CD?

Argo CD is a declarative, GitOps continuous delivery tool for Kubernetes. It follows the GitOps pattern of using Git repositories as the source of truth for defining the desired application state. Argo CD automates the deployment of the desired application states in the specified target environments.

:::note
Argo CD is part of the Argo project, which includes other tools like Argo Workflows and Argo Events. Check out the [Argo project website](https://argoproj.github.io) for more information.
:::

Argo CD is implemented as a Kubernetes controller that continuously monitors running applications and compares the current, live state against the desired target state (as specified in the Git repository). A deployment is considered in sync when the live state matches the target state. If the live state deviates from the target state, Argo CD will automatically synchronize the two states.

Argo CD provides a web UI and a CLI for managing and viewing the state of applications. It supports multiple authentication methods, including SSO, LDAP, and OAuth.

## Key Features

- **Declarative**: Define the desired application state in a Git repository.
- **Automated Sync**: Automatically sync the live state with the target state.
- **Web UI and CLI**: Manage and view the state of applications.
- **Multi-Environment Support**: Manage multiple environments (e.g., dev, staging, production).
- **Rollback and History**: Rollback to a previous application state and view deployment history.
- **Health Status Checking**: Monitor the health of applications and alert on issues.
- **Access Control**: Define roles and permissions for users and teams.
- **Customizable Workflows**: Define custom deployment workflows and hooks.

## How Argo CD Works

Argo CD follows a GitOps workflow to manage the deployment of applications on Kubernetes clusters. Here's an overview of how Argo CD works:

1. **Define Application State**: Define the desired application state in a Git repository using Kubernetes manifests (e.g., YAML files).
2. **Install Argo CD**: Install the Argo CD controller on your Kubernetes cluster.
3. **Add Application to Argo CD**: Add the application to Argo CD by pointing it to the Git repository.
4. **Sync Application State**: Argo CD continuously monitors the application state and automatically syncs the live state with the target state.
5. **View Application State**: Use the Argo CD web UI or CLI to view the state of applications, rollback to previous states, and manage deployments.