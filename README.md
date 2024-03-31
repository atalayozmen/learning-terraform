**Project Setup**
- Run `terraform init` to install provider files, which is aws in this case.
- Run `terraform fmt` to format your configuration
- Run `terraform validate` to validate the formatting of configuration

**Deployment**

- Set access key id and secret access key in your terminal which you create from IAM console:

`export AWS_ACCESS_KEY_ID={your-access-key}`

`export AWS_SECRET_ACCESS_KEY={your-secret-access-key}`

- Run `terraform apply` to create the infrastructure 
