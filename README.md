# Matt Werth

Senior/Staff backend and full-stack engineer. 20+ years building cloud
platforms (AWS/GCP), multi-tenant SaaS and geospatial systems. These days
I build applied-AI systems: agentic tool-use loops, RAG on pgvector,
text-to-SQL, structured outputs, and guardrails enforced in code, with an
eval harness written before the feature it scores.

**Python · FastAPI · Node.js · TypeScript · NestJS · React · Postgres · pgvector · PostGIS · Geospatial · Kafka · RabbitMQ · Event-driven microservices · Anthropic SDK · AWS/GCP · Kubernetes · Docker**

## Applied AI

| project | what it shows |
|---|---|
| [**text-to-sql-analyst**](https://github.com/mattwerthva/text-to-sql-analyst) | Ask a property-maintenance database questions in plain English. Claude writes the SQL as a forced tool call, two independent guardrails gate execution (static check plus a read-only transaction), results stream back over SSE, and a golden-query eval measures accuracy. Runnable locally on fictitious data. |
| [**job_copilot**](https://github.com/mattwerthva/job_copilot) | An agentic assistant over my real job-search pipeline, in daily use. A hand-written tool-use loop — iteration cap, per-run tool allowlist, every step traced and replayable — whose write tools only write proposals a person accepts field by field. RAG over meeting transcripts and JDs with Voyage embeddings in pgvector, read-only Granola/Gmail ingest, and a Postgres-backed worker with backoff and a daily spend cap. Every LLM feature shipped with a dated measurement against the real corpus; it runs on my own data, so a fresh clone starts empty — happy to walk through it live. |


## Contact

[LinkedIn](https://www.linkedin.com/in/mattwerthva)
