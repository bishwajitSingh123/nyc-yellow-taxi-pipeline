# 🚖 NYC Yellow Taxi Trip Data Pipeline (Azure + Databricks)

This project demonstrates a complete data engineering pipeline using Azure Data Lake Storage and Databricks.  
It processes NYC Yellow Taxi data through Bronze → Silver → Gold layers using Delta Lake.

---

## 🛠️ Tools & Tech Used
- Azure Data Lake Storage (Gen2)
- Azure Data Factory
- Azure Databricks (PySpark)
- Delta Lake
- GitHub

---

## 📂 Data Lakehouse Structure

- **Bronze**: Raw ingested data (from ADF)
- **Silver**: Cleaned + transformed data (with schema applied)
- **Gold**: Aggregated/report-ready data

---

## 📒 Notebooks

- [🔹 Silver Layer](notebooks/silver.ipynb)
- [🥇 Gold Layer](notebooks/gold.ipynb)

---

## 📊 Sample Transformations in Gold
- Total fare per payment type
- Avg trip distance by pickup zone
- Tip % analysis

---

## 🧠 Learnings
- Data lake architecture (Bronze → Silver → Gold)
- PySpark transformations
- Managing large-scale data with Delta Lake
- Working with Azure cloud components end-to-end

---

## 🙏 Author

**Bishwajit Singh**  
Aspiring Data Engineer | Azure + Spark Enthusiast  
[GitHub](https://github.com/bishwajitSingh123) | [LinkedIn](https://www.linkedin.com/in/bishwajitSingh123)

---

## 📌 License
This project is licensed under the [MIT License](LICENSE).
