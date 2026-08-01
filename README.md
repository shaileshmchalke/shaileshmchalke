<h1 align="center">Shailesh Chalke</h1>
<h3 align="center">Snowflake Data Engineer — Cloud ELT, Migration & Performance</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=17&pause=1000&color=29B5E8&center=true&vCenter=true&width=650&lines=Snowflake+%C2%B7+dbt+Core+%C2%B7+Apache+Airflow+%C2%B7+Python;Oracle+%2F+SQL+Server+%E2%86%92+Snowflake+Migration;Medallion+Architecture+%C2%B7+SCD+Type+2+%C2%B7+Metadata-Driven+ELT;Open+to+Snowflake+Data+Engineering+Opportunities" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/SnowPro%20Core-Certified-29B5E8?style=flat-square&logo=snowflake&logoColor=white"/>
  <img src="https://img.shields.io/badge/SnowPro%20Advanced-Data%20Engineer-29B5E8?style=flat-square&logo=snowflake&logoColor=white"/>
  <img src="https://img.shields.io/badge/Based%20in-Pune%2C%20India-6c757d?style=flat-square"/>
  <img src="https://img.shields.io/badge/Open%20to-Data%20Engineering%20Roles-success?style=flat-square"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/shailesh-chalke/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:shailesh.chalke.data@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white"/></a>
</p>

---

### Introduction

I design and deliver production-grade Snowflake ELT platforms that modernize legacy Oracle and SQL Server workloads into scalable, governed, and high-performance cloud data platforms.

My work focuses on data modeling, orchestration, performance optimization, and cost-efficient data processing — building reliable pipelines that are easy to maintain, audit-ready, and built for enterprise-scale analytics.

With 14+ years of overall IT experience, including 5+ years specializing in Snowflake Data Engineering, I enjoy solving complex data engineering challenges through modern architecture, automation, and cloud-native best practices.

---

### About

My day-to-day is Medallion architecture — Bronze, Silver, Gold — built on dbt Core and orchestrated through Apache Airflow, with Python filling the gaps around ingestion and validation. I lean toward metadata-driven design: config-driven joins over hardcoded SQL, reusable Jinja macros over copy-pasted models, SCD Type 2 snapshots over manual history tracking. A pipeline is only good if the next engineer can extend it without rewriting it.

The other half of the job is migration and governance. I've moved production Oracle systems onto Snowflake, converted nightly batch procedures into incremental dbt models, and spent a fair amount of time inside Query Profile chasing down the warehouse settings quietly inflating a Snowflake bill. RBAC and Dynamic Data Masking aren't an afterthought — they go in alongside the pipeline, not after an audit asks for them.

---

### Core Expertise

- **Snowflake Engineering** — Enterprise edition, External Stages, Storage Integration, Snowpipe, Time Travel, Zero-Copy Cloning, Clustering Keys, Query Profile tuning
- **ELT with dbt Core** — Incremental models, Jinja macros, Snapshots (SCD Type 2), singular tests, ephemeral models, source & lineage documentation
- **Orchestration** — Apache Airflow DAGs, dependency management, retry logic, failure alerting, scheduled production runs
- **Data Modeling** — Medallion architecture, Star Schema, One Big Table (OBT), metadata-driven pipeline design, fact/dimension modeling
- **Cloud Migration** — Oracle & SQL Server → Snowflake, schema conversion, batch-to-incremental re-architecture, cutover validation
- **Governance & Security** — RBAC, Dynamic Data Masking, Row Access Policies, column-level security
- **Cloud & Storage** — Azure Blob Storage, Azure Data Factory, AWS S3, Service Principal auth
- **Languages** — Advanced SQL, T-SQL, PL/SQL, Python (Pandas, Snowflake Connector), Jinja2

---

### Certifications

<p align="center">
  <img src="https://img.shields.io/badge/SnowPro%20Core-Certified-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white"/>
  &nbsp;&nbsp;
  <img src="https://img.shields.io/badge/SnowPro%20Advanced-Data%20Engineer-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white"/>
</p>

---

### Technology Stack

