# NodeJS-ECS-Terraform
Deploying a flask application to AWS ECS via AWS CodePipeline, and all resources provisioned by terraform.


The major components of our implementation here are:

GitHub to house the source code
ECR to host the docker image
ECS to host the deployed application. A good alternative would also be EBS.
CodePipeline to continuously deploy future versions of our application
Terraform to manage the provisioning of our resources easily

Elastic Container Service (ECS) - Amazon ECS is a fully managed container orchestration service that helps you quickly deploy, manage, and scale containerized applications. It deeply integrates with the rest of the AWS platform to provide a secure and easy-to-use solution for running container workloads in the cloud and now on your infrastructure with Amazon ECS Anywhere.

Fargate - AWS Fargate is a technology that you can use with Amazon ECS to run containers without having to manage servers or clusters of Amazon EC2 instances. With Fargate, you no longer have to provision, configure, or scale clusters of virtual machines to run containers. This removes the need to choose server types, decide when to scale your clusters, or optimize cluster packing.

Elastic Container Registry - Amazon Elastic Container Registry (Amazon ECR) is an AWS-managed container image registry service that is secure, scalable, and reliable. Amazon ECR supports private repositories with resource-based permissions using AWS IAM.

CodePipeline - AWS CodePipeline is a continuous delivery service you can use to model, visualize, and automate the steps required to release your software. You can quickly model and configure the different stages of a software release process. CodePipeline automates the steps required to release your software changes continuously.

Terraform - Terraform is an infrastructure-as-code tool that lets you build, change, and version infrastructure safely and efficiently.
