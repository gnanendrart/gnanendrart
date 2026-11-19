# Gnanendra Reddy (Gnan)

Data analyst who ships AI tools. 8+ years finding and fixing data problems before they reach stakeholders, most of it on national public health data at CDC.  
Open to **AI analyst**, **analytics engineering** and **senior data analyst** roles, remote or hybrid across Canada.

CDC (2020 to 2026). Teladoc Health (2022 to 2023). Cognizant (2014 to 2018).  
Calgary, AB. Canadian permanent resident.

[![Portfolio](https://img.shields.io/badge/Portfolio-gnanendra--portfolio-1F4FD8?style=flat)](https://gnanendra-portfolio-xi.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-gnanendrart-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/gnanendrart/)

---

## Projects

### AI tools

**[crickql](https://github.com/gnanendrart/crickql)** · Python · Claude API · dbt · PostgreSQL · Snowflake · S3 · Airflow · FastAPI · Docker

Ask an IPL cricket question in plain English and get the answer with the SQL that produced it. Cricsheet ball-by-ball data (1,243 matches, 295,732 deliveries) lands in S3, Postgres and Snowflake, is modeled and tested in dbt (49 data tests) and refreshed weekly by Airflow. Claude writes the SQL. A parser check, a read-only database role and a 10-second timeout keep it read-only. It scores 11 of 12 on a holdout set I wrote blind to the agent. The first eval scored 46.7% because my scorer rejected correct answers that came with extra rows; the README walks through the fix. Retrieval over the Laws of Cricket is next.

---

**[job-hunt-agent](https://github.com/gnanendrart/job-hunt-agent)** · [Live demo](https://job-hunt-agent.onrender.com) · React · Vite · Express · Claude API · Apify

AI-powered job search assistant with a full web UI. Upload a resume and paste a job description. It scrapes LinkedIn and Indeed via Apify, ATS-scores every listing against the resume, rewrites bullets for the role, drafts a cover letter, estimates salary and tracks the pipeline in a Kanban or list view. Email digest included.

---

**[n8n-job-search](https://github.com/gnanendrart/n8n-job-search)** · n8n · Claude API · Apify · Supabase · Gotenberg

Automated overnight job search pipeline on a self-hosted VPS, running at 7 AM daily. Scrapes LinkedIn and Indeed in parallel, deduplicates via Supabase, screens with Claude Haiku, escalates good-fit jobs (60/100 and up) to Claude Sonnet for full resume tailoring, renders PDFs via Gotenberg, uploads to Google Drive and emails a daily digest. Daily effort: under 10 minutes.

---

**[ai-data-quality-checker](https://github.com/gnanendrart/ai-data-quality-checker)** · Python · pandas · Claude API

Python CLI that profiles any CSV across 8 checks (missing values, duplicate rows, data type issues, cardinality, outliers, string consistency, date formats and summary statistics), sends the findings to Claude and writes a plain-English report ranked by severity. Built from years of catching the same categories of errors by hand before data reached stakeholders.

---

### Data engineering and analytics

**[ipl-dbt](https://github.com/gnanendrart/ipl-dbt)** · dbt Core · Snowflake · GitHub Actions

dbt project on Snowflake over 1,095 IPL matches: 2 staging views, 4 mart tables (match summary, player batting, team season, venue), 19 tests (unique, not_null, accepted_values, relationships and a custom singular test) and CI on every pull request. A test limiting innings to 1 and 2 failed on real data. The failures were legitimate super-over innings, so the rule changed instead of the data.

---

**[ab-test-saas-conversion](https://github.com/gnanendrart/ab-test-saas-conversion)** · Python · pandas · scipy · statsmodels

End-to-end A/B test on a SaaS learning platform's pre-enrollment screener. Covers experiment design, sanity checks, z-test and confidence intervals. Gross conversion dropped 2.06pp (significant); net conversion held flat (not significant). Recommendation: do not launch.

---

**[ipl-cricket-analytics](https://github.com/gnanendrart/ipl-cricket-analytics)** · PostgreSQL · psql · VS Code SQLTools

SQL analytics on 16 years of IPL match data: 1,095 matches, 260,920 deliveries. 15 queries covering window functions, CTEs, multi-table joins, conditional aggregation and HAVING filters: toss impact on results, venue scoring, best economy rates with minimum-over thresholds and batting averages in finals.

---

## Professional Background

**CDC, Senior Data Analyst, Contractor (Jun 2023 to Feb 2026):** Reconciled 1.5M+ records between legacy SAS pipelines and the One CDC Data Platform (1CDP), eliminating facility and org ID mismatches behind a 10 to 15% weekly error rate. Built Python and SQL validation checks on the Influenza Vaccination Pathway that caught 80% of the recurring data-quality issue types before federal submission, cutting reporting errors and rework 15%. Built PySpark pipelines on 1CDP processing 3M+ records weekly across 6 facility types. Coauthor on 2 CDC MMWR reports (Nov 2023) on health care personnel vaccination coverage across 5,200+ hospitals.

**Teladoc Health, Data Operations Analyst II, Contractor (Oct 2022 to May 2023):** Reduced billing data loss from 2.3% to 0.06% across 5 enterprise partnerships covering 50,000+ members by tracing a migration that left billing codes behind. Automated inbound file management for 4 enterprise clients: SFTP to S3, Python response files, encryption and outbound delivery in one Jenkins job, cutting manual effort 30%.

**CDC, Data Analyst, Contractor (Dec 2020 to Sep 2022):** COVID-19 surveillance analytics in SAS and SQL across 16,000+ long-term care facilities, delivering 3 weekly reports to White House and federal leadership. Analyzed breakthrough cases across a vaccinated population of 1M+, comparing observed to expected cases against a 70% vaccine effectiveness benchmark. Cut reporting turnaround from 5 hours to 1 hour by redesigning the data quality framework.

**Cognizant, Programmer Analyst (Aug 2014 to May 2018):** Clients UPS, Cigna and HealthNet. Cut claims-processing defect-fix costs 18% by catching defects in the requirements phase. Reduced UPS delivery errors 15% with SQL data integrity and validation checks.

---

## Stack

| Area | Tools |
|---|---|
| LLM APIs | Anthropic Claude (Haiku, Sonnet) |
| Data engineering | dbt · Airflow · Jenkins |
| Automation | n8n |
| Languages | SQL · Python · PySpark · R |
| Databases | PostgreSQL · Snowflake · Redshift · SQL Server |
| Cloud | AWS (S3, Glue, Lambda) · Azure Data Lake · Databricks |
| BI | Power BI · Tableau · Metabase |
| APIs and delivery | FastAPI · Docker · GitHub Actions |
| Other | SAS · Git |

---

## Education

M.S. Information Management, University of Illinois Urbana-Champaign (2020)  
B.E. Electronics and Communication, Sathyabama University (2014)
