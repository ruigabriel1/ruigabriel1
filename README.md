<div align="center">

# Rui Gabriel Oliveira

### Engenharia de Dados · IA aplicada

Construo pipelines de dados confiáveis e coloco IA em cima deles para resolver problemas reais,
medindo com honestidade o que funcionou e o que não funcionou.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-rui--gabriel--oliveira-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rui-gabriel-oliveira/)
[![Email](https://img.shields.io/badge/ruigabrieloliveira1%40gmail.com-161b22?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ruigabrieloliveira1@gmail.com)

</div>

---

### Sobre mim

- **Técnico de Infraestrutura na Softplan.** Trabalho com dados de produção todos os dias: KPIs operacionais
  no Zabbix, investigação de locks e anomalias em bancos de dados com SQL, e cruzamento de dados de
  Kubernetes, Elastic, VMs e logs para montar evidências de incidentes em sistemas que não podem parar.
- **Dois anos na Norsk Hydro**, em ambiente industrial multinacional: monitoramento em Zabbix e Grafana,
  SQL para diagnóstico e documentação para equipes globais.
- **Sistemas de Informação na Unisul**, formatura em dez/2026.
- Uso IA como ferramenta de trabalho todos os dias. O que aprendi: o valor está em **saber validar** o que
  ela entrega, com testes, comparações honestas e limites explícitos.

---

### Projeto em destaque

#### 🦟 [Clima × Arboviroses](https://github.com/ruigabriel1/Projeto_Clima_X_Dengue): do dado público ao alerta de risco

> O calor aumenta a dengue no Sul do Brasil. Mas isso ajuda a prever o próximo surto?

<table>
<tr>
<td width="50%" valign="top">

**Engenharia de dados**
- Ingestão de **4 APIs públicas** (InfoDengue, Open-Meteo, NOAA, IBGE) para **1.190 municípios**, 2015–2026
- Carga **incremental e idempotente** em SQLite: upsert, índice único, retomada após falha
- Validação de qualidade: duplicatas, faixas físicas, cobertura e conferência contra a fonte
- **62 testes automatizados**, incluindo testes contra vazamento de dados futuros

</td>
<td width="50%" valign="top">

**IA e análise**
- XGBoost Poisson com variáveis sem vazamento e alerta de risco **calibrado**, servido por **FastAPI**
- Efeito do clima por **DLNM**: um mês quente eleva o risco de dengue em **46%** nos 3 meses seguintes
- O alerta **supera o alerta oficial do InfoDengue** em todas as combinações testadas
- **Protocolo pré-registrado** e testes de uso único: quando o modelo perdeu em 2025, o resultado foi
  publicado e virou a próxima versão

</td>
</tr>
</table>

`Python` · `pandas` · `SQL` · `SQLite` · `XGBoost` · `pyfixest` · `FastAPI` · `pytest`

Melhor trabalho da Região Sul no **IV Symposium One Health / Saúde Única** (2026). Pesquisa de mestrado de
Fernando R. D. J. de Oliveira; meu papel: engenharia de dados, modelagem e API.

---

### Outros projetos

| Projeto | Foco | Em uma linha |
|---|---|---|
| [**PR Babysitter**](https://github.com/ruigabriel1/PR-Babysitter-Jarvis) | IA · agentes | Agente autônomo de code review no CI/CD: webhooks em FastAPI, quality gate com métricas em SQLite e **Llama 3.2 local** sugerindo correções. Feito em menos de 24 h, só com ferramentas gratuitas |
| [**Jarvis Task Assistant**](https://github.com/ruigabriel1/jarvis-task-assistant) | IA · voz | Assistente desktop de tarefas por voz com Gemini, com escrita atômica e controle de concorrência |
| [**Arquiteto de Mundos**](https://github.com/ruigabriel1/Arquiteto-de-Mundos) | IA generativa | Plataforma Django de RPG online com IA (GPT + Claude) como Game Master |
| [**ECommerceSystem**](https://github.com/ruigabriel1/Projeto-ECommerceSystem) | Back-end distribuído | Microsserviços em .NET 9 com API Gateway, JWT, RabbitMQ e SQL Server |
| **Pipeline ELT orquestrado** *(em construção)* | Engenharia de dados | API pública → PostgreSQL em Docker → dbt (staging → marts) → Airflow → painel |

---

### Stack

**Dados** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**IA e ML** &nbsp;
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EB5E28?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-161b22?style=flat-square&logo=ollama&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

**Back-end** &nbsp;
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)

**Infra e observabilidade** &nbsp;
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Elastic](https://img.shields.io/badge/Elastic-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![Zabbix](https://img.shields.io/badge/Zabbix-D40000?style=flat-square&logo=zabbix&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Estudando** &nbsp; Apache Airflow · dbt · modelagem dimensional (Kimball) · agentes de IA

---

<div align="center">

<img src="https://raw.githubusercontent.com/ruigabriel1/github-snake/main/dist/github-snake-dark.svg" alt="Cobrinha percorrendo o gráfico de contribuições do GitHub" width="100%">

</div>
