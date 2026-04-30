# 🌐 DataSphere — E-Commerce Sales & Customer Insights Platform

DataSphere is a backend data pipeline and analytics platform built on the real-world **Olist Brazilian E-Commerce dataset**. It ingests and integrates multiple data sources, stores and manages data using **AWS S3 and Snowflake**, and delivers business insights through a lightweight dashboard powered by automated pattern analysis.

---

## 🏗️ Architecture Overview

Raw CSV Data (Olist) → Data Ingestion & Preprocessing → AWS S3 (Storage) → Snowflake (Data Warehouse) → Analysis & Pattern Detection → Dashboard Visualization

---

## 🚀 Features

- **Backend Data Pipeline** — Ingests, cleans, and integrates multiple Olist CSV datasets covering orders, customers, payments, reviews, sellers, products, and geolocation
- **AWS S3 Integration** — Connects to AWS S3 for cloud-based data storage and retrieval
- **Snowflake Data Warehouse** — Maintains a live, updatable database layer in Snowflake for scalable querying and storage
- **Automated Pattern Analysis** — Model-driven analysis identifies trends and patterns across sales, customer behavior, and seller performance
- **Insight Dashboard** — Visualizes key business metrics and analytical findings in a simple, readable format

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Language | Python |
| Data Processing | Pandas, NumPy |
| Cloud Storage | AWS S3 |
| Data Warehouse | Snowflake |
| Analysis & Visualization | Matplotlib, Scikit-learn |
| Environment | Jupyter Notebook / VS Code |

---

## 📂 Dataset

The project uses the **Olist Brazilian E-Commerce Public Dataset**, which includes the following files:

- `olist_orders_dataset.csv` — Order lifecycle and status
- `olist_customers_dataset.csv` — Customer identifiers and location
- `olist_order_items_dataset.csv` — Products and sellers per order
- `olist_order_payments_dataset.csv` — Payment methods and values
- `olist_order_reviews_dataset.csv` — Customer satisfaction scores and comments
- `olist_products_dataset.csv` — Product categories and attributes
- `olist_sellers_dataset.csv` — Seller identifiers and location
- `olist_geolocation_dataset.csv` — Geographic coordinates for customers and sellers
- `product_category_name_translation.csv` — Category name translations (Portuguese → English)

---

## 📊 Key Insights Delivered

- Sales trends across product categories and time periods
- Customer purchasing patterns and retention signals
- Seller performance and order fulfillment analysis
- Payment method distribution and order value breakdown
- Geographic distribution of customers and sellers across Brazil

---

## ⚙️ Setup & Installation

**1. Clone the repository**
```bash
git clone https://github.com/Savani-Raj/DataSphere-Project.git
cd DataSphere-Project
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Configure AWS credentials**

Set up your AWS credentials to enable S3 connectivity:
```bash
aws configure
```

**4. Configure Snowflake connection**

Update your Snowflake connection parameters (account, warehouse, database, schema) in the configuration file before running the pipeline.

**5. Run the pipeline**
```bash
python main.py
```

---

## 📁 Project Structure

```
DataSphere-Project/
│── data/                  # Raw Olist CSV datasets
│── src/                   # Pipeline and analysis source code
│── notebooks/             # Exploratory analysis notebooks
│── outputs/               # Generated visualizations and reports
│── requirements.txt       # Python dependencies
│── README.md              # Project documentation
```

---

## 📜 License

This project is licensed under the MIT License.

---

## 📧 Contact

**Raj Savani**  
GitHub: [Savani-Raj](https://github.com/Savani-Raj)  
Email: therajsavani@gmail.com
