# Code4Life - DevOps Journey
This repository talks about the journey (road map) to become a DevOps Engineer.

## About
This roadmap is composed by **@Code4life-Labs** with many concepts, theories and examples for practicing that we think it matches our requirements, so this map is suitable for us and if you want to follow this, don't hesitant, let's start.

## What is DevOps?
<p align="center">
  <img src="https://github.com/user-attachments/assets/e0995c33-f9d7-4540-a0bf-99a2f37a64bd" />
</p>

DevOps is a compound & abbreviate words of **Develop** and **Operate**. It isn't a role but is a culture of work which helps developers and operators work together smoothly and prevent issues as much as possible. It covers development, testing, building, packaging, delivery, deployment and monitoring. This process is divided into 2 main sub processes: **Continuous Integration** and **Continuous Delivery/Deployment**.

The guidline of devops is **Automation**, devops "will help" the team delivery application to end users in light speed by implement various automatic process called **stage** in a **pipeline**.

Each stage inludes multiple designed steps for different environments, such as Test, Development, Staging and Production (environment of end users). Although the automation is prioritized, some stages are must be handle by human, especially, code stage. When an application is decided to merge with the main branch, it will be automatically build, test, packaging and deploy. But remember that, each pipeilne will be different between numerous system, team.

## Map
### Linux
With the popular of linux in nowaday, it seems to be good to learn Linux. We can see there are many systems is operated with linux. So, in this stage, what we will learn
- Basic directories in linux and their meaning
- Some basic command
- Authority

### Docker
Docker gives an abstraction of application deployment by containerize application and run it in Docker environment, fit in multiple environment.
- Docker
- Docker Compose

### Cloud (AWS)
Computing in Cloud is trending, the largest cloud computing provider in the world is AWS (Amazon Web Services). They provide multiple solutions for almost our problems in this web era.
- Network
- EC2
- CloudFormation (IaC)
- ECS
- Load Balacing
- API Gateway

### CI/CD
When the application is ready to deploy, firstly, we must integrate some tools to build, test and packaging, then continously deploy it to required environment.
- Github Actions
- Jenkins

### Clustering
When our system contains many containers, we need to classify them as clusters and manage these clusters.
- K8S
- EKS (Elastic Kubernetes Service)

### Network
Because devops works with system, so we need to know about network.
- Fundamental of network
- Network in Docker
