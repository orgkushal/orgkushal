## Kushal Mishra

Data engineer in Pune. I keep a production data platform running — Airflow, dbt, Snowflake, CDC replication — and I write the tooling for the failures I find.

Most of my work is the unglamorous half of data engineering: something upstream changed, a DAG went red, and someone has to find out why before the morning reports go out. I've gotten good at the finding-out. When a fix is worth keeping, it goes into the codebase permanently rather than into a runbook as a manual step.

```
80+ DAGs, daily    4–5 failures / week    4–6 h report → green
```

---

### 🔧 [dbt-testpilot](https://github.com/orgkushal/dbt-testpilot)

A dbt project usually has fewer tests than it should, and writing them by hand never reaches the top of the sprint. dbt-testpilot profiles the actual data in your warehouse and proposes the tests you're missing — then makes you approve them.

```bash
pip install dbt-testpilot
```

Two decisions that matter:

- **Heuristics run before the LLM.** Deterministic rules produce the obvious tests, so the tool works with no API key at all. The LLM layer adds rationale, cross-table relationships, and custom tests on top.
- **Verify before write.** Every approved test is executed against real data and only written if it passes. Your suite stays green, and a failing test always means a real data-quality finding — not a bad guess by a model.

`profile → propose → apply → dbt test`, plus `benchmark` (compares LLM providers by would-fail rate) and `drift` (re-checks written tests against current data and schema, non-zero exit for CI).

DuckDB · SQLite · Postgres. Demonstrated on a ~1M-row jaffle_shop across all three, ending `PASS=199 ERROR=0`.

Currently building a Spark / Databricks adapter for v0.4.

---

### Currently

- **Data Engineer** at KPI Partners, on a Snowflake platform for a US athletic footwear and apparel brand
- Working on dbt-testpilot v0.4 — Spark / Databricks adapter
- Reachable at orgkushal@gmail.com

### Toolbox

**In production, daily** — Advanced SQL · Airflow · dbt · Snowflake · HVR (CDC) · AWS S3 · AWS Secrets Manager · Python

**Built with independently** — Python packaging & PyPI · DuckDB · SQLite · Postgres · data profiling · LLM APIs · CLI design · uv · hatchling

**Certified** — AWS ML Engineer Associate · Databricks Data Engineer Associate · SnowPro Core · HackerRank SQL (Advanced)

---

[Website](https://orgkushal.netlify.app) · [LinkedIn](https://linkedin.com/in/orgkushal) · [PyPI](https://pypi.org/project/dbt-testpilot/)
