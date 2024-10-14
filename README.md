# Basic Terraform Project for an Azure VM

This is my first Terraform project to provision an Azure Linux Virtual Machine using Terraform.

### Steps to Use:

You can clone the repository and ensure that you **remove** the `terraform.tfstate` and `terraform.tfstate.backup` files before running the following commands.

### Create Alias for Terraform:
To shorten the `terraform` command, you can create an alias:

```bash
alias tf=terraform

# Initialize Terraform (downloads providers and modules)
tf init

# Show the execution plan (what Terraform will create, change, or destroy)
tf plan 

# Apply the changes (provisions the VM)
tf apply

