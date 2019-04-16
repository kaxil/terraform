# Terraform for Astronomer for GCP

Under construction

[Terraform](https://www.terraform.io/) is a simple and powerful tool that lets us write, plan and create infrastructure as code.

## Getting Started
### Prerequisites
1. [Install](https://learn.hashicorp.com/terraform/getting-started/install) Terraform.

### Configure
Configure the variables in `default.tfvars` with values relevant to your project.

### Initialize
`terraform init`
## Build Infrastructure
### Plan
`terraform plan -var-file default.tfvars`
### Apply
`terraform apply -var-file default.tfvars`
