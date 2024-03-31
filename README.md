**Project Setup**
- Run `terraform init` to install provider files, which is aws in this case.
- Run `terraform fmt` to format your configuration
- Run `terraform validate` to validate the formatting of configuration

**Deployment**

- Set access key id and secret access key in your Terraform Cloud organization
- Run `terraform apply` to create the infrastructure
- Run `terraform destroy` to clean up the resources after we are done with it. This will only destroy resources defined in the configuration, and nothing else.
