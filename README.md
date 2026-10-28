# SQL Data Warehouse Project | Data Engineering & Quality Engineering

## Project Overview

This project focuses on building a SQL-based data warehouse from scratch, following the hands-on tutorial **“SQL Data Warehouse from Scratch | Full Hands-On Data Engineering Project”** by **Baraa from Data with Baraa**.

The project integrates data from ERP and CRM source systems, applies data cleansing and transformation rules, and organizes the data into a unified model to support analytical reporting and business insights.

Following the **Medallion Architecture**, the data warehouse is structured into three layers:

- **Bronze Layer:** Stores raw data ingested from source systems.
- **Silver Layer:** Cleanses, standardizes, and transforms data to improve data quality and consistency.
- **Gold Layer:** Organizes business-ready data into analytical models for reporting and decision-making.

As a Quality Engineering (QE) professional, I am extending the project with a strong focus on **data warehouse testing and quality assurance**. This includes validating data completeness, transformation accuracy, data consistency, source-to-target reconciliation, and the reliability of data across the warehouse layers.

This repository serves as a learning and portfolio project to strengthen my expertise in SQL, data warehousing, ETL testing, and data quality assurance while demonstrating how Quality Engineering practices can contribute to building reliable, analytics-ready data solutions.

## Project Objectives

### 1. Data Warehouse Development <img width="30" height="30" alt="image" src="https://github.com/user-attachments/assets/6eb35db0-e3a6-495e-ae42-7f5b5a5ba90b" /> 

- **Data Sources:** Import data from ERP and CRM systems provided as CSV files.
- **Data Quality:** Identify and address data quality issues during data preparation.
- **Data Integration:** Consolidate data from multiple sources into a unified data model.
- **Data Modeling:** Develop a model suitable for analytical queries and reporting.
- **Documentation:** Document the architecture, data model, and transformation logic.
- **Scope:** Focus on the latest available dataset; historical data tracking is outside the initial project scope.

### 2. Quality Engineering & Data Testing <img width="30" height="30" alt="image" src="https://github.com/user-attachments/assets/d9f61d0e-fb24-4c41-a744-da6d876c3114" /> 

The testing component focuses on ensuring that data is accurate, complete, consistent, and correctly transformed as it moves through the warehouse.

#### Testing Scope

- **Source Data Validation:** Validate source CSV files, column headers, data types, and expected data structures.
- **Schema Validation:** Verify column names, data types, nullability, and expected table structures.
- **Data Completeness:** Identify missing, NULL, empty, or unexpected values.
- **Data Quality Validation:** Check for duplicate records, invalid values, and inconsistent data formats.
- **Transformation Validation:** Verify that cleansing, standardization, and business transformation rules are correctly applied.
- **Data Integration Validation:** Validate the integration of ERP and CRM data and check for data loss or unintended duplication.
- **Fact and Dimension Validation:** Verify relationships between fact and dimension tables, key mappings, and expected record counts where applicable.
- **Data Reconciliation:** Compare source and target data using record counts, key fields, and relevant column-level comparisons.
- **Analytical Query Validation:** Validate SQL query results and business metrics against independently derived expected results.

#### Testing Approach

Testing will be performed using SQL queries and source-to-target comparisons. Test cases will be documented with validation objectives, test queries, expected results, actual results, and execution status.

Potential defects and data quality issues will be documented with supporting evidence and expected outcomes.

### 3. BI Analytics & Reporting <img width="30" height="30" alt="image" src="https://github.com/user-attachments/assets/cb3d14c1-c593-4134-9d95-2fa4a20b3d30" />  

Develop SQL-based analytical queries to generate insights into:

- Customer behavior
- Product performance
- Sales trends

The analytical results will also be validated to ensure that calculations, aggregations, joins, and business metrics produce the expected outcomes.

## Tools & Technologies

- SQL Server
- SQL
- CSV source files
- Git and GitHub
- SQL-based data validation and testing

*Additional tools and technologies will be documented as the project evolves.*

## Repository Structure

The repository will be organized to separate warehouse development, testing, and documentation.

```text
sql-data-warehouse-project/
├── datasets/
├── scripts/
│   ├── init_database.sql
│   ├── bronze/
│   ├── silver/
│   └── gold/
├── tests/
│   ├── schema_validation/
│   ├── data_quality/
│   ├── transformation_validation/
│   ├── data_reconciliation/
│   └── analytics_validation/
├── docs/
│   ├── architecture/
│   ├── data_model/
│   └── test_documentation/
└── README.md
```

*This is a proposed structure and can be adjusted to match the actual implementation.*

## Project Status

**Status: In Progress**

The warehouse is being developed by following the tutorial, with additional focus on SQL-based testing and Quality Engineering practices.

Testing documentation, SQL validation queries, and results will be added progressively as each component is implemented.

## Learning Outcomes

- Develop a SQL-based data warehouse from scratch.
- Understand data warehouse architecture and data modeling.
- Strengthen SQL skills for data validation and reconciliation.
- Apply ETL and data warehouse testing techniques.
- Develop reusable SQL validation queries.
- Use Git and GitHub to maintain and document a technical portfolio.

## Credits & Acknowledgements <img width="30" height="30" alt="image" src="https://github.com/user-attachments/assets/6ff2b553-a225-41f9-a2e3-50891bbc9289" /> 

The core project concept, learning material, and warehouse implementation approach are based on the tutorial:

**“SQL Data Warehouse from Scratch | Full Hands-On Data Engineering Project”**

Created by **Baraa — Data with Baraa**.

I acknowledge and appreciate Baraa's educational content, which provides the foundation for this learning project.

My additional focus is on applying Quality Engineering principles to data warehouse validation, including SQL-based test cases, data quality checks, transformation validation, and source-to-target reconciliation.

Please refer to the original tutorial and the creator's repository for the original implementation and learning materials.

## Disclaimer

This is an independent learning and portfolio project developed for educational purposes. The original tutorial and its creator are credited above. Additional testing scripts, documentation, and enhancements will be identified as they are developed.
