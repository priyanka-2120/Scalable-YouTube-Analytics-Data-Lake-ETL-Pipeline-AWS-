# 🚀 Scalable YouTube Analytics Data Lake & ETL Pipeline (AWS)

## 📌 Overview
Built an end-to-end Data Engineering pipeline to process and analyze large-scale YouTube trending data. The system ingests raw structured and semi-structured data, transforms it using ETL workflows, and stores it in a scalable AWS data lake for analytics and reporting.

---

## 🎯 Key Features
- Automated **data ingestion** from multiple sources  
- End-to-end **ETL pipeline** for data cleaning and transformation  
- Scalable **data lake architecture using AWS S3**  
- Serverless data processing using **AWS Glue & Lambda**  
- Fast querying using **AWS Athena**  
- Interactive dashboards using **Amazon QuickSight**

---

## 🏗️ Architecture
<img src="architecture.jpeg" alt="Architecture Diagram" width="800"/>

---

## ⚙️ Tech Stack
- **Cloud:** AWS (S3, Glue, Lambda, Athena, IAM, QuickSight)  
- **Languages:** Python, SQL  
- **Data Processing:** Pandas  
- **Storage:** AWS S3 (Data Lake)  

---

## 🔄 Data Pipeline Workflow
1. Ingest raw data (CSV & JSON) from external sources  
2. Store raw data in AWS S3 (data lake)  
3. Transform and clean data using AWS Glue  
4. Automate processing using AWS Lambda  
5. Query processed data using AWS Athena  
6. Visualize insights using Amazon QuickSight  

---

## 📊 Dataset
- Source: Kaggle YouTube Trending Dataset  
- Size: ~500K+ records across multiple regions  
- Data includes: views, likes, comments, category, timestamps  

🔗 https://www.kaggle.com/datasets/datasnaek/youtube-new

---

## 📈 Key Outcomes
- Improved data usability through structured ETL workflows  
- Enabled faster querying using serverless architecture  
- Built a scalable pipeline capable of handling large datasets  

---


## 📌 Future Improvements
- Integrate real-time streaming using Kafka  
- Add data validation and monitoring  
- Optimize query performance further  
