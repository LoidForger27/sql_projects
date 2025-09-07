# 🗄️ SQL Portfolio — Real-World Data Projects
> Query. Analyze. Transform. A curated collection of SQL projects that solve practical business problems with clean schema design, efficient queries, and clear insights.

<p align="left">
  <a href="#"><img alt="SQL" src="https://img.shields.io/badge/SQL-PostgreSQL%20%7C%20MySQL%20%7C%20BigQuery-blue"></a>
  <a href="#"><img alt="Status" src="https://img.shields.io/badge/Status-Active-success"></a>
  <a href="#"><img alt="License" src="https://img.shields.io/badge/License-MIT-lightgrey"></a>
</p>

---

## 📌 Overview
This repository showcases end-to-end SQL work: from modeling and cleaning data to writing analysis queries and optimizing performance. Each project folder includes a problem brief, dataset, runnable SQL scripts, and a short results summary.

---

## ❓ Problem Statement
Organizations collect mountains of raw data. Without effective querying, structure, and validation, it remains unused. These projects address real scenarios:
- Cleaning messy operational data
- Designing normalized relational schemas
- Building analysis queries and views for decision-making
- Optimizing performance for large tables

---

## 🔧 Solution Approach
**Core tools:** PostgreSQL • MySQL • BigQuery • SQL Server (SSMS) • DBeaver/pgAdmin  
**Techniques:** CTEs, window functions, subqueries, analytical aggregations, indexing, constraints, and views.  
**Workflow:**  
1) Understand the business question  
2) Model the data (ERD, normalization)  
3) Load/clean datasets  
4) Write modular queries and views  
5) Validate and document insights

---

## ✨ Key Features / Highlights
- 🧹 **Data Cleaning:** Deduplication, type fixes, referential integrity, constraints
- 🧩 **Schema Design:** ERD + 1NF–3NF normalization with indexes and foreign keys
- 📊 **Analytics:** Cohort/RFM, retention, trendlines via window functions
- ⚡ **Performance:** Query refactors and indexing strategies
- 🔄 **Reusable Assets:** Views, UDFs (where supported), and parameterized scripts

---

## 🛠 Skills Demonstrated
- **SQL Joins & Subqueries** → Complex data wrangling  
- **Window Functions** → Ranking, moving averages, cumulative totals  
- **CTEs & Views** → Modular analysis and readable logic  
- **Database Design** → ER modeling and normalization  
- **Performance Tuning** → Indexing, execution-plan-aware refactors

---

## 📈 Results / Impact (Examples)
- Reduced complex report runtime by **40%** with composite indexing and CTE refactor.  
- Cleaned and analyzed **10k+ rows** across multiple domains with integrity constraints.  
- Implemented a normalized schema for a **library system** to support thousands of transactions.

---

## 📂 Repository Structure
SQL-Projects/
│
├─ datasets/ # Sample CSVs or SQL dumps used across projects
├─ common/ # Shared helpers: views, UDFs, seeders
│ ├─ views/
│ ├─ functions/
│ └─ utils/
│
├─ projects/
│ ├─ library_mgmt/ # Example: Library Management System
│ │ ├─ README.md
│ │ ├─ schema.sql
│ │ ├─ seed.sql
│ │ ├─ analysis.sql
│ │ └─ results.md
│ ├─ intl_students/ # Example: International Students Mental Health
│ │ ├─ README.md
│ │ ├─ create_tables.sql
│ │ ├─ clean_transform.sql
│ │ ├─ analytics.sql
│ │ └─ results.md
│ └─ bellabeat_case/ # Example: Bellabeat usage & cohorts (if applicable)
│ ├─ README.md
│ ├─ schema.sql
│ ├─ transform.sql
│ ├─ cohorts.sql
│ └─ results.md
│
└─ README.md # You are here

---

## ▶️ How to Run
1. **Clone**
   ```bash
   git clone https://github.com/<YOUR_USERNAME>/sql-projects.git
   cd sql-projects
2. Pick a project (e.g., projects/library_mgmt/) and open it in your SQL client (pgAdmin, DBeaver, SSMS, BigQuery).

3. Create schema
  \i schema.sql            -- PostgreSQL
  -- or run the file in your client

4. Load sample data
  \i seed.sql

5. Run analysis
\i analysis.sql

6. View summarized results in the project’s results.md.

BigQuery note: Replace \i usage with the BigQuery UI/CLI and adjust dataset/table IDs accordingly.

## ✅ Data Quality & Governance

Primary/foreign keys and NOT NULL constraints

Check constraints on enumerations and valid ranges

Minimal privileges for read/write roles where applicable

Repeatable seeds and idempotent scripts

## 🔮 Future Improvements

dbt project for modular transforms and tests

Airflow orchestration for scheduled SQL jobs

Parameterized reporting views for self-service BI (Looker/Tableau/Power BI)

Benchmark suite comparing indexes and query plans

## 🤝 Contributing

PRs are welcome—open an issue describing the dataset, the problem statement, and the SQL approach. Keep scripts idempotent and documented.

## 📬 Contact / Portfolio

GitHub: [https://github.com/](https://github.com/LoidForger27)

LinkedIn: [https://www.linkedin.com/in/](https://www.linkedin.com/in/josephbaguio27339198/)
