# ☁️ Armazenamento no Azure

## 📄 Descrição
Este resumo explora as principais opções e serviços de armazenamento no **Microsoft Azure**, abordando desde conceitos básicos até ferramentas avançadas para migração e gerenciamento de dados. O objetivo é fornecer um panorama completo das funcionalidades de armazenamento na nuvem e como utilizá-las para garantir segurança, alta disponibilidade e desempenho.

## 🗂️ Tópicos Principais

### 🔹 Introdução
O **Armazenamento no Azure** é fundamental para atender a uma ampla gama de necessidades, como backup, arquivamento, gerenciamento de grandes volumes de dados e suportar sistemas de alta disponibilidade. 

[Saiba mais sobre o Armazenamento no Azure](https://docs.microsoft.com/pt-br/azure/storage/)

### 🔹 Redundância e Serviços de Armazenamento
- **LRS (Locally Redundant Storage)**: Mantém três cópias dos dados dentro de um único datacenter. Garantia de disponibilidade: **99,9%**.
- **ZRS (Zone Redundant Storage)**: Distribui dados entre diferentes zonas de disponibilidade. Garantia de disponibilidade: **99,99%**.
- **GRS (Geo-Redundant Storage)**: Replica dados entre duas regiões, com uma durabilidade de **99,99999999999999%**.
- **RA-GRS (Read-Access Geo-Redundant Storage)**: Adiciona a capacidade de leitura dos dados na região secundária. Garantia de leitura de **99,99%**.

[Saiba mais sobre Redundância no Azure](https://docs.microsoft.com/pt-br/azure/storage/common/storage-redundancy)

### 🔹 Pontos de Extremidades Públicos e Camadas de Acesso
Entenda como o **Azure** utiliza pontos de extremidade públicos e camadas de acesso para otimizar a segurança e o controle sobre os dados.

[Saiba mais sobre Pontos de Extremidades](https://docs.microsoft.com/pt-br/azure/storage/blobs/storage-blobs-introduction)

### 🔹 Migrações para o Azure
O Azure oferece várias soluções para migração de dados, como o **AzCopy** e o **Azure Data Box**, que facilitam o processo de transferência de grandes volumes de dados de ambientes locais para a nuvem.

- **AzCopy**: Uma ferramenta de linha de comando para copiar dados para o **Azure Blob Storage**.  
  [Documentação do AzCopy](https://learn.microsoft.com/pt-br/azure/storage/common/storage-use-azcopy-v10)
  
- **Azure Data Box**: Um dispositivo físico para transferências em larga escala para o **Azure**.  
  [Documentação do Azure Data Box](https://learn.microsoft.com/pt-br/azure/databox/)

### 🔹 Opções de Gerenciamento de Arquivos
Gerenciar arquivos em grande escala no **Azure** pode ser feito com ferramentas poderosas como o **AzCopy** para operações rápidas e o **Data Box** para migrações físicas de grandes volumes de dados.

---

## 📘 Referências
- [Documentação Oficial do Armazenamento no Azure](https://docs.microsoft.com/pt-br/azure/storage/)
- [AzCopy - Transferência de Dados](https://learn.microsoft.com/pt-br/azure/storage/common/storage-use-azcopy-v10)
- [Azure Data Box - Migração de Dados](https://learn.microsoft.com/pt-br/azure/databox/)