**Snowflake** &nbsp;
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Snowpipe](https://img.shields.io/badge/Snowpipe-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Snowpark](https://img.shields.io/badge/Snowpark-29B5E8?style=flat-square&logo=snowflake&logoColor=white)

**Transformation & Orchestration** &nbsp;
![dbt](https://img.shields.io/badge/dbt%20Core-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![ADF](https://img.shields.io/badge/Azure%20Data%20Factory-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

**Languages & Databases** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle%20PL%2FSQL-F80000?style=flat-square&logo=oracle&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)

**Cloud** &nbsp;
![Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS%20S3-FF9900?style=flat-square&logo=amazonaws&logoColor=white)

**Developer Tools** &nbsp;
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

---

### Featured Projects

**[🚀 sql-server-to-snowflake-migration](https://github.com/shaileshmchalke/sql-server-to-snowflake-migration)**
Migrating off SQL Server usually means hand-converting schemas and hoping the data lands intact. This project automates the schema conversion and data validation steps of that migration end to end, so the cutover itself is repeatable instead of a one-off script someone runs at 2am.
`Snowflake` `Python` `Azure Data Factory`

**[💰 snowflake-finops-toolkit](https://github.com/shaileshmchalke/snowflake-finops-toolkit)**
Snowflake bills climb quietly — an idle warehouse here, an oversized auto-suspend setting there. This toolkit tracks credit consumption in real time and surfaces the warehouse configurations actually driving cost, the same class of tuning that cut compute spend by 40% on a past production migration.
`SQL` `Python` `Streamlit`

**[⚡ modern-elt-pipeline-dbt-adf](https://github.com/shaileshmchalke/modern-elt-pipeline-dbt-adf)**
A reference implementation of the Medallion architecture (Bronze → Silver → Gold) I run in production — dbt Core for transformation, Azure Data Factory for ingestion, built to scale as new source systems get added.
`Snowflake` `dbt Core` `Azure Data Factory`

**[🔒 enterprise-rbac-data-masking](https://github.com/shaileshmchalke/healthcare-hipaa-rbac-audit)**
A layered RBAC hierarchy paired with Dynamic Data Masking at the column level, modeled on the governance patterns used to pass 100% of internal audits across 30+ production schemas in a prior engagement.
`Snowflake Security` `RBAC` `Dynamic Data Masking`

**[🧊 snowflake-iceberg-lakehouse](https://github.com/shaileshmchalke/snowflake-iceberg-lakehouse)**
A strategy and reference setup for Iceberg tables on Snowflake — evaluating where open table formats make sense for cheaper, more flexible long-term storage.
`Iceberg` `Snowflake`

---

### What I Build

- Production-grade ELT pipelines on Medallion architecture
- Legacy Oracle & SQL Server → Snowflake migrations
- Metadata-driven, config-based data models
- Incremental dbt models with SCD Type 2 history
- Airflow-orchestrated pipelines with retry and alerting
- Warehouse performance tuning & cost optimization
- RBAC and Dynamic Data Masking for governed data delivery

---

### GitHub Analytics

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=shaileshmchalke&theme=default&hide_border=true" />
</p>

<p align="center">
  <a href="https://github.com/shaileshmchalke">
    <img src="https://github-profile-trophy.vercel.app/?username=shaileshmchalke&theme=flat&no-frame=true&column=4&margin-w=10" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=shaileshmchalke&color=29B5E8&style=flat-square&label=Profile+Views"/>
</p>

---

### Open to Work

Currently open to **Snowflake Data Engineer**, **Data Engineer**, and **Cloud Data Engineering** roles — full-time or contract.

---

### Connect

<p align="center">
  <a href="https://www.linkedin.com/in/shailesh-chalke/">
    <img src="https://img.shields.io/badge/LinkedIn-shailesh--chalke-0077B5?style=for-the-badge&logo=linkedin"/>
  </a>
  &nbsp;
  <a href="mailto:shailesh.chalke.data@gmail.com">
    <img src="https://img.shields.io/badge/Email-shailesh.chalke.data%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

<p align="center"><i>Building scalable data platforms, one pipeline at a time.</i></p>
