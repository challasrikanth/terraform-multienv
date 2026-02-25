workspaces
=================

if we want to create multiple environment we can make use of terraform workspaces.
terraform will give us special variable called terraform.workspace

1. Workspaces allow you to reuse the same Terraform configuration for multiple environments—dev, stage, prod—without duplicating code.
Benefit:
Less code duplication, easier maintenance.

2. Simple State File Isolation
Each workspace gets its own separate state file (terraform.tfstate).
Benefit:
Avoids mixing resources of different environments by mistake



advantages: -
same code re-use in multi environments


disadvantages:
since code is same, we should be very careful, because it applies to prod also.
