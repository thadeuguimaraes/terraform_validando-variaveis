# terraform_validando-variaveis

Este projeto utiliza Terraform para provisionar recursos na AWS e garantir a validação de variáveis com precondition e postcondition.

## Precondition e Postcondition

O Terraform irá verificar se as condições pré e pós definidas no arquivo `terraform.tfvars `estão de acordo antes de provisionar os recursos na AWS. Caso alguma das condições não sejam atendidas, o Terraform retornará um erro e não aplicará as mudanças.
