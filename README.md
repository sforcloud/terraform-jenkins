# Create a Jenkins CI server using Terraform

Provisioning a Jenkins CI server manually can be error-prone and time-consuming, so I shall be configuring the Jenkins Continuous Server (CI) using Infrastructure as Code (IaC).

## Pre-Requisites

1. Create a key pair [click here for steps](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-key-pairs.html#having-ec2-create-your-key-pair)

2. Feel free to update the *terraform.tfvars* with your own values or use the default values

## Commands to execute

`terraform init`

`terraform plan`

`terraform apply -auto-approve`
