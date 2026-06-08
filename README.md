# I am Olivier :wave:

Most software and data platform failures come from hidden constraints, wrong assumptions and unintended trade-offs. We're now seeing AI scaling those risks faster.

I help leadership make the right data platform and backend decisions before architecture becomes expensive, margins erode and systems outgrow their original design constraints.

I surface hidden constraints, clarify trade-offs, and define technically sound patterns that engineering teams can execute.

I have 8+ years of experience across startups and high-throughput engineering environments. I currently work as a Foundational Data Platform / Backend Engineer across OLTP/OLAP systems, data flows and cloud infrastructure where reliability, latency, cost, clarity, and ownership heavily matter.

Workshops & technical conferences:  
https://www.linkedin.com/in/olivierbenard/
  
More on how I think about architecture and decision-making:  
https://cloudframework.eu

---

#### Infrastructure & Platform Foundations

- **Terraform Modules for Cloud Platforms**  
  Reusable, versioned Terraform modules designed to make infrastructure ownership explicit and predictable.  
  https://github.com/olivierbenard/gcp-terraform-modules

#### Decision-Driven Cloud Infrastructure

- **Colocated Infrastructure & Deployment Template**  
  A reference structure (re-using the aforementioned exposed modules) showing how to co-locate infrastructure with services using Terraform, Terragrunt, and YAML — optimized for clarity, ownership, and low cognitive load.  
  https://github.com/olivierbenard/infra-colocation-template

#### Data Platform, System Design & Selected Patterns

- **Analytics Batch Pipeline Reference (Python + dbt + Airflow)**  
  Demonstrates how analytical workloads evolve from ad-hoc scripts into production-grade data platform pipelines.  
  Focuses on layered modeling (raw → staging → marts), reproducibility, and trade-offs across ingestion boundaries, deduplication strategies, and state management (append-only vs constrained raw layers, hash vs business keys, MERGE vs full refresh).  
  https://github.com/olivierbenard/analytics-batch-pipeline-reference

- **CDC Data Platform Reference (DuckDB + Airflow)**  
  Explores correctness in event-driven data systems, including append-only ingestion, ordering guarantees, idempotency, and privacy boundaries (raw → staging_pii → staging → marts).  
  Emphasizes auditability and late-binding transformations in CDC pipelines.  
  https://github.com/olivierbenard/cdc-data-platform-reference

- **CSV Ingestion Reference (TypeScript + Node.js)**  
  A small TypeScript reference project for backend/runtime patterns through a familiar data-ingestion use case.  
  Reads CSV data, enriches records with ingestion metadata, applies deterministic transformations, and writes JSON output through a CLI and Dockerized runtime.  
  Focuses on TypeScript fundamentals for platform work: typed contracts, runtime configuration, dependency injection, structured logging, testing with Vitest, linting, Docker/Compose execution, and the distinction between build-time and runtime dependencies.  
  https://github.com/olivierbenard/csv-ingestion-ts

- **Postgres Workload Reference**  
  Exploring PostgreSQL as a multi-workload platform (OLTP, time-series, vector, document).  
  Focuses: how access patterns drive indexing strategy, cost and system boundaries.  
  https://github.com/olivierbenard/postgres-workload-lab
