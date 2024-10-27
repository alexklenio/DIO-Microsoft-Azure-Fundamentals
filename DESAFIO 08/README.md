<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="60px" src="https://assets.dio.me/Mo-tlP263KBZIWFaCvplHdmnL4GSLIITz5tzmMUoX7s/f:webp/h:77/q:80/w:77/L2xhYl9wcm9qZWN0cy9iYWRnZXMvY2E0NTA1ZmYtNTI2YS00ZGZkLWI3ZTAtZDhhZTEwMDdiNTRjLnBuZw"></a>
    <span> 
Microsoft Azure - 
Otimizando Custos no Azure</span>
</h1>

Repositório desenvolvido para fins didáticos, com a disponibilização de materiais de apoio para o lab **Microsoft Azure - 
Otimizando Custos no Azure** da [Digital Innovation One](https://www.dio.me/).

[![Link do Lab](https://img.shields.io/badge/▶-000?style=for-the-badge&logo=movie&logoColor=E94D5F)](https://web.dio.me/lab/identidade-acesso-e-seguranca-laboratorio/learning/d4d096b1-f66e-48f2-8a68-32bd50aa4028) 
[![Link do Lab](https://img.shields.io/badge/Acesse%20o%20Lab%20na%20Plataforma-E94D5F?style=for-the-badge)](https://web.dio.me/lab/identidade-acesso-e-seguranca-laboratorio/learning/d4d096b1-f66e-48f2-8a68-32bd50aa4028)

## Objetivo
Como resolução do Lab7, módulo 2, repasso um resumo de tudo visto, aprendido e discutido no módulo
   
## Resposta do Lab

O gerenciamento eficaz de custos no Azure é fundamental para maximizar o valor dos serviços em nuvem enquanto se mantém dentro do orçamento. Este guia abrangente fornece insights sobre as melhores práticas, ferramentas e estratégias para otimizar seus gastos no Azure.

---

## 1. Compreendendo o TCO (Total Cost of Ownership) 📊

O TCO é crucial para entender o custo real de migrar para a nuvem. A Calculadora de TCO do Azure é uma ferramenta valiosa nesse processo:

1. Acesse a [Calculadora de TCO do Azure](https://azure.microsoft.com/en-us/pricing/tco/calculator/).
2. Configure seu cenário atual, incluindo servidores, armazenamento e rede.
3. Configure o cenário equivalente no Azure.
4. Compare os custos para tomar decisões informadas sobre a migração.
---

## 2. Ferramentas de Gerenciamento de Custos no Azure 🛠️

### 2.1 Azure Cost Management + Billing

Esta ferramenta é essencial para monitorar, analisar e otimizar seus custos no Azure:

- **Visão Geral de Custos**: Fornece relatórios detalhados sobre o uso e custos dos serviços.
- **Análise de Custo**: Explore e visualize seus gastos em diferentes períodos e recursos.
- **Orçamentos e Alertas**: Configure limites de gastos e receba notificações quando atingir esses limites. 

### 2.2 Azure Advisor

Oferece recomendações personalizadas para otimizar custos, incluindo:
- Sugestões para redimensionamento de VMs
- Identificação de recursos ociosos
- Recomendações para reservas de instâncias
  
---

## 3. Estratégias de Otimização de Custos 💡

### 3.1 Seleção Adequada de Recursos

- **Escolha o Tamanho Correto de VM**: Utilize VMs que atendam às suas necessidades sem excessos.
- **Use VMs de Baixo Custo**: Considere séries B para cargas de trabalho que não necessitam de desempenho constante.
- **Dimensionamento Automático**: Configure o auto-scaling para ajustar recursos conforme a demanda.

### 3.2 Otimização de Armazenamento

- **Camadas de Armazenamento**: Utilize Hot para dados acessados frequentemente, Cool para acesso menos frequente, e Archive para dados raramente acessados.
- **Lifecycle Management**: Automatize a movimentação de dados entre camadas e a exclusão de dados antigos.

### 3.3 Instâncias Reservadas e Benefícios Híbridos

- **Instâncias Reservadas**: Obtenha descontos significativos com compromissos de 1 ou 3 anos.
- **Azure Hybrid Benefit**: Utilize licenças existentes de Windows Server e SQL Server para reduzir custos.

### 3.4 Gerenciamento de Recursos Ociosos

- **Automação de Desligamento**: Use Azure Automation para desligar VMs em períodos ociosos.
- **Revisão Regular**: Identifique e elimine recursos não utilizados.

### 3.5 Otimização de Rede

- **Minimize Tráfego Entre Regiões**: Mantenha serviços na mesma região quando possível.
- **Use CDN ou Azure Front Door**: Otimize a entrega de conteúdo e reduza custos de transferência de dados.

---

## 4. Monitoramento e Controle Contínuo 👀

### 4.1 Configuração de Alertas

Como mostrado na terceira imagem, configure alertas de orçamento para ser notificado quando os gastos se aproximarem dos limites definidos.

### 4.2 Uso de Tags

Aplique tags aos recursos para categorizar e rastrear custos por departamento, projeto ou ambiente. Isso facilita a alocação precisa de custos entre diferentes unidades de negócios.

### 4.3 Revisões Periódicas

Realize análises regulares dos seus recursos e gastos. Utilize o Azure Advisor para obter insights sobre possíveis otimizações.

---

## 5. Considerações Finais 🎯

A otimização de custos no Azure é um processo contínuo que requer atenção constante e ajustes. Ao implementar estas práticas e utilizar as ferramentas disponíveis, você pode significativamente reduzir seus gastos na nuvem sem comprometer a performance ou a segurança.

Lembre-se de que o cenário de custos no Azure é dinâmico, como ilustrado na segunda imagem, onde vemos uma mudança significativa na distribuição de custos entre o ambiente local e o Azure. No Azure, a computação representa 83% dos custos, enquanto o data center e a rede têm seus custos reduzidos ou eliminados.

Ao seguir este guia e manter-se atualizado com as últimas ofertas e ferramentas do Azure, você estará bem posicionado para otimizar seus investimentos em nuvem e maximizar o retorno sobre o investimento (ROI) de sua infraestrutura de TI.

⭐ Obrigado por chegar até aqui e sintas-e a vontade para contribuir e deixar uma estrelinha! (**star**) 
