# ☁️ Lab: Armazenamento no Azure

## 📄 Descrição
Este projeto foi desenvolvido durante o laboratório do bootcamp da **DIO** para praticar o uso de recursos de armazenamento no **Microsoft Azure**. O objetivo é criar uma **Storage Account**, configurar o **Azure Data Box** para migração de grandes volumes de dados, utilizar a ferramenta de linha de comando **AzCopy** para transferência rápida de arquivos, e explorar o **Gerenciador de Armazenamento do Azure**.

## 🛠️ Pré-requisitos
- Conta no [Microsoft Azure](https://azure.microsoft.com/).
- Ferramenta **AzCopy** instalada. [Documentação do AzCopy](https://learn.microsoft.com/pt-br/azure/storage/common/storage-use-azcopy-v10).
- Acesso ao portal do **Azure**.
- Conhecimento básico de comandos CLI.

## 🚀 Passos do Lab

### 1. 🗄️ Criando uma Storage Account no Azure
O primeiro passo é criar uma **Storage Account** no Azure, que será o ponto central de armazenamento de dados.

1. Acesse o [Portal do Azure](https://portal.azure.com/).
2. No menu à esquerda, clique em **"Criar um recurso"** e procure por **"Storage Account"**.
3. Preencha as seguintes informações:
   - **Subscription**: Selecione a assinatura ativa.
   - **Resource Group**: Escolha ou crie um grupo de recursos.
   - **Storage Account Name**: Defina um nome único para a conta de armazenamento.
   - **Region**: Escolha a região de preferência.
   - **Performance**: Selecione entre **Standard** ou **Premium**, dependendo da necessidade.
   - **Replication**: Selecione o tipo de redundância (LRS, ZRS, GRS, RA-GRS) para seus dados.
4. Clique em **Review + Create** e, em seguida, em **Create**.

Após a criação da Storage Account, você pode gerenciar e armazenar dados em diferentes camadas de acesso, como **Blob, Table, File e Queue**.

[Documentação do Azure Storage Account](https://learn.microsoft.com/pt-br/azure/storage/common/storage-account-overview)

### 2. 📦 Configurando o Azure Data Box
O **Azure Data Box** é ideal para quem precisa transferir grandes volumes de dados para a nuvem sem depender da largura de banda da internet.

1. No Portal do Azure, busque por **Azure Data Box** e clique em **Criar**.
2. Preencha os seguintes detalhes:
   - **Nome do Data Box**: Escolha um nome para o dispositivo.
   - **Resource Group**: Selecione o grupo de recursos.
   - **Tipo de Data Box**: Escolha o dispositivo físico de sua preferência (Data Box Disk, Data Box, Data Box Heavy).
3. Siga as instruções do portal para agendar o envio do dispositivo físico.
4. Após receber o dispositivo, conecte-o ao seu sistema e siga as instruções para copiar os dados.

[Documentação do Azure Data Box](https://learn.microsoft.com/pt-br/azure/databox/)

### 3. 🏃‍♂️ Usando o AzCopy para Transferência de Dados
O **AzCopy** é uma ferramenta de linha de comando que facilita a movimentação de dados entre seu ambiente local e o **Azure Blob Storage**.

#### Instalação do AzCopy:
1. Baixe a versão mais recente do **AzCopy** no link abaixo:  
   [Download do AzCopy](https://aka.ms/downloadazcopy)
2. Extraia o arquivo e adicione o caminho do **AzCopy** ao **PATH** do sistema operacional.

#### Comandos principais do AzCopy:
- **Login no Azure:**
   ```bash
   azcopy login

- **Copiar arquivos do sistema local para o Blob Storage:**
    ```bash
    azcopy copy '/local/arquivo.txt' 'https://<storageaccount>.blob.core.windows.net/<container>' --recursive=true

- **Copiar arquivos do Blob Storage para o sistema local:**
    ```bash
    azcopy copy 'https://<storageaccount>.blob.core.windows.net/<container>/arquivo.txt' '/local/destino/' --recursive=true

[Documentação do Azcopy](https://learn.microsoft.com/pt-br/azure/storage/common/storage-use-azcopy-v10?tabs=dnf)

### 🗂️ Gerenciando Dados com o Gerenciador de Armazenamento do Azure
O Azure Storage Explorer é uma ferramenta gráfica que permite gerenciar arquivos armazenados no Azure de forma simples e intuitiva. Com ele, você pode acessar, criar e gerenciar contêineres, blobs e outros serviços de armazenamento.

#### 🛠️ Instalação:
- Baixe o **Azure Storage Explorer** [aqui](https://azure.microsoft.com/pt-br/products/storage/storage-explorer/).
- Instale o programa e faça login com suas credenciais do Azure.

#### 🚀 Funcionalidades:
- Gerencie **Blobs, Queues, Tables e File Shares.**
- **Upload e Download** de arquivos diretamente do seu computador para o Azure Storage.
- Acesse e edite permissões e configurações de contêineres.
- Conecte-se a diferentes contas de armazenamento em uma interface gráfica.

[Documentação do Gerenciador de Armazenamento do Azure](https://learn.microsoft.com/pt-br/azure/storage/)

## 🤝 Contribuições e Melhorias

Espero que este resumo do aprendizado te ajude de alguma forma! Se você tiver sugestões, melhorias ou quiser contribuir de alguma forma, fique à vontade para abrir um *pull request* ou *issue*. Suas ideias e contribuições são sempre bem-vindas! Obrigado. 🖤
