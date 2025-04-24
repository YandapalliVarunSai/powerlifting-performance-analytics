
# 🏋️‍♂️ Powerlifting Performance Analytics Using Spark & Azure

📊 **Project by:** Yandapalli Varun Sai  

## 📌 Overview
A big data pipeline that analyzes 1.5M+ global powerlifting entries to discover insights on federations, gender, equipment, and weight class performance using Apache Spark, Azure SQL, and Power BI.

---

## 🔍 Problem Statement
To explore and quantify trends in powerlifting performance across federations, gender, weight classes, and equipment types using a scalable cloud-first analytics pipeline.

---

## 🧰 Tech Stack

| Component       | Tool/Tech Used         |
|----------------|------------------------|
| Language        | Python (PySpark)        |
| Big Data Engine | Apache Spark 3.4.4      |
| Cloud Storage   | Azure Data Lake Gen2    |
| Database        | Azure SQL Database      |
| Visualization   | Power BI                |
| IDE             | Jupyter Notebook        |

---

## 🚀 Features
- End-to-end ETL using PySpark
- Data hosted on Azure Data Lake
- Cleaned, transformed, and exported to Azure SQL
- Interactive dashboards in Power BI
- Analysis across 1.5M+ lifter records

---

## 📂 Project Structure

```
├── Notebooks/                # Jupyter notebook for ETL
├── PowerBI_Dashboard/       # Final dashboard .pbix
├── Data/                    # Raw CSV data
├── Report/                  # Academic report document
├── README.md                # Project description
├── requirements.txt         # Python dependencies
```

---

## 📈 Dashboards
Interactive dashboards analyze:
- Federation-wise strength progress
- Gender & equipment-based trends
- Weight class performance profiles

---

## ⚙️ How to Run

1. **Install Dependencies**  
   Ensure Python 3.10+, Spark 3.4.4, JDK 17 are installed.  
   Install Python packages:
   ```
   pip install pandas matplotlib seaborn findspark pyspark
   ```

2. **Environment Setup**  
   Set environment variables:
   ```
   JAVA_HOME=C:\Program Files\Java\jdk-17  
   SPARK_HOME=C:\spark\spark-3.4.4-bin-hadoop3
   ```

3. **Run Notebook**  
   Launch Jupyter Notebook and execute `DI_CA_2_code.ipynb` in sequence.

---

## 🧠 Learnings
- Scalable processing using PySpark
- Integration with Azure cloud ecosystem
- Real-world sports data visualization

---

## 📬 Contact
📧 yandapallivarun@gmail.com 
🔗 [LinkedIn](https://www.linkedin.com/in/YOUR_HANDLE)
