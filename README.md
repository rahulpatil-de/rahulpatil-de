# Hi, I'm Rahul Patil 👋

### AWS Data Engineer · 6.5 Years of Experience

I design and build **scalable, production-grade data pipelines** on AWS — from ingestion to data lake to orchestration. I've delivered end-to-end solutions single-handedly, including full CI/CD automation, multi-environment Airflow setups, and vendor file processing pipelines handling hundreds of feeds daily.

---

## 🔧 What I Build

- ⚙️ **Automated DAG Factories** — Generate 500+ Airflow DAGs from a single YAML file, no Python coding required
- 🏭 **Multi-Vendor File Pipelines** — Ingest CSV, XLSX, CSV.GZ from any vendor → validate → Parquet data lake
- 🚀 **CI/CD for Data** — End-to-end deployment pipelines for data infrastructure, built from scratch
- ☁️ **Cloud Modernization** — Migrate legacy on-prem ETL processes to AWS cloud architecture

---

## 🛠️ Tech Stack

**AWS Services**

![MWAA](https://img.shields.io/badge/AWS-MWAA-FF9900?logo=amazonaws&logoColor=white)
![Glue](https://img.shields.io/badge/AWS-Glue-FF9900?logo=amazonaws&logoColor=white)
![Step Functions](https://img.shields.io/badge/AWS-Step_Functions-FF9900?logo=amazonaws&logoColor=white)
![Lambda](https://img.shields.io/badge/AWS-Lambda-FF9900?logo=amazonaws&logoColor=white)
![S3](https://img.shields.io/badge/AWS-S3-569A31?logo=amazons3&logoColor=white)
![Athena](https://img.shields.io/badge/AWS-Athena-FF9900?logo=amazonaws&logoColor=white)
![DynamoDB](https://img.shields.io/badge/AWS-DynamoDB-4053D6?logo=amazondynamodb&logoColor=white)
![EventBridge](https://img.shields.io/badge/AWS-EventBridge-FF9900?logo=amazonaws&logoColor=white)
![SNS](https://img.shields.io/badge/AWS-SNS-FF9900?logo=amazonaws&logoColor=white)
![SQS](https://img.shields.io/badge/AWS-SQS-FF9900?logo=amazonaws&logoColor=white)
![Redshift](https://img.shields.io/badge/AWS-Redshift-8C4FFF?logo=amazonredshift&logoColor=white)

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3.11-3776AB?logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-3.x-E25A1C?logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache-Airflow-017CEE?logo=apacheairflow&logoColor=white)
![Terraform](https://img.shields.io/badge/IaC-Terraform-7B42BC?logo=terraform&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Redshift%20%2F%20Athena-336791?logo=postgresql&logoColor=white)

---

## 📌 Featured Projects

### 🔗 [aws-airflow-dag-factory](https://github.com/rahulpatil-de/aws-airflow-dag-factory)
> Create production-ready Airflow DAGs by dropping a single YAML file into S3 — no Python coding required.

- Lambda + Jinja2 renders a full DAG Python file from a YAML config
- Supports 10+ task types: Glue crawlers, job steps, S3 actions, email notifications, asset scheduling
- Used to automate creation of **500+ production DAGs** across DEV, TEST, PROD
- Stack: `AWS MWAA` `Lambda` `S3` `Jinja2` `Python`

---

### 🔗 [aws-multi-vendor-pipeline](https://github.com//rahulpatil-de/aws-multi-vendor-pipeline)
> Fully automated multi-vendor file ingestion pipeline — handles CSV, XLSX, CSV.GZ from any vendor, validates schemas, writes Parquet snapshots, archives originals.

- DynamoDB-driven config — add a new vendor with zero code changes
- Schema drift detection vs Athena catalog with SNS alerting
- Parallel processing with ThreadPoolExecutor across Glue workers
- Full infrastructure as code with **Terraform**
- Stack: `Glue` `Step Functions` `Lambda` `DynamoDB` `SQS` `SNS` `Athena` `Terraform` `PySpark`

---

## 📈 What I'm Currently Working On

- 🧱 Building a **CI/CD framework** for data pipeline deployments on AWS
- 🌐 Available for **freelance projects** in AWS Data Engineering

---

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rahul-patil2025)
[![Email](https://img.shields.io/badge/Email-Reach_Out-D14836?logo=gmail&logoColor=white)](mailto:rahulpatil.wisdom@gmail.com)

> 💼 **Open to freelance AWS Data Engineering projects** — pipelines, Airflow setup, cloud modernization, Terraform IaC.
