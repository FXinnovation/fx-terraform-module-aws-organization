# Organization

Creates an organization with accounts.

## Usage

To run this example you need to execute:

```bash
$ terraform init
$ terraform plan
$ terraform apply
```

Note that this example may create resources which can cost money (AWS Elastic IP, for example). Run `terraform destroy` when you don't need these resources.

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 0.12 |

## Providers

No providers.

## Modules

| Name | Source | Version |
|------|--------|---------|
| <a name="module_organization"></a> [organization](#module\_organization) | ../../ | n/a |

## Resources

No resources.

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_access_key"></a> [access\_key](#input\_access\_key) | Credentials: AWS access key. | `string` | `"PLEASE SET THE AWS ACCESS KEY"` | no |
| <a name="input_region"></a> [region](#input\_region) | Region. | `string` | `"ca-central-1"` | no |
| <a name="input_secret_key"></a> [secret\_key](#input\_secret\_key) | Credentials: AWS secret key. Pass this a variable, never write password in the code. | `string` | `"PLEASE SET THE AWS SECRET KEY. DO NOT WRITE YOUR SECRET IN THIS FILE."` | no |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_account_ids"></a> [account\_ids](#output\_account\_ids) | n/a |
| <a name="output_account_names"></a> [account\_names](#output\_account\_names) | n/a |
| <a name="output_arn"></a> [arn](#output\_arn) | n/a |
| <a name="output_id"></a> [id](#output\_id) | n/a |
| <a name="output_master_account_arn"></a> [master\_account\_arn](#output\_master\_account\_arn) | n/a |
| <a name="output_master_account_email"></a> [master\_account\_email](#output\_master\_account\_email) | n/a |
| <a name="output_master_account_id"></a> [master\_account\_id](#output\_master\_account\_id) | n/a |
<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
