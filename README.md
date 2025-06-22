# 📊 Global Super Store - Data Modeling & Analysis Project

This project was developed as part of the **Data Modeling & Business Intelligence course**, and it focuses on building a complete data workflow for the fictional "Global Super Store" business case.

---

## 📁 Project Overview

The project involves:

1. Designing and normalizing a relational database.
2. Implementing the schema using **MySQL Workbench**.
3. Building a **dimensional data model** using a Star Schema.
4. Analyzing data and building an **interactive dashboard** using **Tableau Desktop**.

---

## 🧱 1. Entity-Relationship (ER) Modeling

- ✅ Designed a **high-level conceptual data model**.
- ✅ Created a **logical ER diagram** for the Global Super Store.
- ✅ Applied **1NF, 2NF, and 3NF** to ensure normalized structure.
- ✅ Implemented the schema in **MySQL Workbench** using the **Forward Engineer** method.

---

## 🛠️ 2. MySQL Database Implementation

- Built tables and relationships based on the ER model.
- Used **MySQL Workbench** to deploy the schema to the local **MySQL Server**.
- Created **a virtual table (view)** to summarize data across multiple tables for analytical use.

---

## 🌟 3. Dimensional Modeling

- Designed a **Star Schema** to support fast analytical queries.
- Included:
  - One central **Fact Table** (e.g., `Sales_Fact`)
  - Multiple **Dimension Tables** (e.g., `Customer_Dim`, `Product_Dim`, `Region_Dim`, `Date_Dim`)

---

## 📊 4. Data Analysis and Dashboard (Tableau)

- Imported cleaned data into **Tableau Desktop**.
- Built **several analytical charts** (e.g., sales by region, profit by category, order trends).
- Created an **interactive dashboard** to help stakeholders explore and understand sales performance.

---

## 💻 Tools Used

- 🛠️ **MySQL Workbench**
- 🗄️ **MySQL Server**
- 📊 **Tableau Desktop**
- 📚 **Normalization Techniques (1NF, 2NF, 3NF)**

---

## 📌 How to Use

1. Clone the repository.
2. Open the `.mwb` file in MySQL Workbench to view the ER diagram.
3. Use the SQL scripts to deploy the database via Forward Engineering.
4. Open the Tableau `.twbx` file to view the final dashboard and visualizations.

---



