<!-- BEGIN_TF_DOCS -->
## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | 5.82.2 |
| <a name="provider_aws.secondary"></a> [aws.secondary](#provider\_aws.secondary) | 5.82.2 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [aws_route53_record.primary](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route53_record) | resource |
| [aws_route53_record.secondary](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route53_record) | resource |
| [aws_api_gateway_domain_name.primary](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/api_gateway_domain_name) | data source |
| [aws_api_gateway_domain_name.secondary](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/api_gateway_domain_name) | data source |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_api_dns_name"></a> [api\_dns\_name](#input\_api\_dns\_name) | n/a | `any` | n/a | yes |
| <a name="input_project_name"></a> [project\_name](#input\_project\_name) | n/a | `any` | n/a | yes |
| <a name="input_region_primary"></a> [region\_primary](#input\_region\_primary) | n/a | `any` | n/a | yes |
| <a name="input_region_secondary"></a> [region\_secondary](#input\_region\_secondary) | n/a | `any` | n/a | yes |
| <a name="input_route53_hosted_zone"></a> [route53\_hosted\_zone](#input\_route53\_hosted\_zone) | n/a | `any` | n/a | yes |
| <a name="input_routing"></a> [routing](#input\_routing) | n/a | <pre>object({<br/>    us-east-1 = number<br/>    sa-east-1 = number<br/>  })</pre> | n/a | yes |

## Outputs

No outputs.
<!-- END_TF_DOCS -->