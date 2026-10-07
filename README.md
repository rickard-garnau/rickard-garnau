# Hi there! I'm Rickard

Data Engineering student at STI (2025–2027), looking for a LIA internship 11 January – 28 May 2027 in the Stockholm area.

Before studying I spent 15 years at Citymail Sweden AB [CHECK: use the same title as in the LinkedIn post], where a wrong address or register has real consequences. That is a big part of why I want data to be right from the start.

## Stack

- **Languages:** Python (Pandas, OOP) · SQL (CTEs) · dbt · dlt
- **Cloud & Infrastructure:** Azure · Terraform · Docker
- **Data Platforms:** Databricks · Delta Live Tables · PySpark · Snowflake · Apache Kafka
- **Databases:** PostgreSQL · DuckDB
- **Backend & APIs:** FastAPI · REST
- **Modeling:** ER-modeling · 3NF Normalization · Dimensional modeling · Medallion architecture
- **BI:** Power BI · Streamlit · Evidence.dev
- **Practices:** Git · GitHub Actions · pytest · Agile/Scrum

## Projects

### [eClipseBord](https://github.com/rickard-garnau/azure_python_fullstack_lab)
Fullstack app for analysis and visualization of solar and lunar eclipses, based on NASA's Five Millennium Catalogs.

- FastAPI backend and Streamlit frontend as separate services
- Containerized with Docker, deployed to Azure with Terraform (Container App and Web App)
- Error handling for failed API calls, backend URL controlled via environment variable

### [Marathos Lab](https://github.com/rickard-garnau/marathos_rickard_garnau)
Medallion pipeline on Databricks for ultra marathon results (7.4M rows, 1990–2022).

- Streaming ingestion via Delta Live Tables into bronze
- Silver: unit standardization, date parsing, performance normalization [CHECK: deduplication]
- Dimensional model in gold: `fct_results`, `dim_athlete`, `dim_event` and analytical views
- Genie space for ad hoc questions, verified manually against SQL
- Databricks dashboard on the gold views

### FoodHub (group project)
Recipe search platform: FastAPI, Kafka and PostgreSQL in Docker. Kafka producer/consumer streams data from the Spoonacular API into PostgreSQL (staging → curated), with a cache-first strategy to limit external API calls. ETL with Pydantic validation, NaN handling and fuzzy ingredient matching. Scrum Master for half the project [CHECK team size].

### STHLMs Puls (group project)
Event guide for Stockholm in Power BI, with a map of venues, charts per genre and weekday, and filters on date and subcategory. Data from Ticketmaster, Visit Stockholm, Berns, Fasching and Google Places, plus weather via API. I built the start page, the performing-arts and nightlife pages, and parts of the data pipeline. Also a Streamlit version.

## Contact

- LinkedIn: [Rickard Garnau](https://www.linkedin.com/in/rickard-garnau-37363b233/)
- Email: rickardgarnau@gmail.com
- Location: Stockholm

More projects and course work under my repositories.
