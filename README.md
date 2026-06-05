# Gnanendra Reddy (Gnan)

8 years building data pipelines and analytics systems in healthcare and public sector.  
Targeting **ML/AI Engineer**, **Data Engineer**, and **Senior Data Analyst** roles.

CDC (2020–2026). Teladoc Health (2022–2023). Cognizant (2014–2018).  
Calgary, AB. Open to remote roles.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-gnanendrart-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/gnanendrart/)

---

## Projects

### AI / Automation

**[job-hunt-agent](https://github.com/gnanendrart/job-hunt-agent)** · [Live demo](https://job-hunt-agent.onrender.com) · React · Vite · Express · Claude API · Apify

AI-powered job search assistant with a full web UI. Upload your resume, paste a job description — it scrapes LinkedIn and Indeed via Apify, ATS-scores every listing against your resume, optimizes your bullets per role, generates cover letters, estimates salary, and manages your pipeline in a Kanban or list view. Email digest included.

---

**[n8n-job-search](https://github.com/gnanendrart/n8n-job-search)** · n8n · Claude API · Apify · Supabase · Gotenberg

Automated overnight job search pipeline. Runs at 7 AM daily on a self-hosted VPS. Scrapes LinkedIn and Indeed in parallel, deduplicates via Supabase, screens with Claude Haiku, escalates good-fit jobs (≥60/100) to Claude Sonnet for full resume tailoring, renders PDFs via Gotenberg, uploads to Google Drive, and emails a daily digest. Daily effort: under 10 minutes.

---

**[ai-data-quality-checker](https://github.com/gnanendrart/ai-data-quality-checker)** · Python · pandas · Claude API

Python CLI that runs 8 automated quality checks on any CSV — missing values, duplicates, type mismatches, outliers, string inconsistencies, date format errors — sends structured findings to Claude, and writes a ranked plain-English markdown report. Built from years of catching the same categories of errors by hand before data goes to stakeholders.

---

### Analytics

**[ab-test-saas-conversion](https://github.com/gnanendrart/ab-test-saas-conversion)** · Python · pandas · scipy · statsmodels

End-to-end A/B test on a SaaS learning platform's pre-enrollment screener. Covers experiment design, sanity checks, z-test, and confidence intervals. Gross conversion dropped 2.06pp (significant); net conversion held flat (not significant). Recommendation: do not launch.

---

**[ipl-cricket-analytics](https://github.com/gnanendrart/ipl-cricket-analytics)** · PostgreSQL · psql · VS Code SQLTools

SQL analytics on 16 years of IPL match data. 1,095 matches. 260,920 deliveries. 15 queries covering window functions, CTEs, multi-table joins, conditional aggregation, and HAVING filters — toss impact on match result, venue scoring environments, best economy rates with minimum-over thresholds, and batting averages filtered to finals only.

---

## Professional Background

**CDC — Senior Data Analyst (Jun 2023–Feb 2026):** Engineered Python and SQL validation checks across the Influenza Vaccination Pathway that caught 80% of data-quality issues before federal submission, cutting reporting errors 15%. Built PySpark pipelines on the One CDC Data Platform processing 3M+ records weekly across 6 facility types. Reconciled legacy SAS and 1CDP systems across 1.5M+ records, taking weekly rate-comparison errors from 10–15% down to zero. Delivered vaccination coverage reporting for 15,000+ sites used in national CDC reporting.

**Teladoc Health — Data Operations Analyst II (Oct 2022–May 2023):** Reduced billing data loss from 2.3% to 0.06% across 5 enterprise partnerships covering 50,000+ members by tracing root causes and redesigning the cross-team process. Built SQL-driven automation that cut manual data operations 30%.

**CDC — Data Analyst (Dec 2020–Sep 2022):** Led analytics for national COVID-19 surveillance across 16,000+ long-term care facilities. Conducted statistical analysis on 1M+ records including observed-to-expected ratio modeling against vaccine effectiveness assumptions. Produced 3 weekly reports used in White House and inter-agency pandemic response planning. Cut reporting turnaround by 4 hours through data quality framework improvements.

**Cognizant — Programmer Analyst (Aug 2014–May 2018):** Reduced delivery errors 15% for UPS via SQL-based data integrity checks. Improved portal engagement 24% for HealthNet and Cigna. Built Tableau dashboards for route monitoring, improving route optimization efficiency 10%.

---

## Stack

| Area | Tools |
|---|---|
| LLM APIs | Anthropic Claude (Haiku, Sonnet) |
| Automation | n8n |
| Languages | SQL · Python · PySpark · R |
| Databases | PostgreSQL · Snowflake · Redshift · SQL Server |
| Cloud | AWS (S3, Glue, Lambda) · Azure Data Lake |
| BI | Power BI · Tableau · Metabase |
| Other | SAS · Docker · Git |

---

## Education

M.S. Information Management — University of Illinois Urbana-Champaign (2020)  
B.E. Electronics and Communication — Sathyabama University (2014)
