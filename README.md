# Muhannad Najjar

Computer Science Master’s student building practical data engineering projects with Python, SQL, APIs, DuckDB, and automation.

I am currently developing the **Berlin Data Engineering Lab**, a portfolio of connected projects focused on real-world data pipelines, data validation, analytics warehouses, testing, and reproducible workflows.

Current status: the first three projects are implemented, tested locally, documented in English, and connected through shared data outputs.

## Featured Projects

The three featured projects below form one connected data engineering workflow: mobility data ingestion, weather data ingestion, and a DuckDB analytics warehouse that combines both datasets.

### Berlin Mobility Pipeline

Batch ETL pipeline for Berlin bike counter data.

**Focus:** Excel ingestion, data cleaning, validation, CSV/Parquet/SQLite outputs, pytest, Ruff, and GitHub Actions.

**Output:** `bike_counts_2025_clean.parquet`

**Repository:** [berlin-mobility-pipeline](https://github.com/muhannadnajjar1-hash/berlin-mobility-pipeline)

---

### Berlin Weather Pipeline

API-based pipeline for historical Berlin weather data in 2025.

**Focus:** API ingestion, historical weather data, time-series processing, Parquet/SQLite storage, testing, and CI.

**Output:** `weather_2025_historical.parquet`

**Repository:** [berlin-weather-pipeline](https://github.com/muhannadnajjar1-hash/berlin-weather-pipeline)

---

### Berlin Analytics Warehouse

Local DuckDB analytics warehouse combining the outputs of the mobility and weather pipelines for SQL analysis and report generation.

**Focus:** star schema, fact/dimension tables, SQL analytics, DuckDB, report generation, and data modeling.

**Input:** mobility pipeline output + weather pipeline output  
**Output:** local DuckDB warehouse and analysis figures

**Repository:** [berlin-analytics-warehouse](https://github.com/muhannadnajjar1-hash/berlin-analytics-warehouse)

## Skills

Python · Pandas · SQL · DuckDB · SQLite · APIs · Parquet · pytest · Ruff · GitHub Actions · Data Engineering

## Current Learning Focus

- Building reproducible data pipelines
- Improving testing and CI practices
- Designing analytics-ready data models
- Connecting separate data projects into one portfolio workflow
- Preparing a professional data engineering portfolio

## Portfolio Direction

My current portfolio shows a connected learning path:

```text
Raw data pipeline
→ API data pipeline
→ Analytics warehouse
→ Data API
→ Portfolio website
