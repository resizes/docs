---
sidebar_position: 4
---

# Atlantis

Atlantis is an open-source tool that automates Terraform workflows. It provides a collaborative environment for Terraform, enabling teams to work together on infrastructure changes. Atlantis is designed to simplify the process of reviewing, approving, and merging Terraform pull requests, ensuring that infrastructure changes are managed in a controlled and efficient manner. It integrates with version control system (VCS) providers like GitHub, GitLab, and Bitbucket to provide a unified workflow for provisioning and managing infrastructure through pull requests (PRs).

:::info
Atlantis is developed and maintained by the [community](https://www.runatlantis.io/).
:::

## Key Concepts

- **Pull Request Automation**: Atlantis automates Terraform plan and apply commands in response to VCS pull requests and comments, making infrastructure changes visible and collaborative.
- **State Locking**: Prevents concurrent execution of Terraform commands on the same state files, ensuring that infrastructure changes are applied safely.
- **Custom Workflows**: Supports custom workflows, allowing teams to tailor Atlantis to fit their specific processes and policies.
