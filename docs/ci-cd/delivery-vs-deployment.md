---
sidebar_position: 3
---

# Continuous Delivery vs. Continuous Deployment

Continuous Deployment and Continuous Delivery are two closely related practices in the realm of automated software release processes, often part of a broader DevOps approach. While they share similarities and the same initials (CD), they cater to slightly different stages of the software release pipeline and embody different philosophies regarding the automation of software releases. Here are the main differences between the two:

## Continuous Delivery

- **Goal**: The primary goal of Continuous Delivery is to ensure that the software can be reliably released to production at any time. It extends Continuous Integration by deploying all code changes to a testing environment and/or a production-like staging environment after the build stage. This practice enables a team to ensure that the software is always in a deployable state.

- **Manual Release Trigger**: Continuous Delivery often includes a manual step for deployment to production. The decision to deploy is made by the team, based on business requirements, schedules, or other considerations. This manual gate before production deployment allows for final verification, stakeholder approval, or scheduling the release at an optimal time.

- **Focus**: Focuses on automating the testing and deployment processes up to, but not always including, the final step of deploying to production. Continuous Delivery ensures that every change is deployable and that there is a clear, automated pathway to production, even if the final step requires human intervention.

## Continuous Deployment

- **Goal**: Continuous Deployment takes Continuous Delivery one step further by automating the deployment to production. With this practice, every change that passes through the pipeline's automated tests is deployed to production automatically, without explicit approval for each specific deployment.

- **Automated Release Trigger**: The deployment process in Continuous Deployment is fully automated. If a change passes all stages of the pipeline (build, test, and any pre-production verification), it gets released to production automatically. There's no manual intervention required for a deployment to happen.

- **Focus**: Focuses on minimizing the time and effort required to get changes released to users. Continuous Deployment aims to accelerate the feedback loop with customers by ensuring that any code commit that meets the automated quality checks is released to customers without delay.

## Summary of Differences

- **Manual vs. Automated Deployment**: The most significant difference lies in how deployments to production are triggered. Continuous Delivery allows for manual control over the timing of releases, while Continuous Deployment automates this step entirely.

- **Approach to Releases**: Continuous Delivery provides flexibility in scheduling and vetting releases, making it suitable for businesses that require control over when changes are made live. Continuous Deployment suits organizations aiming for maximum efficiency and speed in delivering changes to users, assuming their testing and monitoring practices are robust enough to catch issues before and after deployment.

- **Risk Management**: Continuous Deployment assumes a high level of confidence in the deployment pipeline's testing and monitoring capabilities, as any change could potentially be released to users automatically. Continuous Delivery allows for an additional layer of decision-making before changes go live, offering a balance between rapid iteration and risk management.

Both practices require a strong foundation in Continuous Integration and automated testing to work effectively. The choice between Continuous Delivery and Continuous Deployment often comes down to the organization's risk tolerance, regulatory requirements, and business needs.