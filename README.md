# resumo-do-lab
# AZURE: Computação em Nuvem

## Descrição do Projeto

Este projeto tem como objetivo resumir o lab da [DIO](https://www.dio.me/), computação em nuvem, utilizando a plataforma Microsoft Azure. As atividades foram realizadas como parte do curso na DIO, e envolvem a familiarização com o ambiente da Microsoft Azure e para isso vamos resumir os primeiros passos para configurar o ambiente, assim como alguns dos principais serviços disponiveis.

## Objetivos

- Entender a arquitetura de nuvem.
- Configurar o ambiente de desenvolvimento Azure.
- Explorar e entender os principais recursos do Azure.

## Configurando o Ambiente Azure

### - Acesso ao Portal Azure:

1. Crie uma conta e faça login na plataforma [Azure](https://azure.microsoft.com/pt-br/).
2. Com o login efetuado, acesse o [portal Azure](https://portal.azure.com/) e será direcionado para a seguinte tela:
![image](https://github.com/user-attachments/assets/b38b40ac-c79d-44e9-b869-76a15c5d98c6)

### - Mudando a linguagem na Plataforma:

Caso tenha configurado erroneamente a liguagem ou queira muda-lá apos um tempo. Então:
1. Acesse a engrenagem no canto superior direito. Conforme a imagem abaixo ou [clique aqui](https://portal.azure.com/#settings):
![image](https://github.com/user-attachments/assets/61fca220-bb88-4cc7-9336-1fa17455ff58)


2. Em seguida, localize na tela "Idioma + região", conforme a seguir:
![image](https://github.com/user-attachments/assets/a0f8179b-8e65-420b-a77a-72fefb3fbbbf)

3. Sendo assim, podera escolher a conforme desejar e não esqueça de aplicar as modificações, no centro inferior da tela.

### - Mudando o Tema:

1. Para mudar o tema do Portal Azure [clique aqui](https://portal.azure.com/#settings).
2. Vá em "Aparência + vistas de arranque".
3. Em seguida, selecione o "Comportamento do menu", o "Comportamento do menu de serviço", o "Tema" e a "Pagina de arranque" que preferir.

## Explorando Alguns dos Principais Serviços:

Atualmente, o Portal Azure oferece uma ampla gama de serviços que podem atender diversas necessidades, desde infraestrutura até inteligência artificial. A escolha dos serviços mais adequados dependerá do seu objetivo e das demandas do projeto.

Neste projeto, irei destacar os principais serviços apresentados durante o lab da DIO, além de mencionar alguns serviços que chamaram a minha atenção. Esses serviços fornecem uma base sólida para a exploração da nuvem e para o desenvolvimento de soluções inovadoras. No entanto, sinta-se à vontade para contribuir e sugerir outros serviços que possam enriquecer a apresentação e expandir o alcance do projeto.

Acessando a opção "Todos os serviços", disponivel na barra lateral esquerda terá acesso as categorias de:

### - Análise
Nessa categoria irei me aprofundar um pouco mais devido o interesse na área. Bom, o Azure tem várias ferramentas para ajudar a analisar grandes volumes de dados. Aqui estão algumas que eu conheci:

#### 1. Azure Synapse Analytics:
Uma plataforma que combina análise de big data e data warehouse. Ideal para rodar consultas em dados grandes e complexos de forma integrada.

#### 2. Azure Databricks:
Uma plataforma que funciona com Apache Spark, ótima para criar pipelines de dados e rodar machine learning em grande escala. É bem integrada com o Azure, facilitando o uso.

#### 3. Data Lake Analytics:
Um serviço que processa grandes volumes de dados sem que você precise se preocupar com a infraestrutura. Ele permite rodar consultas em dados não estruturados armazenados no Data Lake.

#### 4. Data Lake Storage Gen1:
Um local seguro e escalável para armazenar grandes quantidades de dados que não estão organizados (não estruturados). É útil para armazenar tudo o que não cabe em um banco de dados tradicional.

#### 5. Apache Airflow™ on Astro:
É uma versão do Apache Airflow, usada para automatizar e organizar tarefas complexas, especialmente em pipelines de dados.

#### 6. Power BI Incorporado:
Permite que você incorpore relatórios e dashboards interativos do Power BI diretamente em aplicativos personalizados, facilitando o compartilhamento de insights.

#### 7. Azure Data Explorer:
Um serviço rápido e escalável para explorar e analisar grandes volumes de dados em tempo real. Ele é ideal para consultas rápidas em dados de logs e telemetria.

#### 8. Stream Analytics:
Um serviço de análise em tempo real para processar e analisar dados que vêm de fontes como sensores e dispositivos IoT.

#### 9. Hubs de Eventos:
Um serviço de ingestão de dados em tempo real, ideal para capturar e processar milhões de eventos de dispositivos e sistemas conectados.
Computação

### - Computação

Há também alguns serviços voltados para computação no Azure:

#### 1. Máquinas Virtuais (VMs):
O Azure oferece VMs que você pode configurar conforme suas necessidades para rodar aplicativos, fazer testes, ou hospedar servidores.

#### 2. Azure Kubernetes Service (AKS):
Um serviço para gerenciar contêineres com Kubernetes no Azure. Ele facilita a implantação e o gerenciamento de aplicativos em contêineres.

#### 3. Funções do Azure (Azure Functions):
Um serviço que permite rodar pequenos pedaços de código sem precisar gerenciar servidores, ideal para automatizar tarefas.

### - Redes

Para a parte de redes no Azure, existem várias opções para configurar e gerenciar o tráfego de rede:

#### 1. Azure Virtual Network (VNet):
Isso permite que você crie redes privadas no Azure, conectando seus recursos de forma segura.

#### 2. Azure Load Balancer:
Um serviço que distribui o tráfego de rede entre vários servidores para garantir maior disponibilidade e desempenho.

#### 3. VPN Gateway:
Uma solução para conectar suas redes locais ao Azure por meio de uma VPN segura.

### - Armazenamento

Aqui estão os serviços de armazenamento no Azure:

#### 1. Blob Storage:
Um serviço de armazenamento para grandes quantidades de dados não estruturados, como imagens, vídeos e backups.

#### 2. Discos Gerenciados:
São discos virtuais usados para armazenar dados em VMs, com backup e replicação automática.

#### 3. Azure Files:
Um serviço de compartilhamento de arquivos na nuvem, que pode ser acessado via protocolo SMB, como um servidor de arquivos tradicional.

### - Bases de Dados

O Azure oferece vários serviços de bancos de dados, como:

#### 1. Azure SQL Database:
Um banco de dados relacional na nuvem que oferece alta disponibilidade e escala automática.

#### 2. Cosmos DB:
Um banco de dados NoSQL distribuído globalmente, ideal para aplicativos que precisam de baixa latência e alta disponibilidade.

#### 3. Azure Database for MySQL/PostgreSQL:
Bancos de dados relacionais gerenciados na nuvem, compatíveis com MySQL e PostgreSQL, para quem já utiliza essas tecnologias.

### - Contentores

Popularmente chamados de Contêineres, são serviços destinados para gerenciar aplicativos, e adivinha na Azure também existem esses serviços:

#### 1. Azure Kubernetes Service (AKS):
Gerencia e orquestra contêineres Kubernetes, facilitando a implementação de aplicativos em contêineres.

#### 2. Azure Container Instances (ACI):
Permite executar contêineres sem a necessidade de gerenciar a infraestrutura, ideal para cenários rápidos e temporários.

#### 3. Azure Container Registry:
Um repositório para armazenar e gerenciar imagens de contêineres, que pode ser usado com o AKS ou outros serviços.

### - AI + Machine Learning

Por fim, chegamos na famosa IA para fechamos com chave de ouro este resumão... Sendo assim, irei deixar aqui algumas ferramentas de IA e Machine Learning no Azure:

#### 1. Azure Machine Learning:
Uma plataforma completa para criar, treinar, e implantar modelos de machine learning na nuvem.

#### 2. Cognitive Services:
Um conjunto de APIs de IA que permitem adicionar funcionalidades como reconhecimento de fala, visão computacional e processamento de linguagem natural aos aplicativos.

#### 3. Bot Service:
Um serviço para criar e gerenciar chatbots inteligentes que podem interagir com usuários por meio de texto ou fala.

