More info at <a href="https://www.kidsil.net/2018/10/terraform-workspaces-multiple-deployments">Terraform Workspaces Multiple Deployments - kidsil.net</a>

Make sure you rename `dev.tfvars.example` to `dev.tfvars`

To run:

`terraform apply --var-file=$(terraform workspace show).tfvars`
