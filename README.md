# Insure-Me – CI/CD Pipeline and Infrastructure Automation

## Project Overview
Insure-Me is a global leading insurance provider based out of the USA, offering products and services such as:
- Home Insurance
- Health Insurance
- Car Insurance
- Life Insurance

### Problem Statement
Insure-Me initially used a monolithic application architecture, which became increasingly difficult to manage as the company grew. They faced several challenges, including:
- Difficulty in building complex builds
- Manual testing efforts across various components and modules
- Managing and deploying incremental builds
- Time-consuming manual infrastructure setup and configuration
- Challenges in continuous manual monitoring of applications

### Solution
To overcome these challenges, Insure-Me has transformed its monolithic architecture into a microservices-based architecture. They adopted DevOps practices and implemented a robust CI/CD pipeline, utilizing **AWS** as the primary cloud service provider to provision servers, databases, and deploy applications.

## Project Goals
- Deliver product updates frequently and reliably to production
- Automate build, test, deployment, and monitoring processes
- Reduce manual intervention and accelerate feedback between developers and testers
- Improve deployment speed, quality, and scalability

## Tools & Technologies Used
| Tool           | Purpose                                                                  |
|----------------|--------------------------------------------------------------------------|
| **Git**        | Version control system to track code changes                           |
| **Jenkins**    | Continuous Integration and Continuous Deployment automation            |
| **Docker**     | Containerization of applications for seamless and consistent deployment |
| **Ansible**    | Configuration management and automated setup across environments       |
| **AWS (EC2)**  | Cloud platform to provision servers and deploy applications            |

## Key Benefits
- Automated provisioning of **AWS EC2 instances** using infrastructure automation
- Continuous build, test, and deployment with Jenkins integrated with Docker
- Simplified configuration management using **Ansible**
- Faster deployment cycles, reduced manual work, and improved scalability and reliability

## Future Enhancements
- Implement monitoring using **Prometheus and Grafana**
- Integrate automated rollback mechanisms for failed deployments
- Add Slack/Email notifications for build and deployment status
- Adopt advanced deployment strategies like Blue-Green or Canary deployments

---

