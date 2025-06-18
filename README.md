# Guia Rápido: Criando uma Instância Gerenciada de SQL no Azure

Este guia passo a passo ensina como criar uma Instância Gerenciada de SQL no Azure utilizando o Portal do Azure.

## Pré-requisitos

- Uma assinatura ativa do Azure.
- Permissões adequadas para criar recursos no Azure.
- Uma rede virtual (VNet) e sub-rede configuradas ou a criação automática durante o processo.:contentReference[oaicite:7]{index=7}

## Passo 1: Acessar o Portal do Azure

1. Acesse o [Portal do Azure](https://portal.azure.com).
2. No menu à esquerda, selecione **SQL do Azure**.
3. Clique em **+ Criar** para iniciar o processo de criação.:contentReference[oaicite:14]{index=14}

## Passo 2: Configurar a Instância Gerenciada

### Guia Básico

Preencha as informações obrigatórias na guia **Básico**:

- **Assinatura**: Escolha a assinatura desejada.
- **Grupo de recursos**: Selecione um grupo de recursos existente ou crie um novo.
- **Nome da instância gerenciada**: Escolha um nome único para a instância.
- **Região**: Selecione a região onde a instância será provisionada.
- **Método de autenticação**: Escolha **SQL Authentication**.
- **Login de administrador**: Informe um nome de usuário para o administrador.
- **Senha**: Defina uma senha forte para o administrador.:contentReference[oaicite:29]{index=29}

### Guia de Rede

- **Rede virtual**: Escolha uma rede virtual existente ou crie uma nova.
- **Sub-rede**: Selecione uma sub-rede existente ou crie uma nova.
- **Ponto de extremidade público**: Escolha se deseja habilitar o acesso público à instância.:contentReference[oaicite:36]{index=36}

### Guia de Computação + Armazenamento

- **Camada de serviço**: Escolha entre **General Purpose** ou **Business Critical**.
- **vCores**: Selecione o número de vCores desejado.
- **Armazenamento máximo (GB)**: Defina a capacidade de armazenamento necessária.:contentReference[oaicite:43]{index=43}

## Passo 3: Revisar e Criar

1. Revise todas as configurações.
2. Clique em **Criar** para iniciar o provisionamento da instância.:contentReference[oaicite:48]{index=48}

> **Nota**: A implantação de uma instância gerenciada é uma operação de longa duração e pode levar até 6 horas para ser concluída.:contentReference[oaicite:51]{index=51}

## Conclusão

Após a criação, você pode gerenciar sua instância gerenciada de SQL através do Portal do Azure, realizando tarefas como backup, restauração e monitoramento de desempenho.

Para mais detalhes e opções avançadas, consulte a [documentação oficial](https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/instance-create-quickstart?view=azuresql&tabs=azure-portal).

## Contato
Se tiver dúvidas ou sugestões, entre em contato:
- GitHub: [JulianoTurra](https://github.com/JulianoTurra)


