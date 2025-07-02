# NYC Yellow Taxi – Azure Data Engineering Pipeline 🚖

## 📌 Description
End‑to‑end data pipeline using **Azure Data Factory, ADLS Gen2, Databricks (PySpark), and Delta Lake** to process and analyze NYC Yellow Taxi trip data.

## ✅ Pipeline Stages
| Stage  | Description                             |
|--------|-----------------------------------------|
| Bronze | Raw Parquet data ingested to ADLS       |
| Silver | PySpark transformation & cleaning       |
| Gold   | Stored in Delta format with external table |

## 📊 Technologies Used
- Azure Data Factory
- Azure Data Lake Storage Gen2
- Azure Databricks (PySpark)
- Delta Lake
- Hive Metastore

## 📂 Folder Details
| Folder       | Purpose                                      |
|--------------|----------------------------------------------|
| `notebooks/` | Databricks notebooks for each pipeline stage |
| `scripts/`   | Schema file + external‑table SQL             |

## 🧪 Notebooks

- [Silver Layer Notebook](notebooks/silver.ipynb)
- [Gold Layer Notebook](notebooks/gold.ipynb)


## ✨ Output Table
- **Table:** `gold.trip_zone`
- **Format:** Delta Lake  
- **Mode:** External table (ADLS path)

## 🧑‍💻 Author
**Bishwajit Singh**  
_Data Engineer | Azure & Databricks Enthusiast_  
[LinkedIn](www.linkedin.com/in/bishwajitsingh) • [GitHub](https://github.com/bishwajitSingh123)

## 📄 License
MIT License
