# Azure Marketplace

## M.O.N.A - [M]arketplace [ON]boarding [A]ccelerator for SaaS (Software as a Service)

[Acesse o projeto MONA via GitHub](https://github.com/microsoft/mona-saas) - <b>MONA</b> é um projeto que contem um conjunto de scripts a serem executados no portal do Azure. 

Estes Scripts, qndo executados com sucesso, criarão um ambiente para integração com o Azure Marketplace e End-Points para a aquisição e integração ao <b>SaaS</b> como:

- Landing Page - Pagina onde o cliente final será direcionado para o "start" de seu ambiente dentro do <b>SaaS</b>
- APIs e Web-Hooks - End-points para integração

## Landing Page

- Uma página sua que será acessada através do marketplace qndo o cliente adquirir seu SAAS

- Precisa estar disponivel 24/7

- Na requisição será enviado um `token` - qndo o acesso é feito via uma aquisição no Marketplace - e este `token` deverá ser usado posteriormente via [SaaS Resolve API](https://learn.microsoft.com/en-us/azure/marketplace/partner-center-portal/pc-saas-fulfillment-subscription-api#resolve-a-purchased-subscription)


## ADSs - Architecture Design Sessions

Validação na arquitetura da solução para multi-tennancy como:

Existem diversos modelos / estratégias para tratar dados em ambiente multi-tennancy:

[Modelos de Dados em Multi-Tennancy](https://learn.microsoft.com/en-us/azure/azure-sql/database/saas-tenancy-app-design-patterns?view=azuresql)

