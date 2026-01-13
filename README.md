# Supply Chain Intelligence Pipeline

# Overview
This project automates the extraction of supply chain data from emails and converts it into actionable insights. It demonstrates a modern "AI-first" mindset for data engineering and analysis.

# Tech Stack
- **Automation (n8n):** Monitored Gmail for CSV attachments and handled data transformation.
- **Database (Supabase/PostgreSQL):** Designed a Star Schema with Fact (`fact_aggregate`, `fact_order_line`) and Dimension tables.
- **Analytics (Quadratic):** Used an AI-powered spreadsheet to pull SQL data and perform Python-based analysis.

**View my interactive Dashboard in Quadratic**: https://app.quadratichq.com/file/0588de0e-a5a6-4122-8c50-11d90b2dfca0

# Project Structure

  The n8n automation logic.
- `schema.sql`: PostgreSQL table definitions.
- `analysis.py`: Python snippets used for KPI calculations.In this project, I have solved some supply chain issues using Quadratic (AI-powered spreadsheet) &amp; N8N (AI workflow automation tool).

