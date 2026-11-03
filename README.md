# Rui Gabriel Oliveira

**Engenharia de Dados (Jr) · SQL · Python · Pipelines · Power BI**

Trabalho com dados de produção todos os dias. Como Técnico de Infraestrutura na **Softplan**, acompanho KPIs operacionais no Zabbix, investigo locks e anomalias em bancos de dados com SQL (DBeaver) e cruzo dados de Kubernetes, Elastic, VMs e logs para montar evidências de incidentes em sistemas que não podem parar. Agora estou levando essa base para Engenharia de Dados: pipelines, modelagem e análise.

Antes, dois anos na **Norsk Hydro**, em ambiente industrial multinacional, com monitoramento em Zabbix e Grafana, consultas SQL para diagnóstico e documentação para equipes globais.

Formando em Sistemas de Informação pela Unisul (dez/2026).

---

## Projetos

### Clima × Dengue — pipeline de dados e previsão de casos na Região Sul
[`ruigabriel1/Projeto_Clima_X_Dengue`](https://github.com/ruigabriel1/Projeto_Clima_X_Dengue)

Pipeline em arquitetura Medallion (Bronze → Silver → Gold) que cruza dados climáticos (INMET), epidemiológicos (SINAN) e anomalias oceânicas (NOAA/ONI) para prever casos de dengue nos 1.190 municípios da Região Sul.

| | |
|---|---|
| Modelo | XGBoost Regressor |
| R² (cross-validation espacial) | 0,744 |
| MAE | 10,8 casos por cidade/mês |
| Cobertura | 1.190 municípios × 10 anos (142.800 registros) |

Melhor trabalho da Região Sul no IV Symposium One Health / Saúde Única (Campo Grande/MS, 2026). Pesquisa de mestrado de Fernando R. D. J. de Oliveira; meu papel foi a engenharia de dados, o pipeline e o modelo.

`Python` · `pandas` · `XGBoost` · `SQL` · `Power BI`

### Projeto 2 — pipeline ELT orquestrado *(em construção)*

Ingestão de uma API pública com histórico diário para PostgreSQL em Docker, transformação com dbt (staging → intermediário → marts) com modelo dimensional e testes de qualidade, orquestração com Airflow e painel final. Link aqui assim que estiver rodando com um `docker compose up`.

### Projeto ECommerceSystem
[`ruigabriel1/Projeto-ECommerceSystem`](https://github.com/ruigabriel1/Projeto-ECommerceSystem)

Plataforma de e-commerce distribuída em .NET 9 com microsserviços, API Gateway (Ocelot), autenticação JWT, mensageria com RabbitMQ e persistência em SQL Server.

`C#` · `.NET 9` · `RabbitMQ` · `SQL Server`

---

## Stack

**Dados** &nbsp;SQL · Python (pandas) · Power BI · ETL/ELT · Modelagem de dados · Qualidade de dados

**Ferramentas** &nbsp;Git · Docker · Linux · DBeaver · Jupyter

**Infraestrutura e observabilidade** &nbsp;Kubernetes · Elasticsearch · Zabbix · Grafana · Microsoft Azure

**Estudando** &nbsp;Apache Airflow · dbt · modelagem dimensional (Kimball)

Uso IA generativa como ferramenta de produtividade, principalmente na análise de grandes volumes de log e no apoio ao desenvolvimento, sempre revisando e entendendo o código que entrego.

---

📫 &nbsp;ruigabrieloliveira1@gmail.com &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/rui-gabriel-oliveira/)
