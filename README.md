# Hi, I'm Unik 👋

Software engineer from Nepal. I build backend services and data platform infrastructure, and contribute to Apache DataFusion and Arrow projects.
Currently an SDE I at **HighRadius** on the G4 Data Platform team.

📫 unikdahal03@gmail.com · [LinkedIn](https://www.linkedin.com/in/unikdahal) · [Website](https://www.unikdahal.com.np)

---

## 🔧 What I work on

- **Query connectivity:** replaced JDBC/Thrift with Arrow Flight SQL and ADBC, cutting fixed query overhead from ~1.5 s to ~90 ms
- **Analytics migration:** supported moving analytical workloads from Snowflake to Spark, Iceberg and Kyuubi (~90% lower compute cost on migrated workloads)
- **Distributed workflows:** built a Saga-based orchestrator across seven microservices; environment recreation went from ~6 months to ~1 month
- **Multi-tenancy:** fair query admission using Redis-backed leases and tenant-aware routing
- **Production debugging:** database lock contention, catalog and metadata issues

## 🌍 Open source

**Merged**
- DataFusion Comet: native Iceberg MERGE execution, plus WriteDelta planning and delete-metadata correctness
- Apache Arrow ADBC: Java Flight SQL `flightsql://` URI support
- Apache DataFusion: fix for a panic on zero-field structs

**In progress**
- Native merge-on-read writes in DataFusion Comet
- Row-group-level runtime pruning for Iceberg (iceberg-rust / DataFusion Comet), up to 42x faster on one benchmark query

## 🚀 Projects

- **[redis-java](https://github.com/unikdahal/redis-java):** a Redis-compatible server in Java 25 and Netty. It covers RESP, pipelining, transactions, streams, replication, and 599+ tests.
- **[Sutine](https://sutine.com):** a full-stack e-commerce platform for the clothing label I co-own.

## 🛠️ Tech

`Java` `SQL` `TypeScript` `Python` `C++` `Rust` · `Spark` `Iceberg` `Kyuubi` `Arrow Flight SQL` `Kafka` `Redis` `PostgreSQL` `MySQL` · `Docker` `Kubernetes` `AWS`

## 🎓 Education

B.Tech in Computer Science & Engineering (Minor: Financial Economics), KIIT University · CGPA 9.12

🏆 HighRadius Fresher of the Year (HighFlyer 2025)
