<!-- ===================== HEADER ===================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,45:0f766e,100:38bdf8&height=210&section=header&text=Kushal%20Mishra&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Data%20Reliability%20Engineer%20%E2%80%94%20I%20keep%20production%20data%20platforms%20alive&descAlignY=58&descSize=16" width="100%"/>

<!-- Typing animation -->
<a href="https://orgkushal.netlify.app">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=820&height=45&lines=80%2B+Airflow+DAGs+in+production%2C+every+day;I+ship+the+tooling+for+the+failures+I+find;dbt+%C2%B7+Airflow+%C2%B7+Snowflake+%C2%B7+Python;Author+of+dbt-testpilot+%E2%80%94+live+on+PyPI" alt="typing SVG" />
</a>

<br/>

<a href="https://orgkushal.netlify.app"><img src="https://img.shields.io/badge/Portfolio-0d1117?style=for-the-badge&logo=netlify&logoColor=38bdf8" alt="Portfolio"/></a>
<a href="https://linkedin.com/in/orgkushal"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=38bdf8" alt="LinkedIn"/></a>
<a href="https://pypi.org/project/dbt-testpilot/"><img src="https://img.shields.io/badge/PyPI-0d1117?style=for-the-badge&logo=pypi&logoColor=38bdf8" alt="PyPI"/></a>
<a href="mailto:orgkushal@gmail.com"><img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=38bdf8" alt="Email"/></a>
<img src="https://komarev.com/ghpvc/?username=orgkushal&label=Profile%20views&color=38bdf8&style=for-the-badge" alt="views"/>

</div>

<!-- ===================== WHOAMI ===================== -->

### `~ whoami`

Data engineer in Pune. I keep a production data platform running — **Airflow, dbt, Snowflake, CDC replication** — and I write the tooling for the failures I find.

Most of my work is the unglamorous half of data engineering: something upstream changed, a DAG went red, and someone has to find out why before the morning reports go out. I've gotten good at the finding-out. When a fix is worth keeping, it goes into the codebase permanently rather than into a runbook as a manual step.

<div align="center">

<img src="https://img.shields.io/badge/80%2B_DAGs-daily-5eead4?style=for-the-badge&labelColor=0d1117" />&nbsp;
<img src="https://img.shields.io/badge/4–5_failures-per_week-38bdf8?style=for-the-badge&labelColor=0d1117" />&nbsp;
<img src="https://img.shields.io/badge/alert_→_green-4–6h_MTTR-a78bfa?style=for-the-badge&labelColor=0d1117" />

</div>

<!-- ===================== TECH ===================== -->

### `~ toolbox`

**In production, daily**

![SQL](https://img.shields.io/badge/Advanced_SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)

**Built with independently**

![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![Postgres](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![PyPI](https://img.shields.io/badge/PyPI_packaging-3775A9?style=for-the-badge&logo=pypi&logoColor=white)
![LangChain](https://img.shields.io/badge/LLM_APIs-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Docker](https://img.shields.io/badge/CLI_design-000000?style=for-the-badge&logo=gnubash&logoColor=white)

**Certified** &nbsp;·&nbsp; AWS ML Engineer Associate &nbsp;·&nbsp; Databricks Data Engineer Associate &nbsp;·&nbsp; SnowPro Core &nbsp;·&nbsp; HackerRank SQL (Advanced)

<!-- ===================== FEATURED ===================== -->

### `~ featured` &nbsp;🚀

<a href="https://github.com/orgkushal/dbt-testpilot">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=orgkushal&repo=dbt-testpilot&theme=transparent&hide_border=true&title_color=5eead4&icon_color=38bdf8&text_color=c9d1d9" align="right" width="400"/>
</a>

**[dbt-testpilot](https://github.com/orgkushal/dbt-testpilot)** — `pip install dbt-testpilot`

A dbt project usually has fewer tests than it should. dbt-testpilot profiles the **real data** in your warehouse and proposes the tests you're missing — then makes you approve them.

- **Heuristics before the LLM** — deterministic rules produce the obvious tests, so it works with no API key. The LLM layer adds rationale, cross-table relationships, and custom tests on top.
- **Verify before write** — every approved test runs against real data and is only written if it passes, so your suite stays green and a failing test is always a real finding.

`profile → propose → apply → dbt test`, plus `benchmark` and `drift`. DuckDB · SQLite · Postgres. Demonstrated on a ~1M-row run ending `PASS=199 ERROR=0`. *Building a Spark / Databricks adapter for v0.4.*

<br clear="right"/>

<!-- ===================== STATS ===================== -->

### `~ stats`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=orgkushal&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=5EEAD4&icon_color=38BDF8&text_color=C9D1D9" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=orgkushal&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=5EEAD4&text_color=C9D1D9" />

<br/>

<img height="165" src="https://streak-stats.demolab.com?user=orgkushal&hide_border=true&background=0D1117&stroke=38BDF8&ring=5EEAD4&fire=5EEAD4&currStreakLabel=5EEAD4&sideLabels=C9D1D9&dates=8B949E&sideNums=C9D1D9&currStreakNum=C9D1D9" />

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=orgkushal&theme=onedark&no-frame=true&no-bg=true&column=7&margin-w=6&margin-h=6" />

<!-- Contribution-snake (generated by the Action below) -->
<img src="https://raw.githubusercontent.com/orgkushal/orgkushal/output/snake.svg" alt="contribution snake" width="100%"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=orgkushal&bg_color=0d1117&color=5eead4&line=38bdf8&point=ffffff&area=true&hide_border=true&custom_title=Contribution%20activity" width="100%"/>

</div>

<!-- ===================== NOW ===================== -->

### `~ now`

- 🛠️ **Data Engineer** at **KPI Partners** — Snowflake platform for a US athletic footwear & apparel brand
- 🧪 Shipping **dbt-testpilot v0.4** (Spark / Databricks adapter)
- 📫 Reach me at **orgkushal@gmail.com**

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:38bdf8,55:0f766e,100:0d1117&height=120&section=footer" width="100%"/>

<sub>“The unglamorous half of data engineering — done well.”</sub>

</div>
