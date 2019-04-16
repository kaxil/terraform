# Terraform for Astronomer for GCP

Under construction

[Terraform](https://www.terraform.io/) is a simple and powerful tool that lets us write, plan and create infrastructure as code. This code will allow you to efficiently provision the infrastructure required to run the Astronomer platform.
## Features
## Getting Started
### Prerequisites
1. [Install](https://learn.hashicorp.com/terraform/getting-started/install) Terraform.

### Configure
Configure the variables in `default.tfvars` with values relevant to your project:

`region` The regional location in which your resources will run.  See a complete list [here](https://cloud.google.com/compute/docs/regions-zones/).

`zone` The zonal location in which your resources will run.  See a complete list [here](https://cloud.google.com/compute/docs/regions-zones/).

`project`

`cluster_name`

`machine_type`

`min_node_count`

`max_node_count`

`node_version`

### Initialize
`terraform init`
## Build Infrastructure
### Plan
`terraform plan -var-file default.tfvars`
### Apply
`terraform apply -var-file default.tfvars`
