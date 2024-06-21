# M10SEM9

# Pré-requisitos
Para fazer esse tutorial é necessário atender a alguns pré-requisitos. Como em sua máquina, você deve ter:

[Terraform CLI](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)
    
[AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
    
Uma conta da AWS (no meu caso, utilizamos a AWS Academy)
    
Além disso, precisamos das credenciais da conta da AWS: aws_access_key_id, aws_secret_access_key e aws_session_token. 

# Passo a Passo

- Crie uma pasta com o comando 

```
mkdir learn-terraform-aws-instance
``` 

- Entre na pasta e crie o arquivo main.tf, com esse comando: 

```
echo. > main.tf 
```

- Depois de uma série de comandos como:

1- Inicializar o diretório
```
terraform init
```

2- Formatar e Validar o arquivo main.tf
```
terraform fmt
```

```
terraform validate
```

3- Por fim temos o camando no qual cria a infraestrutura em si, e na aws aparece a EC2 criada já que no arquivo main.tf provisiona uma instância EC2.

```
terraform apply
```
Nesse comando ao final também aparece a opção de destruir a instância criada.
