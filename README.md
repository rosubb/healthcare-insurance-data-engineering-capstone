# Healthcare Insurance Data Engineering Capstone

## 📌 Overview
This project demonstrates an **end-to-end data engineering pipeline** for a healthcare insurance use case. The pipeline ingests raw data, performs cleaning and transformations using PySpark, and loads analytics-ready datasets into Amazon Redshift for reporting and insights.

---

## 🛠 Tech Stack
- **Cloud:** AWS (S3, Glue, Athena, Redshift)
- **Processing:** PySpark, AWS Glue
- **Storage:** Amazon S3 (Bronze / Silver / Gold layers)
- **Analytics:** Amazon Redshift
- **Querying:** SQL

---

## 🏗 Architecture
![Healthcare Insurance Data Engineering Architecture](architecture/architecture-diagram.png)

---

## 🔄 Data Pipeline Flow
1. Raw healthcare insurance data ingested into **S3 (Bronze layer)**
2. Data cleaned and transformed using **PySpark in AWS Glue**
3. Curated datasets stored in **S3 (Silver & Gold layers)**
4. Analytical tables loaded into **Amazon Redshift**
5. Business insights generated using SQL queries

---

## 📈 Key Outcomes
- Built scalable, cloud-native ETL pipelines  
- Applied data modeling for analytics-ready schemas  
- Enabled KPI reporting for insurance analytics  

---

## 🚀 Future Enhancements
- Add data quality checks  
- Automate pipeline orchestration  
- Integrate dashboards (Power BI / Tableau)
