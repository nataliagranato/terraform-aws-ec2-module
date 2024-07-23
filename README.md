# terraform-aws-ec2-module
[![tfsec](https://github.com/nataliagranato/terraform-aws-ec2-module/actions/workflows/tfsec.yml/badge.svg)](https://github.com/nataliagranato/terraform-aws-ec2-module/actions/workflows/tfsec.yml)
<!-- BEGIN_TF_DOCS -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_aws"></a> [aws](#requirement\_aws) | ~> 5.0 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | ~> 5.0 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [aws_instance.web](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/instance) | resource |
| [aws_ami.ubuntu](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/ami) | data source |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_environment"></a> [environment](#input\_environment) | Ambiente da instância. | `string` | `"dev"` | no |
| <a name="input_nome"></a> [nome](#input\_nome) | Nome da instância. | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_instance_ip_addr"></a> [instance\_ip\_addr](#output\_instance\_ip\_addr) | n/a |
<!-- END_TF_DOCS -->