# Gnanendra Reddy (Gnan)

Data analyst with 8 years in healthcare and public sector. Building LLM-powered automation and SQL analytics pipelines.

CDC (2020–2026). Teladoc Health (2022–2023). Cognizant (2014–2018).  
Calgary, AB. Open to remote roles.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-gnanendrart-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/gnanendrart/)

---

## Projects

### [n8n-job-search](https://github.com/gnanendrart/n8n-job-search) &nbsp;·&nbsp; n8n · Claude API · Apify · React · Supabase · Gotenberg

An AI-powered job search pipeline built in two phases.

**Phase 1 — Manual morning tool.** React + Express app. Scrapes LinkedIn and Indeed via Apify, scores each job against your resume using Claude, optimizes your bullets per job, generates cover letters, and manages your pipeline in a Kanban or list view.

**Phase 2 — Automated overnight pipeline.** Runs at 7 AM via n8n on a self-hosted VPS. Scrapes both sources in parallel, drops jobs already processed (Supabase deduplication), scores each new job with Claude Haiku (fast, cheap), passes good-fit jobs (≥60/100) to Claude Sonnet for full resume tailoring, renders PDFs via self-hosted Gotenberg, uploads to Google Drive, and emails a summary. Daily effort on your end: under 10 minutes.

The two-tier AI architecture — Haiku screening before Sonnet tailoring — matters both for cost and reliability. A poor-fit job sent directly to Sonnet sometimes returns a plain-text explanation instead of JSON, crashing the pipeline. The Haiku filter eliminates that failure mode for fractions of a cent per job.

---

### [ipl-cricket-analytics](https://github.com/gnanendrart/ipl-cricket-analytics) &nbsp;·&nbsp; PostgreSQL · psql · VS Code SQLTools

SQL analytics on 16 years of IPL match data. 1,095 matches. 260,920 deliveries.

15 queries covering: window functions, CTEs, multi-table joins, conditional aggregation, and HAVING filters. Topics include toss impact on match result, venue scoring environments, best economy rates with minimum-over thresholds, and batting averages filtered to finals only.

---

## Professional Background

**CDC (2020–2026):** Owned the Influenza Vaccination Pathway for 15K+ healthcare facilities used in national CDC reporting. Built PySpark repositories on the 1CDP platform processing 3M+ records weekly. Led cross-system reconciliation between legacy SAS and 1CDP, aligning facility and org ID mismatches across 16K+ records. Cut COVID-19 Power BI report delivery from 6 hours to 2 via Azure Data Lake automation.

**Teladoc Health (2022–2023):** Reduced billing data loss from 2.3% to 0.06% through cross-team process redesign. Managed 5 healthcare data partnerships covering 50K+ members at 95%+ accuracy from go-live.

**Cognizant (2014–2018):** Data and analytics work for UPS, Cigna, and HealthNet across claims processing, portal UX, and route optimization.

---

## Stack

| Area | Tools |
|---|---|
| Languages | SQL · Python · PySpark · R |
| Databases | PostgreSQL · Snowflake · Redshift · SQL Server |
| Cloud | AWS (S3, Glue, Lambda) · Azure Data Lake |
| BI | Power BI · Tableau · Metabase |
| LLM APIs | Anthropic Claude (Haiku, Sonnet) |
| Automation | n8n |
| Other | SAS · Docker · Git |

---

## Education

M.S. Information Management — University of Illinois Urbana-Champaign (2020)  
B.E. Electronics and Communication — Sathyabama University (2014)
