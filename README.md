# 📊 Insurance Policy Lifecycle Analysis

## 🔍 Project Overview
This project simulates a supplemental insurance environment to analyze policy lifecycles, including trends in:
- Policy **renewals** and **churn**
- **Claims** frequency and status
- **Customer behavior** by demographics

The goal is to build a full ETL pipeline using **Python**, **SQL**, **Airflow**, and **Power BI** to replicate real-world data workflows in the insurance industry.

---

## 🎯 Objectives
- Design a relational database schema for insurance lifecycle data
- Build a Python ETL pipeline to ingest and clean data
- Automate workflows using Apache Airflow
- Use SQL to query and summarize trends
- Visualize insights through Power BI dashboards
- Define business metrics to guide decision-making

---

## 🛠️ Tools & Technologies
| Tool          | Purpose                        |
|---------------|--------------------------------|
| Python        | Data extraction and transformation |
| SQL (SQLite/PostgreSQL) | Database design and querying |
| Apache Airflow | Workflow orchestration         |
| Power BI      | Business intelligence dashboard |
| Git/GitHub    | Version control and collaboration |

---

## 🧱 Database Schema

**Tables:**
- `customers` – demographics of insurance customers
- `policies` – policy issue, renewal, and status data
- `claims` – claims tied to policies
- `payments` – premium payment tracking

---

## 🔄 ETL Workflow

1. **Extract**: Read raw CSV files from the `/data` folder
2. **Transform**: Clean and standardize using Python
3. **Load**: Insert into a structured SQL database
4. **Orchestrate**: Automate with Apache Airflow
5. **Visualize**: Display insights in Power BI

---

## 📊 Key Business Metrics

- **Renewal Rate** = % of policies renewed
- **Churn Rate** = % of policies not renewed
- **Avg. Claim Amount** = total claim value ÷ number of claims
- **Claim Frequency** = average number of claims per policy
- **Resolution Time** = claim closure time in days

---

## 📊 Entity Relationship Diagram (ERD)

[📄 View Full ERD (PDF)](docs/insurance_erd.pdf)

