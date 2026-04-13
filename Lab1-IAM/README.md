## AWS Lab 1: IAM Governance and RBAC

## Project Overview
As part of my AWS Certified Cloud Practitioner journey, I implemented a Role-Based Access Control (RBAC) system. This project simulates a real-world business scenario where specific permissions are delegated to S3 and EC2 support teams.

## Tech Stack and Methodology
* **Platform:** AWS (Identity and Access Management)
* **Tooling:** AWS CLI v2
* **Environment:** Local Development on Apple Silicon (MacBook Air)
* **Security Principle:** Applied the **Principle of Least Privilege (PoLP)**.

## Execution Highlights
I bypassed the standard management console to execute all configurations via the **AWS CLI**. This ensured a repeatable, engineer-centric workflow.

### Key Tasks Completed:
1. **User/Group Architecture:** Organized users into `S3-Support`, `EC2-Support`, and `EC2-Admin` groups.
2. **Policy Assignment:** Attached AWS Managed Policies (`AmazonS3ReadOnlyAccess`) and custom Inline Policies.
3. **Identity Validation:** Configured named profiles to verify that `user-1` (S3) was strictly forbidden from touching EC2 resources.

## Results
Successfully validated all 6 lifecycle tasks with a perfect score of **40/40**.
