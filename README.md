# data-analyst-rahul

## 📌 Overview
This repository contains two major data analytics projects completed as part of the **BUSI 653-06: Cloud Computing Technologies** course at **University Canada West**. These projects leverage AWS cloud services and data analytics techniques to provide insights and improve decision-making.

## 🏆 Projects
### 1️⃣ Public Trees Health Monitoring System for the City of Vancouver
**Objective**: Analyze and monitor the health of public trees in Vancouver using cloud-based data analytics.

- **Exploratory Data Analysis (EDA)**
  - Identified missing values and skewed distributions.
  - Used AWS Glue DataBrew for data profiling.
  - Geospatial mapping of tree density.

- **Descriptive Analysis**
  - Summarized health trends and species distribution.
  - Ranked top 5 most common tree species.
  - Used AWS Athena for SQL-based analysis.

- **Diagnostic Analysis**
  - Investigated factors affecting tree health.
  - Correlation analysis between diameter and planting year.

- **Data Wrangling**
  - Cleaned and transformed datasets.
  - Standardized `date_planted` format.
  - Removed duplicate `TREE_ID` values.

- **Data Quality Control**
  - Validated data accuracy and completeness.
  - Monitored anomalies using AWS CloudWatch.

🔗 **Project Files**:  
- `public-trees-analysis/` – Data profiling reports, transformation scripts, SQL queries  
- `visualizations/` – Charts, graphs, and geospatial maps  
- `data/` – Cleaned dataset (CSV/Parquet format)

---

### 2️⃣ Employee Dispute Resolution System at UCW
**Objective**: Analyze employee conflict resolution trends at UCW to improve mediation strategies.

- **Exploratory Data Analysis (EDA)**
  - Identified common dispute types and resolution patterns.
  - Examined missing values in HR records.

- **Descriptive Analysis**
  - Aggregated dispute resolution success rates.
  - Ranked most common HR conflicts.

- **Diagnostic Analysis**
  - Correlated dispute resolution attempts with employee satisfaction.
  - Identified key challenges in conflict resolution.

- **Data Wrangling**
  - Cleaned and structured HR data.
  - Standardized categorical variables.

- **Data Quality Control**
  - Ensured data consistency and accuracy.
  - Monitored HR dispute data with AWS CloudWatch.

🔗 **Project Files**:  
- `hr-dispute-resolution/` – SQL queries, data transformation scripts  
- `visualizations/` – Conflict resolution trend analysis  
- `data/` – Cleaned HR dataset  

---

## 🛠 Tools & Technologies
- **Cloud Services**: AWS S3, AWS Glue, AWS Athena, AWS CloudWatch
- **Programming**: Python, SQL
- **Data Formats**: CSV, Parquet
- **Visualization**: AWS QuickSight, Geospatial Mapping
- **Security**: AWS KMS for encryption, IAM roles for access control

---
