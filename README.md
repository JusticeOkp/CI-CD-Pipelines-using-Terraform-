# CI-CD-Pipelines-using-Terraform
How to Deploy Cloud-Agnostic Jenkins CI/CD Pipelines using Terraform

## This project was practice using Jenkins as the CI/CD tool to create pipelines.
### Steps:
1. Create a new directory in your CLI for your project. 
2. Create the terraform files(variables.tf, main.tf, and providers.tf) I provided the code I used for my configuration.
3. Deploy the AWS Resources created in the terraform configuration.(Run a Terraform init, Terraform plan, and then Terraform apply)
4. Access Jenkins by navigating to the public IP address of your instance followed by “:8080”.
5. Log into the instance using AWS CLI, to test if it is configured correctly. 
6. To tear down your architecture use Terraform destroy.
