# Curso Containers - LinuxTips

Este repositório contém os arquivos e configurações utilizados no curso de containers da LinuxTips, com foco em práticas envolvendo infraestrutura como código e ambientes virtualizados.

## Estrutura do Repositório

```
.
├── .terraform/               # Configurações e arquivos gerados pelo Terraform
├── environment/              # Configurações específicas para diferentes ambientes
│   └── dev/                  # Arquivos e definições para o ambiente de desenvolvimento
├── .git/                     # Metadados do repositório Git
```

## Requisitos

- **Terraform**: Certifique-se de ter o Terraform instalado. [Instruções de instalação](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)
- **Git**: Necessário para versionamento e colaboração.

## Como Usar

### 1. Clonar o Repositório

```bash
git clone https://github.com/jeansemolini/linuxtips-curso-containers-vpc.git
cd linxutips-curso-containers-vpc
```

### 2. Configurar o Ambiente

Certifique-se de navegar para o diretório do ambiente desejado (por exemplo, `environment/dev`) e ajustar as variáveis no arquivo `terraform.tfvars` de acordo com sua necessidade.

### 3. Inicializar o Terraform

```bash
terraform init
```

### 4. Planejar as Alterações

```bash
terraform plan
```

### 5. Aplicar as Alterações

```bash
terraform apply
```

## Estrutura de Ambientes

O diretório `environment` organiza os arquivos relacionados a diferentes ambientes (como desenvolvimento, homologação ou produção). Cada subdiretório contém as configurações específicas para seu respectivo ambiente.
