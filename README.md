# NodeJS-ECS-Terraform
Deploying a flask application to AWS ECS via AWS CodePipeline, and all resources provisioned by terraform.


The major components of our implementation here are:

GitHub to house the source code
ECR to host the docker image
ECS to host the deployed application. A good alternative would also be EBS.
CodePipeline to continuously deploy future versions of our application
Terraform to manage the provisioning of our resources easily
