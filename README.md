# f1-elt-platform

Industrial-style ELT portfolio project.

Pipeline (target state): F1 source/API -> S3 raw landing -> Snowflake (bronze/silver/gold via dbt) -> Power BI  
Local dev: DuckDB + dbt (Docker)  
Orchestration: Airflow

## Status
Bootstrapping repo and local dev workflow.