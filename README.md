# 🏡 Redfin Data Pipeline: ETL with AWS EMR & PySpark

## 🚀 Overview

This project demonstrates how to **Extract, Transform, and Load (ETL)** real estate data from **Redfin** using a scalable data pipeline powered by **AWS EMR (Elastic MapReduce)**, **Apache Spark**, **PySpark**, and **Amazon S3**.

🔧 Whether you’re handling millions of rows of real estate listings or just learning how to use big data tools in the cloud, this project is a practical guide to modern data engineering.

---

## 🛠️ Tech Stack

- **AWS EMR** — Managed Hadoop framework to run Spark and PySpark jobs at scale  
- **Apache Spark** — Fast cluster computing system  
- **PySpark** — Python API for Spark to handle big data processing  
- **Jupyter Notebook** — Interactive data exploration and transformation  
- **Amazon S3** — Storage for both raw and transformed datasets  
- **Redfin** — Source of real estate data  

---

## 📊 ETL Workflow

1. **Extract**  
   Pull Redfin data into the cloud environment.
   <img width="1440" alt="Screenshot 2025-05-12 at 19 39 30" src="https://github.com/user-attachments/assets/b15f5588-99c7-4511-ae5c-2dc2b937a691" />

2. **Transform**  
   ```python
   # Sample PySpark transformation code
   from pyspark.sql.functions import col
   <img width="1440" alt="Screenshot 2025-05-12 at 19 40 12" src="https://github.com/user-attachments/assets/07b668aa-45b2-4e1c-ab85-5b88e60a67aa" />

   
3. **Load**
   Store the clean and structured data in a reliable, scalable storage format in Amazon S3.
   df_cleaned.write.mode("overwrite").parquet("s3://redfin-transform-zonee-yml/processed/redfin/")
   <img width="1440" alt="Screenshot 2025-05-12 at 19 40 53" src="https://github.com/user-attachments/assets/9999c4c3-f973-4096-b2b1-8f8c2739809e" />

5. **Relevant ScreeenShort**
   
<img width="1440" alt="Screenshot 2025-05-12 at 19 42 23" src="https://github.com/user-attachments/assets/fdde7954-7573-4a66-96b8-c27e79f63491" />
<img width="1440" alt="Screenshot 2025-05-12 at 19 42 41" src="https://github.com/user-attachments/assets/3de8ccbf-0a85-45de-b7ae-c02385fb4bc0" />
<img width="1440" alt="Screenshot 2025-05-12 at 19 43 01" src="https://github.com/user-attachments/assets/1ae9d065-814e-4d27-a7e0-836a8f95c731" />
<img width="1440" alt="Screenshot 2025-05-12 at 19 43 15" src="https://github.com/user-attachments/assets/08c86412-89be-4c16-a317-0a34bd63379b" />
<img width="1440" alt="Screenshot 2025-05-12 at 19 43 24" src="https://github.com/user-attachments/assets/e7e3ec52-72e4-4d04-8bdf-6734f0166e6b" />
<img width="1440" alt="Screenshot 2025-05-12 at 19 43 35" src="https://github.com/user-attachments/assets/f8ccba72-cd92-4548-bc69-2a2a6734170c" />
<img width="1440" alt="Screenshot 2025-05-12 at 19 43 59" src="https://github.com/user-attachments/assets/6ddbd63f-f153-43df-a67a-a28a58489ca2" />
<img width="1440" alt="Screenshot 2025-05-12 at 19 44 10" src="https://github.com/user-attachments/assets/17dd26e2-9901-47f2-9343-3306149ae482" />

   
🧠 **Learn More**
	•	📚 AWS EMR Documentation
	•	🔥 Apache Spark
	•	🏘️ Redfin Data Center
