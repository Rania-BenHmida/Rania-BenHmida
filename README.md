<div align="center">

# Hi, I'm Rania 👋

### Data & AI Engineer

Engineer from **ESPRIT** (graduated with honors, *Mention Très Bien*).
I build the full data path: **ETL → data warehouse → BI → applications → AI on top of the data.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rania-ben-hmida-586724291/)
[![Status](https://img.shields.io/badge/Open%20to-Data%20%26%20AI%20Engineer%20roles-2ea44f?style=for-the-badge)](https://www.linkedin.com/in/rania-ben-hmida-586724291/)

</div>

---

## About me

- 🎓 Engineering degree from **ESPRIT**, after a two-year preparatory cycle at IPEIEM.
- 🏗️ I design **data warehouses and ETL pipelines**, turn them into **dashboards people actually use**, and add **AI features** (natural language → SQL) on top.
- 🧩 Comfortable across the stack: data engineering, BI, back end and front end.
- 🔎 **Looking for a Data Engineer / AI Engineer position.**

---

## 💼 Experience

| Period | Role | What I did |
|---|---|---|
| Feb – Sep 2026 | **End-of-study internship**, MEDIANET | MEDIANET Nexus: AI-assisted CRM platform, PostgreSQL warehouse with Talend ETL, role-based Power BI dashboards, Medianaute NL-to-SQL assistant |
| Jun – Aug 2025 | **Engineering internship**, MEDIANET | Amazon data pipeline: scraping with BeautifulSoup, SQL Server star-schema warehouse loaded with Talend, Power BI dashboard with daily automatic refresh |
| Jul – Aug 2024 | **Summer internship**, Be-Softilys | Tutorials management web app: Spring Boot REST API, Angular front end, PostgreSQL |

**Academic projects:** Graph-RAG product recommendation chatbot · Video emotion recognition (CNN + Autoencoder + LSTM)

---

## ⭐ Featured project: MEDIANET Nexus (end-of-studies project)

A **customer success and analytics platform** built during my final-year internship at **MEDIANET**.
It brings subscription, support, sales and usage data into one governed warehouse, exposes it through dashboards and a web app, and lets users **ask questions in plain French or English**.

```mermaid
flowchart LR
    A[Source data<br/>accounts · subscriptions · tickets · deals · logs] --> B[Talend ETL<br/>scheduled refresh]
    B --> C[(PostgreSQL<br/>constellation-schema warehouse)]
    C --> D[Power BI<br/>embedded dashboards]
    C --> E[Django REST API]
    E --> F[React + TypeScript app]
    E --> G[Gen BI engine<br/>NL → SQL → answer + chart]
    G --> F
```

| Layer | What I built |
|---|---|
| **Data engineering** | Star-schema warehouse in PostgreSQL, loaded with Talend (dimensions first, then facts), refreshed on a schedule or on demand |
| **BI** | Power BI dashboards with DAX measures for sales pipeline and customer success KPIs |
| **Application** | React + TypeScript front end, Django REST back end, role-based access, bilingual interface |
| **AI** | **Medianaute**, a bilingual text and voice assistant: language and intent detection, natural language → SQL, AST-based SQL validation, answers with charts, Groq → Mistral fallback, Whisper speech-to-text. Answers evaluated with BERTScore and LLM-as-a-judge (88% intent accuracy) |

👉 **[See the full project](https://github.com/Rania-BenHmida/MEDIANET-Nexus)**

---

## 🛠️ Tech stack

**Data engineering**
![Talend](https://img.shields.io/badge/Talend-FF6D70?style=flat-square&logo=talend&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**BI & analytics**
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-F2C811?style=flat-square&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**AI**
![LLMs](https://img.shields.io/badge/LLMs-Text--to--SQL-8A2BE2?style=flat-square)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)
![Mistral](https://img.shields.io/badge/Mistral-FF7000?style=flat-square)
![Time series](https://img.shields.io/badge/ARIMA%20%2F%20SARIMA-forecasting-8A2BE2?style=flat-square)

**Full stack**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)

---

## 📌 Other projects

| Project | What it is | Stack |
|---|---|---|
| [**Price_comparator**](https://github.com/Rania-BenHmida/Price_comparator) | Team project: price comparison across supermarket products, hotels and flights, with scrapers, Talend ETL, a Flask API, forecasting models (ARIMA / SARIMA) and Power BI dashboards | Flask · MySQL · SQL Server · Talend · Power BI |
| [**Dashboard_Amazon**](https://github.com/Rania-BenHmida/Dashboard_Amazon) | Multi-source Amazon data integration: scraping, pandas cleaning into one schema, Talend ETL and a Power BI report | Python · Talend · Power BI |
| [**Soccer-Predictor**](https://github.com/Rania-BenHmida/Soccer-Predictor) | Team ML project on Premier League data: predicts a player's best position (five models compared, up to 88% accuracy), ranks players by position, with a Flask app and Power BI report | Python · scikit-learn · XGBoost · Flask |
| [**Tutorials_App**](https://github.com/Rania-BenHmida/Tutorials_App) | Tutorials management web app from my 2024 internship at Be-Softilys, with the full project report | Spring Boot · Angular · PostgreSQL |

---

## 📫 Let's talk

I'm looking for a **Data Engineer / AI Engineer** role. The best way to reach me is on [LinkedIn](https://www.linkedin.com/in/rania-ben-hmida-586724291/).
