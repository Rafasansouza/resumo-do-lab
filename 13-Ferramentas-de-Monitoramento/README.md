# 🛠️ Laboratório: Ferramentas de Monitoramento do Azure

Este laboratório faz parte do bootcamp da DIO sobre **Microsoft Azure** e tem como foco explorar as principais ferramentas de monitoramento que o Azure oferece. O objetivo é aprender a configurar e utilizar essas ferramentas para manter a visibilidade, desempenho, segurança e conformidade dos recursos na nuvem. 

## 🎯 Objetivos do Laboratório

- Utilizar o **Assistente do Azure** para recomendações e otimizações.
- Monitorar a integridade dos serviços com o **Azure Service Health**.
- Configurar e utilizar o **Azure Monitor** para coletar dados de telemetria.
- Criar consultas detalhadas com o **Azure Log Analytics** usando KQL.
- Monitorar o desempenho de aplicativos com o **Application Insights**.
- Configurar alertas no **Azure Alerts** para eventos críticos.
- Diagnosticar problemas de rede com o **Network Watcher**.
- Avaliar a segurança do ambiente com o **Azure Security Center**.
- Analisar custos e orçamentos com o **Azure Cost Management**.

---

## 🖥️ Passo a Passo Detalhado

### 1. **Assistente do Azure e Integridade do Serviço**

**Assistente do Azure** e **Azure Service Health** são ferramentas fundamentais para a gestão proativa do ambiente no Azure.

#### **Assistente do Azure**
O **Assistente do Azure** é uma ferramenta que oferece recomendações de boas práticas, orientações de desempenho, segurança e otimização de custos.

**Passos:**
- Acesse o **Portal do Azure**.
- No menu lateral, clique em **Assistente do Azure**.
- Analise as recomendações para segurança, desempenho, disponibilidade e otimização de custos.
- Implemente as sugestões que forem relevantes para melhorar a eficiência do seu ambiente.

