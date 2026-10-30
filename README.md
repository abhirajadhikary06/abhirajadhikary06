# Abhiraj Adhikary

Software Engineer focused on **Backend Engineering, Data Engineering, and Distributed Systems**. I build complete data platforms and backend systems, with an interest in the engineering problems behind scalability, reliability, performance, and data-intensive applications.

Currently engineering at **OBLIQ-in**, working on backend infrastructure, database performance, and platform reliability. Previously a Backend Engineering Intern at **Springer Capital**.

---

## Experience

**Software Engineer — OBLIQ-in**  
*2026 – Present*

- Building core platform capabilities for secure client document sharing, audit workflow automation, and firm workspace synchronization.
- Improved workspace loading from **~11s to ~98ms (112× faster)** through database indexing and N+1 query elimination.
- Reduced average database latency by **52.26%** through connection-pool optimization.
- Reduced CI test execution time by **49%** using dynamic test concurrency; improved test infrastructure, database health checks, and dependency security.

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
| **[Payment Gateway Data Platform](https://github.com/abhirajadhikary06/payment-gateway-databricks-pipeline)** | Data engineering pipeline exploring payment data processing and lakehouse workflows with Databricks. |

---

## Open Source & Engineering Contributions
<table width="100%">
  <tr>
    <td width="28%" valign="top">
      <strong>aio-libs / aiocache</strong><br/>
      <sub>Open Source · Python</sub><br/><br/>
      <a href="https://github.com/aio-libs/aiocache/pull/1095">PR #1095 ↗</a><br/>
      <sub>OPEN</sub>
    </td>
    <td valign="top">
      <strong>Fix cached_stampede locking when lease is None</strong><br/><br/>
      Corrected the mismatch between documented and actual locking behavior by bypassing RedLock when <code>lease=None</code> or <code>0</code>. Added regression coverage for concurrent execution and keyword forwarding.<br/><br/>
      <sub>Validation: 58 decorator tests passed</sub>
    </td>
  </tr>
  <tr>
    <td colspan="2"><hr/></td>
  </tr>
  <tr>
    <td width="28%" valign="top">
      <strong>OBLIQ-in / obliq-in-app</strong><br/>
      <sub>Product Engineering · Backend</sub><br/><br/>
      <a href="https://github.com/OBLIQ-in/obliq-in-app/pull/109">PR #109 ↗</a><br/>
      <sub>MERGED</sub>
    </td>
    <td valign="top">
      <strong>Database performance and query optimization</strong><br/><br/>
      Added 29 database indexes, eliminated N+1 workspace loading through grouped aggregation, and optimized PostgreSQL connection pooling.<br/><br/>
      <sub>Impact: ~11s → ~98ms workspace loading · 52.26% lower average latency</sub>
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

---

## Connect

[LinkedIn](https://www.linkedin.com/in/abhirajadhikary06) · [GitHub](https://github.com/abhirajadhikary06) · [LeetCode](https://leetcode.com/u/0vz9vQHr2y/) · [HackerRank](https://www.hackerrank.com/profile/abhirajadhikary1) · [Devfolio](https://devfolio.co/@abhirajadhikary) · [DEV Community](https://dev.to/abhirajadhikary06)
