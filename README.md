# 👟 Adidas Sales Analytics & Interactive Power BI Dashboard

## 📌 Project Overview
An end-to-end data analysis and visualization project analyzing **3.1M+ Adidas sales transactions** ($190.4M Net Sales). The project demonstrates large-scale data processing, Star Schema relational modeling from a Microsoft Access database, and modern container-based UI dashboard design in Power BI.

---

## 📸 Dashboard Preview
(images/dashboard_preview1.png)

---

## 🗄️ Dataset & Database Source
Due to file size constraints (+400MB raw database), the full Microsoft Access database (`SalesDB.accdb`) and `.pbix` source files are hosted on Kaggle:
👉 **[View & Download Dataset on Kaggle](https://www.kaggle.com/datasets/yousseflfakir/adidas-sales-analytics-3-1m-records-and-power-bi)**

---

## 🎯 Key Metrics & Business Performance (KPIs)
* **Gross Sales:** $217.6M
* **Net Sales:** $190.4M
* **Total Discounts Given:** $27.2M
* **Total Units Sold:** 6.0M items

---

## 📊 Key Features & Visual Insights
1. **Geospatial Mapping:** Regional distribution tracking sales across major cities (*Cairo, Alexandria, Giza, Luxor, Port Said, Sharm El Sheikh, Ismailia*).
2. **Product Category Performance:** Revenue breakdown highlighting top-performing categories (*Bikes, Clothing, Accessories, Components*).
3. **Multi-Year Flow Analysis:** Flow/Ribbon chart tracking revenue shifts by city over time (*2016 – 2018*).
4. **Monthly Seasonality:** Line trend analysis showcasing monthly sales fluctuations and demand patterns throughout the year.

---

## 🏗️ Data Architecture & Star Schema
The dataset is structured as a **Star Schema** relational database in Microsoft Access (`SalesDB.accdb`):
* **`SalesT` (Fact Table):** Contains **3,145,725 rows** recording granular transactional details (`Quantity`, `Discount`, `Date`).
* **`Location` (Dimension Table):** Primary location lookup containing `CityCode` and `City`.
* **`Product` (Dimension Table):** Product catalog lookup containing `ProductID`, `Category`, and `Price`.

---

## 🛠️ Tech Stack & Skills
* **Business Intelligence:** Power BI Desktop (DAX Measures, Data Modeling, Geospatial Visuals, Custom Container UI Design).
* **Database Management:** Microsoft Access (`SalesDB.accdb`), Relational Modeling, Foreign Keys.
* **Documentation & Hosting:** GitHub, Kaggle Dataset Hosting.

---

## 📁 Repository Structure
```text
├── Adidas_Sales_Dashboard.pbix # Interactive Power BI Dashboard File
├── images/
│   └── dashboard_preview1.png  # High-resolution dashboard screenshot
└── README.md                   # Project documentation


## 🚀 How to Run Locally
1. Clone this repository:
   ```bash
   git clone [https://github.com/youssef-lfakir/Adidas-Sales-Analytics-PowerBI.git](https://github.com/youssef-lfakir/Adidas-Sales-Analytics-PowerBI.git)
