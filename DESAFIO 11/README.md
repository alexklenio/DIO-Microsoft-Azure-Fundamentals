<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="60px" src="https://assets.dio.me/Mo-tlP263KBZIWFaCvplHdmnL4GSLIITz5tzmMUoX7s/f:webp/h:77/q:80/w:77/L2xhYl9wcm9qZWN0cy9iYWRnZXMvY2E0NTA1ZmYtNTI2YS00ZGZkLWI3ZTAtZDhhZTEwMDdiNTRjLnBuZw"></a>
    <span> 
Microsoft Azure - Monitoramento Inteligente com o Azure</span>
</h1>

Repositório desenvolvido para fins didáticos, com a disponibilização de materiais de apoio para o lab **Microsoft Azure - Monitoramento Inteligente com o Azure** da [Digital Innovation One](https://www.dio.me/).

[![Link do Lab](https://img.shields.io/badge/▶-000?style=for-the-badge&logo=movie&logoColor=E94D5F)](https://web.dio.me/project/ferramentas-de-monitoramento-do-azure-laboratorio/learning/2ae90731-2c11-4b3f-b491-1664548ece34?back=/track/microsoft-azure-essentials) 
[![Link do Lab](https://img.shields.io/badge/Acesse%20o%20Lab%20na%20Plataforma-E94D5F?style=for-the-badge)](https://web.dio.me/project/ferramentas-de-monitoramento-do-azure-laboratorio/learning/2ae90731-2c11-4b3f-b491-1664548ece34?back=/track/microsoft-azure-essentials)

## Objetivo
Como resolução do Lab11, módulo 3, repasso um resumo de tudo visto, aprendido e discutido no módulo
   
## Resposta do Lab

## Azure Monitor 📊

O **Azure Monitor** é a plataforma central de monitoramento do Azure que coleta e analisa dados de métricas e logs em tempo real.

### Principais Funcionalidades
- Coleta de métricas e logs de recursos do Azure e de serviços em execução na nuvem.
- Painéis de monitoramento personalizados.
- Integração com alertas para monitoramento proativo.

### Como Configurar
1. Acesse o [Portal do Azure](https://portal.azure.com/).
2. Navegue até "Azure Monitor" usando a barra de pesquisa.
3. Em "Configurações", ative a coleta de dados para as fontes desejadas.
4. Configure alertas na seção "Alertas" para monitorar eventos e métricas específicas.

### Exemplo de Uso
- Monitore o desempenho de VMs, bancos de dados e redes.
- Configure alertas com base em thresholds de métricas específicas.

---

## Azure Application Insights 🔍

O **Azure Application Insights** é uma ferramenta de monitoramento de desempenho de aplicativos (APM) que permite monitorar suas aplicações em tempo real.

### Principais Funcionalidades
- Rastreio de desempenho e falhas de aplicativos web e serviços.
- Monitoramento de telemetria, como tempo de resposta, erros e uso de recursos.
- Identificação automática de gargalos e anomalias no código.

### Como Implementar
1. No Portal do Azure, crie uma nova instância de Application Insights.
2. Copie a chave de Instrumentação fornecida.
3. Adicione o SDK do Application Insights à sua aplicação:
   - Para .NET: Adicione o pacote NuGet `Microsoft.ApplicationInsights.AspNetCore`.
   - Para outras linguagens, consulte a documentação específica.
4. Configure o serviço com a chave de Instrumentação.

### Exemplo de Uso
- Monitoramento de aplicativos .NET, Java, Node.js ou Python.
- Diagnóstico de lentidão em requisições HTTP ou falhas em dependências externas.

---

## Azure Log Analytics 📝

O **Azure Log Analytics** é uma ferramenta para consulta e análise de logs coletados de diferentes fontes no Azure.

### Principais Funcionalidades
- Centralização de logs de infraestrutura, rede e aplicativos.
- Linguagem de consulta Kusto para criar consultas personalizadas.
- Criação de painéis e relatórios detalhados com base nos dados de log.

### Como Utilizar
1. Crie um workspace de Log Analytics no Portal do Azure.
2. Configure a coleta de logs acessando "Fontes de Dados" no workspace.
3. Use o Kusto Query Language (KQL) para criar consultas personalizadas.
4. Salve e compartilhe relatórios baseados nas consultas realizadas.

### Exemplo de Uso
- Analisar logs de segurança de diferentes serviços.
- Monitorar falhas em VMs ou outros recursos do Azure.

---

## Azure Service Health 🏥

O **Azure Service Health** fornece insights sobre o status dos serviços do Azure que você está usando, além de notificações sobre problemas ou manutenções planejadas.

### Principais Funcionalidades
- Informações personalizadas sobre incidentes que afetam seus serviços.
- Alertas sobre atualizações ou interrupções de serviço.
- Visualização de histórico de status de serviços.

### Como Acessar
1. No Portal do Azure, navegue até "Service Health".
2. Visualize o estado atual dos serviços, histórico de incidentes e programações de manutenção.
3. Configure alertas para ser notificado sobre eventos que possam impactar seus recursos.

### Exemplo de Uso
- Receber alertas sobre interrupções em regiões específicas.
- Planejar ações corretivas durante manutenções programadas.

---

## Azure Advisor 💡

O **Azure Advisor** é um serviço de recomendação que fornece conselhos personalizados para otimizar o uso de recursos do Azure.

### Principais Funcionalidades
- Análise de configurações e práticas recomendadas.
- Recomendações para melhorar segurança, desempenho e eficiência de custo.

### Como Utilizar
1. No Portal do Azure, navegue até "Azure Advisor".
2. Revise as recomendações agrupadas em categorias como "High Availability", "Security", "Performance" e "Cost".
3. Siga as orientações para aplicar melhorias em seus recursos.

---

## Network Watcher 🌐

O **Network Watcher** é uma ferramenta que fornece insights sobre a saúde e o desempenho da rede.

### Como Implementar
1. No Portal do Azure, habilite o Network Watcher para a região desejada.
2. Utilize ferramentas como "VPN Diagnostics", "Network Performance Monitor" e "Connection Monitor".
3. Configure alertas de rede para monitorar eventos e condições específicas.

---

## Integrando com Grafana 📈

O **Grafana** é uma ferramenta de visualização que pode ser integrada ao Azure Monitor para criar dashboards personalizados.

### Como Integrar
1. Adicione o Azure Monitor como fonte de dados no Grafana.
2. Configure a conexão fornecendo as credenciais necessárias.
3. Crie dashboards personalizados utilizando a interface do Grafana para visualizar métricas e dados coletados pelo Azure Monitor.

---

## Conclusão 🎓

Parabéns por concluir este guia abrangente sobre Monitoramento Inteligente no Azure! Você agora possui um conhecimento sólido das principais ferramentas e práticas para manter seus recursos Azure otimizados e funcionando de forma eficiente.

Lembre-se de que o aprendizado é contínuo no mundo da tecnologia em nuvem. Continue explorando e aprofundando seus conhecimentos em Azure, pois o mercado está em constante evolução.

### Recursos Adicionais
- [Documentação Oficial do Azure Monitor](https://docs.microsoft.com/azure/azure-monitor/)
- [Azure Application Insights Overview](https://docs.microsoft.com/azure/azure-monitor/app/app-insights-overview)
- [Azure Log Analytics](https://docs.microsoft.com/azure/azure-monitor/logs/log-analytics-overview)
- [Azure Service Health](https://docs.microsoft.com/azure/service-health/overview)

⭐ Obrigado por chegar até aqui e sintas-e a vontade para contribuir e deixar uma estrelinha! (**star**) 
