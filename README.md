# Module Organization

Creates an a organization with several accounts.

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 0.12 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | n/a |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [aws_organizations_account.organization](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/organizations_account) | resource |
| [aws_organizations_organization.organization](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/organizations_organization) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_account_emails"></a> [account\_emails](#input\_account\_emails) | Emails of the accounts to create. Must be different for each account. | `list(string)` | n/a | yes |
| <a name="input_account_names"></a> [account\_names](#input\_account\_names) | Names of the accounts to create. | `list(string)` | n/a | yes |
| <a name="input_organization_create"></a> [organization\_create](#input\_organization\_create) | Whether to create the organization or not. | `bool` | `true` | no |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_account_count"></a> [account\_count](#output\_account\_count) | Number of sub-accounts created. |
| <a name="output_account_ids"></a> [account\_ids](#output\_account\_ids) | Organization sub-account ids. |
| <a name="output_account_names"></a> [account\_names](#output\_account\_names) | Organization sub-account names. |
| <a name="output_arn"></a> [arn](#output\_arn) | ARN of the organization. |
| <a name="output_id"></a> [id](#output\_id) | Id of the organization. |
| <a name="output_master_account_arn"></a> [master\_account\_arn](#output\_master\_account\_arn) | Main (root) account ARN. |
| <a name="output_master_account_email"></a> [master\_account\_email](#output\_master\_account\_email) | Main (root) account email. |
| <a name="output_master_account_id"></a> [master\_account\_id](#output\_master\_account\_id) | Main (root) account id. |
<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
