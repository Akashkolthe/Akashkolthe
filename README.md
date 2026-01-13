# 👋 Hi, I’m Akash Kolthe

🚀 **Data Engineer | Analytics Engineering | Cloud Data Platforms**

I build **scalable, cost-efficient data pipelines and analytics warehouses** that support real business use cases. My focus is on designing reliable data models, enforcing data quality, and optimizing performance so analytics teams can move fast without breaking trust in the data.

I work primarily in **cloud-based ELT architectures**, applying modern data engineering best practices used in production environments.

---

## 🛠️ Core Skills & Technologies (Recruiter Keywords)

**Languages & Querying**

* SQL (Advanced), Python, Jinja

**Data Warehousing & Analytics Platforms**

* Snowflake, Amazon Redshift

**Data Transformation & Orchestration**

* dbt Core (models, tests, snapshots, macros)
* Apache Airflow (learning / DAG-based orchestration)

**Data Modeling & Architecture**

* Medallion Architecture (Bronze / Silver / Gold)
* Incremental Models
* Slowly Changing Dimensions (SCD Type 2)
* One Big Table (OBT)

**Cloud & DevOps**

* AWS (S3, Lambda, Glue)
* Git, version-controlled data workflows

---

## 🌟 Featured Project: Airbnb Analytics Data Warehouse (AWS + dbt + Snowflake)

A **production-style analytics data warehouse** designed to handle growing data volume while keeping compute costs under control.

**What I Built**

* End-to-end ELT pipeline ingesting raw Airbnb data into Snowflake via AWS S3.
* Analytics-ready models structured using **Medallion Architecture** to separate raw, cleaned, and business-level data.

**Key Engineering Decisions**

* **Dynamic SQL with Jinja Macros:** Reduced model duplication by ~70% using configuration-driven transformations.
* **Historical Data Tracking:** Implemented **SCD Type 2 snapshots** to track changes in listings and host attributes over time.
* **Performance & Cost Optimization:** Used incremental materializations in Snowflake to minimize reprocessing and control warehouse spend.
* **Data Quality & Trust:** Applied dbt tests to enforce freshness, uniqueness, and referential integrity.

This project mirrors how modern analytics engineering teams design and maintain data platforms in real-world environments.

🔗 **Repository:** View project in this repo

---

## 🔧 What I’m Currently Improving

* Designing **Airflow DAGs** for reliable orchestration and failure handling
* Advanced **Snowflake performance tuning** (clustering, warehouse sizing, query profiling)
* Data observability and monitoring concepts (freshness, anomalies, SLAs)
* Production patterns for scaling dbt projects across multiple domains

---

## 🧱 Data Stack Diagram

> **High-level architecture of the analytics platform**

```
            Source Data
                |
                v
        AWS S3 (Raw Files)
                |
                v
      Snowflake – Bronze Layer
      (Raw, minimally transformed)
                |
                v
      Snowflake – Silver Layer
   (Cleaned, standardized, tested)
                |
                v
      Snowflake – Gold Layer
 (Business-ready analytics models)
                |
                v
        BI / Analytics / Reporting
```

**Tools Used**

* Ingestion & Storage: AWS S3
* Transformation & Modeling: dbt Core (Jinja, tests, snapshots)
* Data Warehouse: Snowflake

This structure enforces clear data lineage, improves debuggability, and supports scalable analytics workloads.

---

## 🚀 How This Would Run in Production

In a production environment, this project would operate as a fully automated ELT pipeline:

* **Ingestion:** Source data lands in AWS S3 on a scheduled or event-driven basis.
* **Orchestration:** Airflow triggers dbt runs based on upstream data availability and SLA requirements.
* **Transformation:** dbt models execute incrementally in Snowflake to minimize compute usage and control costs.
* **Data Quality:** Automated dbt tests validate freshness, uniqueness, and referential integrity before data is exposed.
* **Monitoring:** Failures and anomalies are surfaced through orchestration logs and alerts.
* **Consumption:** Analytics-ready Gold models are queried by BI tools or downstream applications.

This setup supports scale, team collaboration, and safe iteration without compromising data trust.

---

## 📫 Connect With Me

* ✉️ Email: **[Akashtheviper@gmail.com](mailto:Akashtheviper@gmail.com)**
* 💼 LinkedIn: **linkedin.com/in/akash K**

---

⚡ **Perspective**
Data is only valuable when it’s trustworthy, well-modeled, and cost-efficient. My goal is to build data systems that teams can rely on every day.
