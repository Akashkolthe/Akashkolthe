# 👋 Hi, I’m Akash Kolthe

🚀 **Data Engineer | Scalable Data Pipelines | Batch + Streaming Systems**

I build **production-grade data pipelines** across batch and streaming systems, focusing on **data reliability, performance, and scalable architecture**.
My goal is to design systems that analytics teams can trust — not just pipelines that “run”.

---

## ⚡ Core Expertise

* **Languages:** SQL (Advanced), Python
* **Data Platforms:** Snowflake, Amazon Redshift, Databricks
* **Transformation:** dbt Core (models, tests, snapshots, macros)
* **Streaming & Pipelines:** Delta Live Tables (DLT), Auto Loader
* **Orchestration:** Apache Airflow
* **Cloud:** AWS (S3, Glue, Lambda)
* **Architecture:** Medallion (Bronze/Silver/Gold), Incremental Models, SCD Type 2

---

## 🌟 Featured Project — Airbnb Analytics Data Warehouse (Batch)

**End-to-end ELT pipeline using AWS + Snowflake + dbt**

### 🔧 What I Built

* Data pipeline: **S3 → Snowflake → dbt models**
* Medallion architecture for clean data layering
* Analytics-ready datasets for BI/reporting

### 💡 Key Engineering Decisions

* **Jinja Macros:** Reduced model duplication (~70%)
* **SCD Type 2 Snapshots:** Historical tracking of entities
* **Incremental Models:** Reduced compute cost and runtime
* **Data Quality Tests:** Enforced trust and consistency

👉 **Result:** Scalable, cost-efficient warehouse aligned with real-world analytics engineering practices

🔗 Repository: https://github.com/Akashkolthe/Airbnb-Data-Engineering-Pipeline-dbt-Snowflake-

---

## 🌟 Featured Project — Databricks DLT Pipeline (Streaming)

**Real-time pipeline using Delta Live Tables (DLT)**

### 🔧 What I Built

* End-to-end pipeline using **DLT (Bronze → Silver → Gold)**
* Streaming ingestion via **Auto Loader (cloudFiles)**
* Data validation and transformation layers
* Aggregated outputs for analytics

---

### ⚖️ Batch vs Streaming (Key Insight)

* **Batch (dbt):** Controlled, cost-efficient, easier debugging
* **Streaming (DLT):** Low-latency, continuous processing, stateful

👉 Learned how to choose the right architecture based on **latency, scale, and complexity**

---

### ⚠️ Key Challenges Solved

* **State Management:**

  * Understood DLT checkpointing and pipeline storage behavior

* **Schema Evolution:**

  * Handled invalid columns and schema changes proactively

* **Execution Model:**

  * Built pipelines using DAG dependencies (`dlt.read`, `dlt.read_stream`)

---

### 💡 Why DLT over Spark Jobs?

* Built-in orchestration and dependency management
* Native data quality (`@dlt.expect`)
* Automatic lineage and monitoring
* Lower operational overhead

👉 **Result:** Reliable streaming pipeline with built-in governance and scalability

🔗 Repository: https://github.com/Akashkolthe/Databricks-dlt-end-to-end-pipeline

---

## 🧠 Architecture Snapshot

```id="arch123"
Batch:     Source → S3 → Snowflake → dbt → BI
Streaming: Source → Auto Loader → DLT → Delta Tables → Analytics
```

---

## 📈 Currently Leveling Up

* Designing **production-grade Airflow DAGs** (retries, failure handling)
* Advanced **Snowflake performance tuning**
* Data observability (freshness, SLAs, anomaly detection)
* Scaling data platforms across domains

---

## 📫 Connect

* ✉️ Email: **[Akashtheviper@gmail.com](mailto:Akashtheviper@gmail.com)**
* 💼 LinkedIn: **https://linkedin.com/in/akash-k-a44648222**

---

⚡ *I build data systems that are reliable, scalable, and production-ready — not just pipelines that run once.*
