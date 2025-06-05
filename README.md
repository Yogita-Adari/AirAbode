# ✈️ Airabode: AviationStack ETL Pipeline

Airabode is a Python-based ETL pipeline that ingests flight data from the [AviationStack API](https://aviationstack.com/), performs data cleaning and transformation, and loads it into a PostgreSQL database for further analysis.

---

## 📌 Features

- 🔗 Extracts real-time flight data from the AviationStack API
- 🧹 Transforms and cleans data using `pandas`
- 🗃 Loads structured data into a PostgreSQL table (`flights`)
- ✅ Includes basic data validation and schema enforcement
- ♻️ Designed to be integrated with scheduling tools like `cron` or `Airflow`

---

## 🔧 Tech Stack

| Component     | Technology              |
|---------------|--------------------------|
| Language      | Python 3.x               |
| ETL Framework | Custom Python Script     |
| API Source    | AviationStack            |
| DB            | PostgreSQL               |
| Dependencies  | `requests`, `pandas`, `psycopg2` |

---

## 📁 File Structure

```bash
airabode/
├── etl_script.py       # Main ETL pipeline
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
└── .env (optional)     # For storing your API key securely
