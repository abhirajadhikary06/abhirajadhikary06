# Abhiraj Adhikary

**Software Engineer · Backend Systems · Data Engineering · Distributed Systems**

I’m a software engineer focused on **backend systems, data engineering, and distributed systems**. I build complete data platforms and work on performance, reliability, and scalable system design.

Currently engineering at **OBLIQ**, building backend capabilities and improving application performance. Previously, I worked as a Backend Intern at **Springer Capital**, contributing to backend migration and data extraction systems.

## Experience

**OBLIQ-in — Engineer**  
*2026 – Present*

- Building backend capabilities for secure client document sharing, audit workflows, and firm workspace synchronization.
- Improved workspace loading from **~11s to ~98ms** by eliminating N+1 queries and optimizing database access.
- Added **29 database indexes**, including covering and partial indexes, to improve query performance.
- Tuned PostgreSQL connection pooling, reducing average latency by **52.26%**.
- Improved CI performance through dynamic test concurrency, reducing test runtime by **49%**.
- Strengthened reliability through database health checks, automated migrations, and dependency security updates.

**Selected engineering work:** [Database performance optimization — PR #109](https://github.com/OBLIQ-in/obliq-in-app/pull/109) · Merged

**Springer Capital — Backend Engineering Intern**  
*July 2025 – October 2025*

- Led the migration of Salesforce extraction components from Flask/SQLite to Django/PostgreSQL.
- Built and validated backend APIs using Swagger/OpenAPI.
- Worked on Salesforce connectivity, source extraction pipelines, and Azure deployment workflows.
- Contributed to testing, debugging, and release coordination in an Agile environment.

## Open Source Contributions

I contribute to backend and infrastructure projects, focusing on correctness, reproducible bugs, regression tests, and performance.

### [aio-libs/aiocache](https://github.com/aio-libs/aiocache)

**[Fix `cached_stampede` locking when `lease` is `None`](https://github.com/aio-libs/aiocache/pull/1095)**  
<sub>Python · Asyncio · Caching · Regression Testing · Open PR</sub>

- Fixed the behavior of `cached_stampede` when locking is disabled with `lease=None` or `lease=0`.
- Bypassed `RedLock` in the disabled-locking path while preserving cache-write and skip-cache behavior.
- Added parametrized async regression tests covering concurrent execution and keyword argument forwarding.
- Validated against all **58 tests** in `tests/ut/test_decorators.py`.

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

Apache Kafka · Apache Spark · PySpark · Apache Flink · Spark Structured Streaming

</td>
<td width="50%" valign="top">

**Data Engineering**

Airflow · dbt · Delta Lake · Databricks · Snowflake · Hadoop · Hive · HDFS

**Cloud & Infrastructure**

AWS · Azure · Docker · GitHub Actions · Cloudflare · Render

**Developer Tools**

Git · GitHub · Postman · Jupyter · Supabase · Metabase

**Analytics & ML**

Pandas · NumPy · SciPy · Scikit-learn · TensorFlow

</td>
</tr>
</table>

## Research Interests

Distributed Systems · Serverless Computing · Database Systems · Streaming Architectures · Cloud Engineering · Performance Evaluation

## Connect

[LinkedIn](https://www.linkedin.com/in/abhirajadhikary06) · [GitHub](https://github.com/abhirajadhikary06) · [LeetCode](https://leetcode.com/u/0vz9vQHr2y/) · [DEV](https://dev.to/abhirajadhikary06) · [HackerRank](https://www.hackerrank.com/profile/abhirajadhikary1)
