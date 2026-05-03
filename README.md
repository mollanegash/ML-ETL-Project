# Scalable Healthcare Data Platform: ETL + ML Pipeline

End-to-end data platform processing structured healthcare datasets for predictive analytics.

## Architecture
Databricks Lakehouse → PySpark ETL → ML Model Training → Java REST API

## What I Built
- **PySpark ETL Pipeline**: Ingested + transformed synthetic healthcare data on Databricks
- **ML Pipeline**: Feature engineering with Pandas/NumPy + model training workflows  
- **Backend Integration**: Designed for deployment as Java Spring Boot microservice on Azure AKS
- **MLOps Ready**: Structured for MLflow tracking + CI/CD integration

## Tech Stack
PySpark, Databricks, Python, Pandas, PostgreSQL, Java, Spring Boot, Azure AKS, Kubernetes

## Production Notes
Designed with backend scalability and production integration in mind. Originally prototyped with Flask, migrated architecture to Spring Boot + AKS for enterprise deployment.

**Scale**: TB-scale ready | **Status**: Platform architecture complete
