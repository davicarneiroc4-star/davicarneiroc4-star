# Olá, eu sou o Davi 

Estudante de **Análise e Desenvolvimento de Sistemas** na UNIP, em Belém (PA), focado em **dados e IA aplicada**.

Gosto de pegar dados bagunçados e problemas do dia a dia e transformar em ferramentas que funcionam: pipelines de ETL, dashboards, agentes de IA e automações que economizam tempo. Uso IA junto com os dados: meu assistente com Gemini responde perguntas sobre o banco tratado pelo meu ETL, e minha automação no n8n classifica e resume e-mails sozinha.

## 🛠️ Tecnologias

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logo=sqlalchemy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)

- **Dados:** Python, Pandas, SQL (MySQL), SQLAlchemy
- **Visualização:** Power BI (DAX), Matplotlib, Excel
- **IA e automação:** n8n, Google Gemini (function calling, saída em JSON), Claude Code
- **Ferramentas:** Git, GitHub, VS Code, MySQL Workbench

## 📂 Projetos

### [Triagem de e-mails com IA](https://github.com/davicarneiroc4-star/automacao-emails-n8n)
`n8n` `Gemini` `Gmail API` `JavaScript`

Automação que classifica os e-mails novos em 8 categorias, aplica etiquetas no Gmail e manda um resumo diário com prazos de processos seletivos e vagas no meu perfil.

- 93 e-mails classificados em 17 segundos na primeira execução
- Uma única chamada ao Gemini por execução, com resposta em JSON validada por schema
- Economia estimada de 15 minutos por dia

### [Pipeline ETL para uma empresa SaaS](https://github.com/davicarneiroc4-star/etl-saas-pandas-mysql)
`Python` `Pandas` `MySQL` `SQLAlchemy` `Matplotlib`

Banco MySQL com 8 tabelas e cerca de 28 mil registros, **propositalmente sujo**, que passa por um pipeline de extração, limpeza e carga em Python.

- Tratei 9 tipos de problemas de qualidade (e-mails duplicados, valores negativos, datas inconsistentes), marcando cada linha alterada
- Recuperei datas de pagamento cruzando tabelas com `merge`
- Encontrei e corrigi na origem um bug que gerava 3.778 faturas com datas erradas
- Calculei MRR, churn mensal e LTV por plano
- Criei um assistente com IA (Gemini) que responde perguntas sobre esses dados em português · [Testar demo](https://pergunte-ao-etl.streamlit.app/)

### [Dashboard de Vendas no Power BI](https://github.com/davicarneiroc4-star/dashboard-De-Vendas-No-PowerBI)
`Power BI` `DAX` `Excel`

Dashboard interativo com receita, ticket médio, faturamento por região e marca, evolução mensal e ranking de vendedores, com medidas em DAX.

## 🎓 Certificações

- **AI Fluency: Framework and Foundations** — Claude Academy (Anthropic), 2026 · [Ver certificado](https://academy.claude.com/verify/268cc42d97e28550f95d54717f223e1f)

## 📚 Estudando agora

- Testes automatizados com `pytest`
- Orquestração de pipelines com Apache Airflow
- Docker

## 📫 Contato

- GitHub: [davicarneiroc4-star](https://github.com/davicarneiroc4-star)
- LinkedIn: [Davi Carneiro](https://www.linkedin.com/in/davicarneiro-dados)
