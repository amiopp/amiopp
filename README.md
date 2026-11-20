<h1 align="left">Mohamed Amine Adnane</h1>

**Data Engineer · BI Developer** — Casablanca, Morocco

I build data platforms end to end: ingestion from operational systems, a governed warehouse, the orchestration that keeps it fresh, and the dashboards and forecasts people actually decide with.

Most recently at **RATP Dev Casablanca** (operator of the Casablanca tramway & busway, ~450,000 riders a day), I replaced a manual Excel-based KPI process with a SQL Server Medallion warehouse, a pipeline orchestrator, Power BI reporting and a Prophet forecasting layer.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/mohamed-amine-adnane-57097038a)  
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:mohamedamineadnane00@gmail.com)

---

### What I work on

| Area | What that means in practice |
|---|---|
| **Data warehousing** | Medallion architecture (Bronze → Silver → Gold) on SQL Server, star-schema modeling, T-SQL stored procedures for cleansing and conformance |
| **Ingestion & orchestration** | Python (pandas, SQLAlchemy, pyodbc) loaders from SQL Server sources, GMAO and network Excel files; scheduling, retries with exponential backoff, run logging and alerting |
| **Analytics & BI** | Power BI + DAX, Qlik Sense, KPI definition with business owners (HR, maintenance, fleet availability) |
| **Forecasting** | Time-series forecasting with Prophet, written back to the warehouse and served through BI |
| **Platform** | Docker, Kubernetes, Azure, GitLab CI · Flask, React, Spring Boot when a data product needs an interface |

---

### Selected work

**Medallion KPI warehouse** · *RATP Dev Casablanca, final-year project (company code, private)*  
SQL Server warehouse (Bronze → Silver → Gold) consolidating HR and Maintenance data from AGIRH, GMAO and network Excel files. 5 star schemas (HR, preventive maintenance, rolling-stock availability, MDBFS, contract indicators) feeding 10+ KPIs, with Python loaders and T-SQL stored procedures for every layer transition. Power BI dashboards for HR and Maintenance managers, plus a Prophet module producing 6-month absenteeism and turnover forecasts written back to Gold.  
`Python` `SQL Server` `T-SQL` `Power BI` `DAX` `Prophet`

**TrackFlow — ETL orchestration platform** · *same project (private)*  
Flask control plane for the warehouse: 6 config-driven pipelines, full or per-layer reloads, cron scheduling (APScheduler), retries with exponential backoff, execution logs, success-rate and duration metrics, email/Teams alerting, REST API.  
`Python` `Flask` `APScheduler` `Chart.js`

**Vigon Monitor — hotel IT infrastructure monitoring** · [`vigon-monitor`](https://github.com/amiopp/vigon-monitor)  
Centralized monitoring for hotel IT assets with role-based views, prioritized real-time alerts and an AI assistant.  
`TypeScript` `React` `Node.js`

**ChronoTrack — incident timer** · [`incident-timer`](https://github.com/amiopp/incident-timer)  
Live incident-tracking board displayed on internal operations screens.  
`TypeScript`

---

### Tech

**Data:** Python · SQL / T-SQL · SQL Server · PostgreSQL · MySQL · MongoDB · pandas · SQLAlchemy  
**BI & ML:** Power BI · DAX · Qlik Sense · Prophet  
**Platform:** Docker · Kubernetes · Azure · GitLab CI · Linux  
**Apps:** Flask · React · TypeScript · Spring Boot

---

<sub>Computer Science engineer (EMSI, MIAGE track) · Arabic · French · English · Open to Data Engineer and BI Developer roles.</sub>
