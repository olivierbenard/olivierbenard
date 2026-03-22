# Hello, I am Olivier :wave:

I am a Data Platform Architect with a focus on Cloud/Data Platforms and a Software/Data Engineering background. 
  
I lead architectural decisions that shape systems over the long term.  
My work helps prevent technical choices that quietly turn into long-term cost, ownership or scalability constraints.  
  
I contribute to internal platforms, infrastructure tooling and data-centric systems.  
Occasionally, I share practical lessons through talks and workshops at technical conferences and industry meetups in Germany.  
  
More on how I think about architecture and decision-making:
* https://cloudframework.de

---

### Selected Work

#### Infrastructure & Platform Foundations
- **Terraform Modules for Cloud Platforms**  
  Reusable, versioned Terraform modules designed to make infrastructure ownership explicit and predictable.  
  https://github.com/olivierbenard/gcp-terraform-modules

#### Decision-Driven Cloud Infrastructure
- **Colocated Infrastructure & Deployment Template**  
  A reference structure showing how to co-locate infrastructure with services using Terraform, Terragrunt, and YAML — optimized for clarity, ownership, and low cognitive load.  
  https://github.com/olivierbenard/infra-colocation-template

#### Data Platform & Analytics Engineering

- **Analytics Batch Pipeline Reference (Python → dbt → Airflow)**  
  Demonstrates how analytical workloads evolve from ad-hoc scripts into production-grade data platform pipelines.  
  Focuses on layered modeling (raw → staging → marts), reproducibility, and trade-offs across ingestion boundaries, deduplication strategies, and state management (append-only vs constrained raw layers, hash vs business keys, MERGE vs full refresh).  
  https://github.com/olivierbenard/analytics-batch-pipeline-reference

- **CDC Data Platform Reference (DuckDB + Airflow)**  
  Explores correctness in event-driven data systems, including append-only ingestion, ordering guarantees, idempotency, and privacy boundaries.  
  Emphasizes auditability and late-binding transformations in CDC pipelines.  
  https://github.com/olivierbenard/cdc-data-platform-reference
