<!-- DEVTOWN-BANNER:START -->
[![My DevTown](https://git-devtown.netlify.app/api/banners/abhirajadhikary06.png?mode=day&v=7421)](https://git-devtown.netlify.app/@abhirajadhikary06)
<!-- DEVTOWN-BANNER:END -->


# Abhiraj Adhikary

Software Engineer focused on **Backend Engineering, Data Engineering, and Distributed Systems**. I build complete data platforms and backend systems, with an interest in the engineering problems behind scalability, reliability, performance, and data-intensive applications.

Currently engineering at **OBLIQ-in**, working on backend infrastructure, database performance, and platform reliability. Previously a Backend Engineering Intern at **Springer Capital**.

---

## Experience

**Software Engineer — OBLIQ-in**  
*2026 – Present*

- Building core platform capabilities for secure client document sharing, audit workflow automation, and firm workspace synchronization.
- Optimized PostgreSQL performance through **29 schema and covering indexes**, N+1 query elimination, and connection-pool tuning—reducing workspace load time from **~11s to ~98ms (112× faster)** and database latency by **52.26%**.
- Engineered end-to-end CI/CD infrastructure with GitHub Actions, automated database migrations, quality gates, security checks, and dynamic test concurrency—reducing test execution time by **49%**.
- Implemented production release and packaging workflows, including **PyPI publishing with OIDC-based authentication**, Hatch-VCS versioning, pre-commit automation, and **distroless Docker builds with GHCR releases**.

**Backend Engineering Intern — Springer Capital**  
*Jul 2025 – Oct 2025*

- Led the migration of Salesforce extraction components from **Flask/SQLite to Django/PostgreSQL**.
- Worked on backend API validation and debugging using Swagger/OpenAPI, Salesforce connectivity, and source-extraction pipelines.
- Supported Azure deployment, configuration, and release workflows in an Agile environment.

---

## Selected Projects

| Project | Overview |
|---|---|
| **[Real-Time Search Pipeline](https://github.com/abhirajadhikary06/realtime-search-pipeline)** | Kafka and Flink-based streaming pipeline with Elasticsearch for indexing and Kibana for search observability. |
| **[CDC Streaming Pipeline](https://github.com/abhirajadhikary06/cdc-streaming-pipeline)** | PostgreSQL CDC with Debezium and Kafka, processed through Spark Structured Streaming and Delta Lake. |
| **[GTFS Real-Time Streaming](https://github.com/abhirajadhikary06/gtfs-realtime-streaming-pipeline)** | Event-time streaming architecture for transit data using Spark Structured Streaming and a Kappa-style design. |
| **[Weather Databricks Lakehouse](https://github.com/abhirajadhikary06/weather-databrick-lakehouse-pipeline)** | Databricks-based lakehouse pipeline for ingesting and processing weather data through structured data engineering workflows. |
| **[Instacart Lakehouse Pipeline](https://github.com/abhirajadhikary06/instacart-lakehouse-pipeline)** | End-to-end lakehouse pipeline using dlt, MinIO, Spark, Delta Lake, PostgreSQL, and dbt to process Instacart datasets across Bronze, Silver, and Gold layers. |
| **[Hallbook](https://github.com/abhirajadhikary06/hallbook)** | Web-based platform with a Python backend and PostgreSQL database. [Live Application](https://hallbook-e0u1.onrender.com). |
| **[attend](https://github.com/abhirajadhikary06/attend)** | Offline-first Windows desktop application for real-time facial recognition attendance management using InsightFace, ArcFace, FAISS, OpenCV, and SQLite. [Live Website](https://attend-desktop.netlify.app). |

---

## Open Source & Engineering Contributions

<table>
<tr>
<td width="90" align="center" valign="middle">
<a href="https://github.com/aio-libs/aiocache">
<img src="https://github.com/aio-libs.png?size=64" width="36" alt="aio-libs"/>
</a>
</td>
<td valign="middle">
<strong><a href="https://github.com/aio-libs/aiocache/pull/1095">Fix cached_stampede locking when lease is None</a></strong>
<br/>
<img src="https://img.shields.io/badge/⑂-Open-238636?style=flat-square" height="20" alt="Open PR"/>
<br/>
<sub><strong>#1095</strong> · <a href="https://github.com/aio-libs/aiocache">aio-libs/aiocache</a> · Python</sub>
</td>
</tr>
<tr>
<td width="90" align="center" valign="middle">
<a href="https://github.com/OBLIQ-in">
<img src="https://github.com/OBLIQ-in.png?size=64" width="36" alt="OBLIQ-in"/>
</a>
</td>
<td valign="middle">
<strong><a href="https://github.com/OBLIQ-in/obliq-in-app/pull/109">perf: optimize database indexes, fix N+1 query, and improve connection pooling</a></strong>
<br/>
<img src="https://img.shields.io/badge/⑂-Merged-8957e5?style=flat-square" height="20" alt="Merged PR"/>
<br/>
<sub><strong>#109</strong> · <a href="https://github.com/OBLIQ-in/obliq-in-app">OBLIQ-in/obliq-in-app</a> · Backend</sub>
</td>
</tr>
<tr>
<td width="90" align="center" valign="middle">
<a href="https://github.com/manta-plan/manta">
<img src="https://github.com/manta-plan.png?size=64" width="36" alt="manta-plan"/>
</a>
</td>
<td valign="middle">
<strong><a href="https://github.com/manta-plan/manta/pull/226">feat(ui): add documentation link to header (#4)</a></strong>
<br/>
<img src="https://img.shields.io/badge/⑂-Open-238636?style=flat-square" height="20" alt="Open PR"/>
<br/>
<sub><strong>#226</strong> · <a href="https://github.com/manta-plan/manta">manta-plan/manta</a> · UI Feature</sub>
</td>
</tr>
<tr>
<td width="90" align="center" valign="middle">
<a href="https://github.com/BlitzKraft/saythanks.io">
<img src="https://github.com/BlitzKraft.png?size=64" width="36" alt="BlitzKraft"/>
</a>
</td>
<td valign="middle">
<strong><a href="https://github.com/BlitzKraft/saythanks.io/pull/627">feat: add Mastodon OAuth login integration and database compatibility</a></strong>
<br/>
<img src="https://img.shields.io/badge/⑂-Open-238636?style=flat-square" height="20" alt="Open PR"/>
<br/>
<sub><strong>#627</strong> · <a href="https://github.com/BlitzKraft/saythanks.io">BlitzKraft/saythanks.io</a> · Backend</sub>
</td>
</tr>
<tr>
<td width="90" align="center" valign="middle">
<a href="https://github.com/BlitzKraft">
<img src="https://github.com/BlitzKraft.png?size=64" width="36" alt="BlitzKraft"/>
</a>
</td>
<td valign="middle">
<strong><a href="https://github.com/BlitzKraft/saythanks.io/pull/626">Fix #624: Implement client-side image file size validation and compression to prevent 504 gateway timeouts</a></strong>
<br/>
<img src="https://img.shields.io/badge/⑂-Open-238636?style=flat-square" height="20" alt="Open PR"/>
<br/>
<sub><strong>#626</strong> · <a href="https://github.com/BlitzKraft/saythanks.io">BlitzKraft/saythanks.io</a> · Backend</sub>
</td>
</tr>
<tr>
  <td width="90" align="center" valign="middle">
    <a href="https://github.com/AlgenAI">
      <img src="https://github.com/AlgenAI.png?size=64" width="36" alt="AlgenAI"/>
    </a>
  </td>
  <td valign="middle">
    <strong><a href="https://github.com/AlgenAI/algen-agent-runtime/pull/107">CI: Add offline Lychee link checker workflow and fix documentation link</a></strong>
    <br/>
    <img src="https://img.shields.io/badge/⑂-Open-238636?style=flat-square" height="20" alt="Open PR"/>
    <br/>
    <sub><strong>#107</strong> · <a href="https://github.com/AlgenAI/algen-agent-runtime">AlgenAI/algen-agent-runtime</a> · CI / DevOps</sub>
  </td>
</tr>
</table>

---

## Technical Stack

<table>
<tr>
<td width="50%" valign="top">

**Languages**
  
Python · Go · C · R · Bash

**Backend Engineering**

Django · Flask · FastAPI · Tornado

**Databases**

PostgreSQL · MySQL · SQL Server · SQLite · DuckDB · Cassandra · HBase

**Distributed & Streaming Systems**

Kafka · Apache Spark · PySpark · Flink · Spark Structured Streaming

</td>
<td width="50%" valign="top">

**Data Engineering**

Airflow · dbt · Delta Lake · Databricks · Snowflake · Hadoop · Hive · HDFS

**Cloud & Infrastructure**

AWS · Azure · Docker · GitHub Actions · Cloudflare · Render

**Developer Tools**

Git · GitHub · Postman · Jupyter · Supabase · Metabase

**Analytics & Machine Learning**

Pandas · NumPy · SciPy · Scikit-learn · TensorFlow

</td>
</tr>
</table>

---

## Research Interests

Distributed Systems · Serverless Computing · Database Systems · Streaming Architectures · Cloud Engineering · Performance Evaluation and Reproduction of Research Papers

<table>
<thead>
<tr>
<th>Research Paper</th>
<th>Publication Date</th>
<th>Publication Platform</th>
</tr>
</thead>
<tbody>
<tr>
<td><a href="https://zenodo.org/records/19365667"># llmsays: One-Line LLM Inference with Automatic Prompt-Tier Routing and Multi-Provider Failover</a></td>
<td>1 April 2026</td>
<td><a href="https://zenodo.org/records/19365667">Zenodo</a></td>
</tr>
</tbody>
</table>

---

## Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhirajadhikary06)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/abhirajadhikary06)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/0vz9vQHr2y/)
[![HackerRank](https://img.shields.io/badge/HackerRank-00EA64?style=for-the-badge&logo=hackerrank&logoColor=black)](https://www.hackerrank.com/profile/abhirajadhikary1)
[![Devfolio](https://img.shields.io/badge/Devfolio-3770FF?style=for-the-badge&logo=devfolio&logoColor=white)](https://devfolio.co/@abhirajadhikary)
[![DEV Community](https://img.shields.io/badge/DEV_Community-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white)](https://dev.to/abhirajadhikary06)
