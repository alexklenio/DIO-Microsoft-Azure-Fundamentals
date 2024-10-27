<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="60px" src="https://assets.dio.me/Mo-tlP263KBZIWFaCvplHdmnL4GSLIITz5tzmMUoX7s/f:webp/h:77/q:80/w:77/L2xhYl9wcm9qZWN0cy9iYWRnZXMvY2E0NTA1ZmYtNTI2YS00ZGZkLWI3ZTAtZDhhZTEwMDdiNTRjLnBuZw"></a>
    <span> 
Microsoft Azure - 
Entendendo sobre Segurança e Identidade na Azure</span>
</h1>

Repositório desenvolvido para fins didáticos, com a disponibilização de materiais de apoio para o lab **Microsoft Azure - 
Entendendo sobre Segurança e Identidade na Azure** da [Digital Innovation One](https://www.dio.me/).

[![Link do Lab](https://img.shields.io/badge/▶-000?style=for-the-badge&logo=movie&logoColor=E94D5F)](https://web.dio.me/lab/identidade-acesso-e-seguranca-laboratorio/learning/d4d096b1-f66e-48f2-8a68-32bd50aa4028) 
[![Link do Lab](https://img.shields.io/badge/Acesse%20o%20Lab%20na%20Plataforma-E94D5F?style=for-the-badge)](https://web.dio.me/lab/identidade-acesso-e-seguranca-laboratorio/learning/d4d096b1-f66e-48f2-8a68-32bd50aa4028)

## Objetivo
Como resolução do Lab7, módulo 2, repasso um resumo de tudo visto, aprendido e discutido no módulo
   
## Resposta do Lab

## 1. Introdução 🌟

A segurança e o gerenciamento de identidade são pilares fundamentais na plataforma Azure. Este guia abrangente oferece uma visão detalhada dos principais conceitos, ferramentas e práticas recomendadas para proteger seus recursos e dados na nuvem da Microsoft.

## 2. Microsoft Entra ID (anteriormente Azure Active Directory) 🔑

O Microsoft Entra ID é o coração do gerenciamento de identidade e acesso no Azure.

### 2.1 Configuração Básica

- Acesse o portal do Azure (https://portal.azure.com)
- Procure por "Microsoft Entra ID" na barra de pesquisa
- Explore a visão geral do serviço

### 2.2 Gerenciamento de Usuários e Grupos

- **Adicionar Usuários**: 
  - Navegue até "Usuários" > "Novo usuário"
  - Preencha os detalhes necessários
- **Criar Grupos**: 
  - Acesse "Grupos" > "Novo grupo"
  - Defina o tipo de grupo e atribua membros
- **Atribuir Funções**: Utilize o RBAC (Controle de Acesso Baseado em Funções) para atribuir permissões específicas

### 2.3 Autenticação Multifator (MFA)

- Ative o MFA para aumentar a segurança das contas
- Configure no painel "Segurança" > "Autenticação multifator"
- Defina políticas de MFA para usuários ou grupos específicos

## 3. Controle de Acesso e Políticas 🔒

### 3.1 RBAC (Controle de Acesso Baseado em Funções)

- Acesse o recurso desejado > "Controle de Acesso (IAM)"
- Clique em "Atribuir função" e selecione a função apropriada (ex: Colaborador, Leitor, Proprietário)
- Atribua a função a usuários ou grupos

### 3.2 Azure Policy

- Busque por "Política" no portal Azure
- Crie políticas para definir restrições ou requisitos de segurança
- Aplique políticas em diferentes níveis: assinatura, grupo de recursos ou recurso individual

### 3.3 Acesso Condicional

- Configure no Microsoft Entra ID > "Segurança" > "Acesso condicional"
- Defina condições específicas para acesso a recursos (ex: localização, dispositivo, risco)

## 4. Proteção de Dados 🔐

### 4.1 Criptografia

- **Em Repouso**: Ative a criptografia automática para dados armazenados
- **Em Trânsito**: Utilize HTTPS, SSL/TLS ou IPsec para comunicações seguras

### 4.2 Azure Key Vault

- Crie um novo Key Vault no portal Azure
- Armazene e gerencie chaves de criptografia, segredos e certificados
- Defina políticas de acesso para controlar quem pode acessar os segredos

## 5. Segurança de Rede 🌐

### 5.1 Grupos de Segurança de Rede (NSG)

- Acesse a VM ou Rede Virtual > "Grupos de Segurança de Rede"
- Defina regras de entrada e saída, especificando portas, IPs e protocolos permitidos/bloqueados

### 5.2 Azure Firewall

- Implemente o Azure Firewall para proteção adicional
- Configure regras de filtragem de tráfego entre redes ou com a internet

## 6. Microsoft Defender for Cloud 🛡️

### 6.1 Configuração Inicial

- No portal Azure, busque por "Microsoft Defender for Cloud"
- Explore a visão geral e as principais funcionalidades

### 6.2 Monitoramento de Segurança

- Utilize o painel para uma visão unificada da postura de segurança
- Identifique vulnerabilidades e riscos em seus recursos

### 6.3 Gerenciamento de Incidentes

- Configure alertas para atividades suspeitas
- Responda a incidentes de segurança com recomendações práticas

### 6.4 Avaliação de Conformidade

- Avalie a conformidade com políticas e regulamentos de segurança
- Gere relatórios detalhados para auditorias

## 7. Monitoramento e Auditoria 📊

### 7.1 Azure Monitor

- Configure diagnósticos para rastrear atividades de acesso e login
- Utilize o Log Analytics para análise aprofundada de logs

### 7.2 Revisões Regulares

- Realize auditorias periódicas de permissões e acessos
- Revise logs regularmente para identificar comportamentos suspeitos

## 8. Práticas Recomendadas e Considerações Finais 🌟

- Adote uma abordagem de Segurança Zero Trust
- Mantenha-se atualizado com as últimas ameaças e atualizações de segurança
- Implemente um plano de resposta a incidentes
- Realize treinamentos regulares de conscientização de segurança para sua equipe

## 9. Recursos Adicionais 📚

- [Documentação oficial do Azure](https://docs.microsoft.com/azure/security/)
- [Centro de Confiança da Microsoft](https://www.microsoft.com/trust-center)
- [Blog de Segurança do Azure](https://azure.microsoft.com/blog/topics/security/)

Ao seguir este guia abrangente, você estará bem equipado para implementar uma estratégia robusta de segurança e identidade no Azure, protegendo seus recursos e dados críticos na nuvem. Lembre-se de que a segurança é um processo contínuo, então mantenha-se vigilante e atualize suas práticas regularmente.

⭐ Obrigado por chegar até aqui e sintas-e a vontade para contribuir e deixar uma estrelinha! (**star**) 
