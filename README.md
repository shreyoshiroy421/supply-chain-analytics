# Supply Chain Intelligence Pipeline

**View my interactive Dashboard in Quadratic**: https://app.quadratichq.com/file/0588de0e-a5a6-4122-8c50-11d90b2dfca0

# Overview
This project automates the extraction of supply chain data from emails and converts it into actionable insights. It demonstrates a modern "AI-first" mindset for data engineering and analysis.

# Key Features:

-**Automated Data Ingestion:** Uses n8n to monitor emails, extract CSVs, and load them into a PostgreSQL database.
-**AI-Native Analysis:** Uses Quadratic (AI Spreadsheet) to perform prompt-based analysis, allowing non-technical stakeholders to ask questions like "Show me top 5 customers in India by revenue."

# Tech Stack
- **Automation (n8n):** Monitored Gmail for CSV attachments and handled data transformation.
- **Database (Supabase/PostgreSQL):** Designed a Star Schema with Fact (`fact_aggregate`, `fact_order_line`) and Dimension tables.
- **Analytics (Quadratic):** Used an AI-powered spreadsheet to pull SQL data and perform Python-based analysis.