📘 [Documentação do Assistente do Azure](https://docs.microsoft.com/azure/advisor/)

#### **Integridade do Serviço do Azure**
O **Azure Service Health** fornece informações detalhadas sobre a saúde dos serviços do Azure, incluindo notificações sobre interrupções ou manutenções planejadas que possam impactar seus recursos.

**Passos:**
- No **Portal do Azure**, acesse **Service Health** no menu lateral.
- Visualize informações sobre incidentes, interrupções e notificações de manutenção.
- Configure alertas para ser notificado em caso de problemas que possam afetar seus recursos.
- Acesse relatórios detalhados para investigar e agir rapidamente.

📘 [Documentação do Azure Service Health](https://docs.microsoft.com/azure/service-health/)

---

### 2. **Configurando o Azure Monitor**

O **Azure Monitor** é a principal ferramenta de monitoramento do Azure, projetada para fornecer visibilidade sobre o desempenho e a disponibilidade dos recursos.

**Passos:**
- Acesse o **Portal do Azure**.
- Navegue até **Monitor** no menu lateral.
- Configure métricas para monitorar seus recursos, como CPU, memória e uso de rede.
- Crie **Dashboards** personalizados para visualizar métricas e alertas em tempo real.

📘 [Documentação do Azure Monitor](https://docs.microsoft.com/azure/azure-monitor/overview)

---

### 3. **Criando Consultas no Azure Log Analytics**

O **Azure Log Analytics** é uma ferramenta que permite realizar consultas detalhadas nos logs do Azure usando **Kusto Query Language (KQL)**.

**Passos:**
- No Portal do Azure, vá até **Log Analytics Workspaces** e crie um workspace.
- Colete dados dos recursos que deseja monitorar (máquinas virtuais, aplicativos, etc.).
- Utilize **KQL** para criar consultas e extrair insights dos logs.
- Visualize os resultados no painel de **Log Analytics**.

📘 [Documentação do Azure Log Analytics](https://docs.microsoft.com/azure/azure-monitor/logs/log-analytics-overview)

---

### 4. **Monitoramento de Aplicativos com Application Insights**

O **Application Insights** é uma ferramenta de monitoramento voltada para aplicações web, permitindo identificar gargalos e erros.

**Passos:**
- Acesse o Portal do Azure e vá até **Application Insights**.
- Crie um recurso de **Application Insights** para sua aplicação.
- Instale o SDK do Application Insights na sua aplicação.
- Monitore tempos de resposta, erros, exceções e comportamento do usuário em tempo real.

📘 [Documentação do Application Insights](https://docs.microsoft.com/azure/azure-monitor/app/app-insights-overview)

---

### 5. **Configurando Alertas no Azure Alerts**

O **Azure Alerts** permite configurar notificações automáticas para eventos importantes nos seus recursos.

**Passos:**
- No **Azure Monitor**, selecione **Alerts**.
- Crie uma nova regra de alerta, escolhendo o recurso, a condição e o nível de gravidade.
- Defina ações, como enviar e-mails ou disparar webhooks, quando um alerta for acionado.
- Teste a configuração para garantir que as notificações estejam funcionando corretamente.

📘 [Documentação do Azure Alerts](https://docs.microsoft.com/azure/azure-monitor/platform/alerts-overview)

---

### 6. **Diagnosticando Redes com o Network Watcher**

O **Network Watcher** oferece ferramentas para diagnosticar e monitorar a infraestrutura de rede do Azure.

**Passos:**
- No Portal do Azure, vá até **Network Watcher**.
- Habilite o serviço para a região que deseja monitorar.
- Utilize as funcionalidades de **Packet Capture**, **IP Flow Verify** e **Topology** para analisar a conectividade da rede.
- Resolva problemas de conectividade utilizando as informações coletadas.

📘 [Documentação do Network Watcher](https://docs.microsoft.com/azure/network-watcher/network-watcher-monitoring-overview)

---

### 7. **Avaliação de Segurança com o Azure Security Center**

O **Azure Security Center** ajuda a proteger os recursos no Azure, fornecendo recomendações de segurança.

**Passos:**
- Acesse o **Security Center** no Portal do Azure.
- Habilite a avaliação de segurança e aguarde as recomendações.
- Corrija vulnerabilidades de segurança com base nas recomendações.
- Monitore continuamente o estado de segurança dos seus recursos.

📘 [Documentação do Azure Security Center](https://docs.microsoft.com/azure/security-center/)

---

### 8. **Gestão de Custos com o Azure Cost Management**

O **Azure Cost Management** ajuda a monitorar e otimizar seus custos no Azure.

**Passos:**
- Acesse o **Cost Management + Billing** no Portal do Azure.
- Crie e configure **orçamentos** para controlar os gastos.
- Analise relatórios detalhados sobre o consumo de recursos.
- Implemente otimizações sugeridas para reduzir custos.

📘 [Documentação do Azure Cost Management](https://docs.microsoft.com/azure/cost-management/)

---

## 🌟 Conclusão

Neste laboratório, exploramos as principais ferramentas de monitoramento do Azure. Essas ferramentas permitem que você mantenha uma visão detalhada sobre a performance, segurança e custos do seu ambiente na nuvem. O domínio dessas soluções é essencial para uma gestão eficaz e proativa dos recursos no Azure, garantindo conformidade e eficiência.

## 📚 Referências

- [Assistente do Azure](https://docs.microsoft.com/azure/advisor/)
- [Azure Monitor](https://docs.microsoft.com/azure/azure-monitor/overview)
- [Azure Log Analytics](https://docs.microsoft.com/azure/azure-monitor/logs/log-analytics-overview)
- [Application Insights](https://docs.microsoft.com/azure/azure-monitor/app/app-insights-overview)
- [Azure Alerts](https://docs.microsoft.com/azure/azure-monitor/platform/alerts-overview)
- [Network Watcher](https://docs.microsoft.com/azure/network-watcher/network-watcher-monitoring-overview)
- [Azure Security Center](https://docs.microsoft.com/azure/security-center/)
- [Azure Service Health](https://docs.microsoft.com/azure/service-health/)
- [Azure Cost Management](https://docs.microsoft.com/azure/cost-management/)