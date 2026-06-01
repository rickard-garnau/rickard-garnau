# Hi there! I'm Rickard 

Data Engineering student at STI (2025–2027) with a background in operations and team leadership. I build ETL pipelines, data platforms and medallion architectures with a focus on data integrity, automation and scalability.

## Stack

**Languages:** Python (Pandas, OOP) · SQL (Advanced, CTEs)  
**Databases:** PostgreSQL · DuckDB  
**Platforms & Tools:** Databricks · PySpark · Delta Live Tables · Apache Kafka · Docker · FastAPI · Git  
**Modeling:** ER-modeling · 3NF Normalization · Dimensional modeling  
**BI:** PowerBI · Streamlit · Evidence.dev  

## Projects

### [Marathos Lab](https://github.com/rickard-garnau/marathos_rickard_garnau)
End-to-end medallion pipeline on Databricks for 7.4M ultra marathon results (1798–2022).

- Streaming ingestion via Delta Live Tables into bronze
- 20+ silver transformations: unit standardization, date parsing, performance normalization, deduplication
- Dimensional model in gold: `fct_results`, `dim_athlete`, `dim_event` + analytical views
- Genie space for ad hoc queries with manual verification notebook
- Databricks dashboard built on gold views

### FoodHub — Data Platform (FastAPI + Kafka + PostgreSQL + Docker)
End-to-end data pipeline with Kafka Producer/Consumer for async streaming from Spoonacular API into PostgreSQL (staging → curated). Cache-first strategy to minimize external API calls. ETL with Pydantic validation, NaN-handling and fuzzy ingredient matching. Exposed via FastAPI with search, history and query statistics endpoints. Scrum Master in a team of 5.

### Stock Data Pipeline (FastAPI + PostgreSQL + Docker)
REST API ingestion of stock data stored as JSONB in PostgreSQL. ELT pipeline with Pandas for cleaning, validation and outlier detection. Flagging and rejection logic for data quality. Credentials via `.env` and containerized with Docker.

## Background

15 years as Team Leader at Citymail Sweden AB — responsible for process optimization, flow management and daily KPI delivery across teams of 6–10 people. That background makes me take reliability and edge cases seriously.

---
## Let's talk data. I'm happy to discuss pipeline architecture, medallion design or why your silver layer is lying to you.
More projects and course work under my repositories.

- LinkedIn: [linkedin](https://www.linkedin.com/in/rickard-garnau-37363b233/)
- Email: rickardgarnau@gmail.com
- Location: Stockholm


*Seeking LIA internship. Open to data engineering roles.*
