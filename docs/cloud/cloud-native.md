---
sidebar_position: 4
---

# Cloud Native

## What is Cloud Native?

Cloud native is a term that refers to the modernization of applications and infrastructure to take advantage of the cloud computing delivery model. It is a set of practices that empowers an organization to build and manage applications at scale. Cloud native technologies enable organizations to build and run scalable applications in modern, dynamic environments such as public, private, and hybrid clouds.

Cloud-native is a set of practices and technologies used to develop applications built with services packaged in containers, deployed as microservices, and managed on elastic infrastructure through agile DevOps processes and continuous delivery workflows. When it comes to platform engineering in a cloud-native context, the focus is on creating a scalable and flexible infrastructure that supports the development, deployment, and management of these applications efficiently and securely.

:::note
The [Cloud Native Computing Foundation (CNCF)](https://www.cncf.io/) is a vendor-neutral home for many of the fastest-growing projects in the cloud-native ecosystem. The CNCF provides a comprehensive landscape of the cloud-native ecosystem, which can be found [here](https://landscape.cncf.io/).
:::

## Overview

Platform engineering in a cloud-native ecosystem involves designing, implementing, and managing a platform that provides developers with the tools and capabilities they need to build and deploy applications quickly. This platform is typically based on cloud services and leverages containerization, orchestration, microservices, and CI/CD pipelines to streamline development processes and enable rapid iteration.

## Key Components

- **Containerization**: Containers package application code along with its dependencies, ensuring consistency across environments from development to production. Docker and containerd are popular tools for containerization.
- **Orchestration**: Orchestration tools like Kubernetes manage the deployment, scaling, and operation of containerized applications, ensuring they run efficiently and resiliently across multiple computing environments.
- **Microservices Architecture**: This architectural style structures an application as a collection of loosely coupled services, which makes it easier to develop, deploy, and scale parts of the application independently.
- **CI/CD Pipelines**: Continuous Integration (CI) and Continuous Delivery (CD) pipelines automate the building, testing, and deployment of applications, facilitating rapid releases and updates.
- **Infrastructure as Code (IaC)**: IaC tools like Terraform and CloudFormation allow teams to automate the provisioning and management of infrastructure using code, improving consistency and reducing manual errors.
- **Observability and Monitoring**: Tools and practices that provide insights into the performance and health of applications and infrastructure, including logging, monitoring, and tracing. Prominent tools include Prometheus, Grafana, and Elastic Stack.

## Best Practices

- **Automate Everything**: Automation is key in a cloud-native platform. Automate deployment, scaling, recovery, and infrastructure provisioning to reduce manual intervention and increase efficiency.
- **Security by Design**: Incorporate security at every stage of the development lifecycle. Use automated scanning for vulnerabilities, enforce security policies, and practice the principle of least privilege.
- **Build for Scalability**: Design services and infrastructure to be scalable from the outset. Use scalable cloud services and design applications in a way that they can handle varying loads gracefully.
- **Emphasize Observability**: Ensure that the system is observable from the outside, providing insights into its state and behavior. This is crucial for troubleshooting and understanding system performance.
- **Foster a DevOps Culture**: Encourage collaboration between development and operations teams. A strong DevOps culture is essential for successful cloud-native platform engineering.

## Conclusion

Cloud-native platform engineering requires a shift in how organizations approach IT infrastructure and application development. By leveraging containerization, orchestration, microservices, and automation, teams can create more resilient, scalable, and efficient applications. The focus on automation, security, and DevOps practices ensures that the platform remains flexible and responsive to the needs of the business while minimizing risk.