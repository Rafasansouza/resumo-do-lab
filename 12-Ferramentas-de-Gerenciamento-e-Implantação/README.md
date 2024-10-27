# 🌐 Laboratório de Ferramentas de Implantação de Recursos no Azure 🚀

Neste laboratório, parte do Bootcamp da DIO sobre **Ferramentas de Implantação de Recursos no Azure**, aprendemos a utilizar diferentes abordagens para criar, gerenciar e automatizar recursos no Azure.

## 📝 Tópicos Abordados

1. **Azure Portal** 🌐
   - Criamos e gerenciamos recursos diretamente pelo Azure Portal, uma interface gráfica amigável que oferece facilidade e rapidez para a configuração inicial.
   - **Documentação**: [Azure Portal](https://docs.microsoft.com/en-us/azure/azure-portal/)

2. **Azure PowerShell** 🖥️
   - Exploramos o uso do PowerShell para criar e gerenciar recursos via linha de comando. Aprendemos a automatizar tarefas, como a criação de Resource Groups e máquinas virtuais.
   - **Comandos Utilizados**:
     ```powershell
     # Login no Azure
     Connect-AzAccount

     # Criar um Resource Group
     New-AzResourceGroup -Name "MyResourceGroup" -Location "EastUS"

     # Implantar uma VM
     New-AzVM -ResourceGroupName "MyResourceGroup" -Name "MyVM" -Location "EastUS"
     ```
   - **Documentação**: [Azure PowerShell](https://docs.microsoft.com/en-us/powershell/azure/new-azureps-module-az)

3. **Azure CLI** 🖱️
   - Utilizamos a CLI do Azure para realizar implantações diretamente do terminal. Exploramos a simplicidade e flexibilidade dos comandos para criar e gerenciar recursos.
   - **Comandos Utilizados**:
     ```bash
     # Login no Azure
     az login

     # Criar um Resource Group
     az group create --name MyResourceGroup --location eastus

     # Implantar uma VM
     az vm create --resource-group MyResourceGroup --name MyVM --image UbuntuLTS --admin-username azureuser --generate-ssh-keys
     ```
   - **Documentação**: [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/)

4. **ARM Templates** 📜
   - Criamos templates JSON para descrever e automatizar a infraestrutura, garantindo implantações consistentes e reutilizáveis.
   - **Exemplo de ARM Template**:
     ```json
     {
       "$schema": "https://schema.management.azure.com/schemas/2019-04-01/deploymentTemplate.json#",
       "contentVersion": "1.0.0.0",
       "resources": [
         {
           "type": "Microsoft.Compute/virtualMachines",
           "apiVersion": "2021-03-01",
           "name": "MyVM",
           "location": "EastUS",
           "properties": {
             "hardwareProfile": {
               "vmSize": "Standard_DS1_v2"
             },
             "osProfile": {
               "computerName": "MyVM",
               "adminUsername": "azureuser",
               "adminPassword": "Password123!"
             }
           }
         }
       ]
     }
     ```
   - **Documentação**: [ARM Templates](https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/overview)

5. **Azure Bicep** 🏗️
   - Utilizamos o Bicep, uma linguagem declarativa que facilita a criação de templates, comparado ao JSON dos ARM Templates. Mais simples e legível!
   - **Documentação**: [Azure Bicep](https://docs.microsoft.com/en-us/azure/azure-resource-manager/bicep/)

6. **Terraform** 🌳
   - Implementamos recursos no Azure usando o Terraform, uma ferramenta multicloud que facilita o gerenciamento de infraestrutura em diferentes provedores.
   - **Documentação**: [Terraform para Azure](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs)

7. **Azure DevOps e GitHub Actions** ⚙️
   - Exploramos a criação de pipelines de CI/CD com Azure DevOps e GitHub Actions, automatizando o deploy e a gestão de infraestrutura de forma contínua.
   - **Documentação**: 
     - [Azure DevOps](https://docs.microsoft.com/en-us/azure/devops/)
     - [GitHub Actions para Azure](https://docs.github.com/en/actions)


## 🌟 Conclusão

Este laboratório demonstrou como diferentes ferramentas podem ser utilizadas para gerenciar e implantar recursos no Azure. Cada ferramenta possui suas características e pontos fortes, e a escolha da ferramenta ideal dependerá da necessidade do ambiente, da equipe e dos requisitos do projeto.

Sinta-se à vontade para sugerir melhorias e explorar mais sobre o tema. O aprendizado sobre o Azure é contínuo, e novas ferramentas e funcionalidades são lançadas regularmente!