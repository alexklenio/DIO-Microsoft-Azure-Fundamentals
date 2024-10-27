<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="60px" src="https://assets.dio.me/Mo-tlP263KBZIWFaCvplHdmnL4GSLIITz5tzmMUoX7s/f:webp/h:77/q:80/w:77/L2xhYl9wcm9qZWN0cy9iYWRnZXMvY2E0NTA1ZmYtNTI2YS00ZGZkLWI3ZTAtZDhhZTEwMDdiNTRjLnBuZw"></a>
    <span> 
Microsoft Azure - Construindo Arquiteturas no Azure</span>
</h1>

Repositório desenvolvido para fins didáticos, com a disponibilização de materiais de apoio para o lab **Microsoft Azure - Construindo Arquiteturas no Azure** da [Digital Innovation One](https://www.dio.me/).

[![Link do Lab](https://img.shields.io/badge/▶-000?style=for-the-badge&logo=movie&logoColor=E94D5F)](https://web.dio.me/lab/componentes-de-arquitetura-do-azure-laboratorio/learning/undefined) 
[![Link do Lab](https://img.shields.io/badge/Acesse%20o%20Lab%20na%20Plataforma-E94D5F?style=for-the-badge)](https://web.dio.me/lab/componentes-de-arquitetura-do-azure-laboratorio/learning/undefined)

## Objetivo
Como resolução do Lab4, módulo 2, repasso um resumo de tudo visto, aprendido e discutido no módulo
   
## Resposta do Lab

# 🌐 Resumo Laboratório Azure - AZ-900 - Módulo 2️⃣ - Arquitetura e Serviços Azure

## 🏫 Aula: Componentes de Arquitetura do Azure
### 🔖 Conteúdo: Componentes de Arquitetura do Azure

* REGIÕES: Ao criar um recurso no Azure, é necessário indicar o local em que ele deve ficar 🗺️.
  * Quanto mais perto o recurso estiver do local físico, menor será o delay da informação. 🌩️⏲️
  * As tarifas variam de acordo com a região. 💸
  * Alguns recursos estão disponíveis em determinadas regiões. 🛍️
* O Azure está presente em mais de 60 regiões correspondentes a mais de 140 países. 🌍
* As regiões são compostas de um ou mais datacenters muito próximos. 🏢💻 [Zona de Disponibilidade]

<h1 align="center"> ☁️🗄️💻 ↔️ ☁️🗄️💻 ↔️ ☁️🗄️💻 </h1>

* Cada datacenter é equipado com alimentação, resfriamento e rede independentes. 🔌🧊🕸️

### 🔖 Conteúdo: Entendendo Pares de Região e Grupos de Recursos

* PARES DE REGIÃO: Cada região possui uma região par que será acessada caso a região original seja impactada. 🌍🤝
  * Há cenários com replicação automática para alguns serviços. 🔄⚙️
    * [Regiões Pares](https://aka.ms/PairedRegions-ptb)

![Pares de Região](https://github.com/thiagofs84/Res_Lab_Azure/blob/main/Regi%C3%B5es.PNG)

* REGIÕES SOBERANAS DO AZURE: Regiões exclusivas de governos (atualmente EUA e China). 🛡️🌐
  * Inacessíveis para usuários não autorizados. 🚫
    * Serviços Governamentais dos EUA - Voltado às necessidades de segurança e conformidade das agências federais. 🗽🛡️
    * Azure China - A Microsoft é o 1º provedor estrangeiro de serviços de nuvem pública na China, fisicamente separado dos serviços de nuvem. (21Vinet) 🇨🇳🎖️

   * RECURSOS DO AZURE: Componentes como armazenamento, máquinas virtuais e redes disponíveis para soluções de nuvem. ☁️💾
     * Ao criar uma máquina virtual, por exemplo, é importante organizar os respectivos recursos - [criar grupo de recursos] 🗃️
       * Os recursos podem existir em apenas um grupo e em diferentes regiões. 🌐
       * Podem ser movidos 🔀
       * Os aplicativos podem utilizar vários grupos de recurso. 📦

### 🔖 Conteúdo: Assinatura da Azure e Grupos de Gerenciamentos

* ASSINATURA DO DESENVOLVIMENTO 🔑⚙️
* ASSINATURA DO TESTE 🔑🧪
* ASSINATURA DA PRODUÇÃO 🔑🕴️

> ❗ Uma conta pode ter diversas assinaturas, mas uma assinatura está associada apenas a uma conta. 🧾

  * As assinaturas do Azure permitem gerenciar limites de cobrança e controles de acesso. 🧑‍💻🔐

* GRUPOS DE GERENCIAMENTO
  * Regras padrões para gerenciar assinaturas. 📑⚙️
⭐ Obrigado por chegar até aqui e sintas-e a vontade para contribuir e deixar uma estrelinha! (**star**) 
