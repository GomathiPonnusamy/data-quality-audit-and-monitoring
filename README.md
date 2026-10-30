# Data Quality Audit & Monitoring System

## Project Overview

The **Data Quality Audit & Monitoring System** is a data analytics project designed to assess, investigate, and monitor data quality across multiple business datasets.

The project uses SQL and Power BI to identify data quality issues, evaluate data quality dimensions, investigate root causes, and present actionable insights through interactive dashboards.

Rather than modifying the original source data, this project focuses on auditing existing data and making quality issues visible for further investigation and remediation.

## Project Objectives

- Evaluate the overall quality of business data.
- Identify duplicate, missing, invalid, and inconsistent records.
- Detect referential integrity and temporal issues.
- Identify computational errors and other data anomalies.
- Measure data quality across different dimensions.
- Investigate root causes and prioritize critical issues.
- Present findings through interactive Power BI dashboards.

## Tools & Technologies

- **PostgreSQL** – Database management and SQL-based data quality auditing.
- **SQL** – Data validation, issue detection, joins, CTEs, aggregations, and views.
- **Power BI** – Interactive dashboards and data quality monitoring.
- **DAX** – KPI calculations, percentages, measures, and dynamic insights.

## Data Quality Dimensions

The project evaluates data quality across the following dimensions:

| Dimension | Purpose |
|---|---|
| Completeness | Identifies missing or null values in important fields. |
| Uniqueness | Detects duplicate records. |
| Consistency | Identifies inconsistent values and relationships. |
| Integrity | Checks referential integrity between related datasets. |
| Validity | Detects values that do not meet expected business rules. |
| Accuracy-related checks | Identifies computational and other data anomalies. |

## Data Quality Issues Identified

- Duplicate records
- Missing values
- Invalid records
- Orphan records
- Temporal errors
- Computational errors

## Power BI Dashboards

### 1. Data Quality Overview Dashboard

Provides a high-level view of the overall data quality performance.

Key metrics:
- Total Records Audited
- Data Quality Score
- Uniqueness Percentage
- Completeness Percentage
- Consistency Percentage
- Integrity Percentage

### 2. Data Quality Investigation Dashboard

Helps investigate the root causes of data quality issues and prioritize remediation.

Key metrics:
- Total Issues Identified
- Critical Issues
- Most Affected Table
- Affected Records Percentage

### 3. Issue Details & Sample Records Dashboard

Provides record-level visibility into identified data quality issues.

Features:
- Detailed issue records
- Sample records for investigation
- Table-level filtering
- Issue-category filtering

## SQL Implementation

The project uses SQL views to organize and investigate different categories of data quality issues.

Key views include:

- `vw_duplicate_issues`
- `vw_missing_issues`
- `vw_invalid_issues`
- `vw_orphan_issues`
- `vw_temporal_issues`
- `vw_computational_issues`
- `vw_issue_audit`

The master audit view brings together identified data quality issues for reporting and investigation.

## Key Analytical Outcomes

This project demonstrates how SQL and Power BI can be used together to:

- Measure data quality systematically.
- Identify the most affected datasets and issue categories.
- Highlight critical data quality risks.
- Investigate potential root causes.
- Support data quality improvement and remediation decisions.

## Skills Demonstrated

- SQL querying and data validation
- PostgreSQL database management
- Data quality auditing
- Data profiling and issue investigation
- KPI development using DAX
- Power BI dashboard development
- Analytical thinking and business insights

## Project Purpose

This project demonstrates a practical approach to data quality auditing and monitoring, showing how raw business data can be evaluated and transformed into meaningful information for data-driven decision-making.

---

**Project Category:** Data Analytics | Data Quality | Business Intelligence

**Tools:** PostgreSQL | SQL | Power BI | DAX
