# E-Commerce Real-Time Analytics & Recommendations Pipeline

End-to-end data engineering pipeline for e-commerce analytics and ML-based recommendations.

## 🏗️ Architecture

Events → Kinesis → Lambda → S3 → Spark → Snowflake → dbt → ML → FastAPI → Dashboard

## Data Ingestion (COMPLETE)

- AWS infrastructure setup with IAM
- S3 buckets for raw/processed data
- Kinesis stream for real-time events
- Lambda functions for event validation
- 100+ test events generated and flowing
- All data validated and stored

## 📊 Project Status

Week 1/12 Complete ✅
- Data ingestion: LIVE ✅
- 100+ events flowing: ACTIVE ✅
- Infrastructure: PRODUCTION-READY ✅

## 🛠️ Tech Stack

- AWS (S3, Lambda, Kinesis, CloudWatch)
- Python 3.11
- Apache Spark (Week 2-3 ✅)
- Databricks (Week 2-3 ✅)
- Snowflake (coming Week 4-5)
- dbt (coming Week 4-5)
- ML Models (coming Week 6-7)

## 📅 Timeline

- Week 1-2: AWS Data Ingestion ✅ COMPLETE
- Week 3-4: Spark + Airflow Processing ✅ COMPLETE (Databricks)
- Week 5-6: Snowflake + dbt Warehouse ⏳ NEXT
- Week 7-8: ML Models (3 models)
- Week 9: FastAPI REST API
- Week 10: Streamlit Dashboard
- Week 11-12: Production & Optimization

## 📊 Current Status

**Week 2-3 Completion:**
- ✅ Databricks ETL pipeline deployed
- ✅ 500 clean events processed
- ✅ 51 unique users analyzed
- ✅ 26 unique products analyzed
- ✅ Delta Lake enabled
- ✅ Production-ready

## 👨‍💻 Author

Chirag Tiwari
- GitHub: [@Chiku-projects](https://github.com/Chiku-projects)
- Email: ct880717@gmail.com
- Location: Kolkata, West Bengal

## 📄 License

MIT License