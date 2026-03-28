# 📊 SQL Data Warehouse Project

## 🧠 Overview

This project is a hands-on implementation of concepts from *The Data Warehouse Toolkit (3rd Edition)* by Ralph Kimball.  
It recreates real-world scenarios using **fictional datasets** to demonstrate how dimensional modeling works in practice.

The goal is to bridge the gap between theory and implementation by building a simplified, yet realistic, data warehouse environment.

---

## 🎯 Objectives

- Apply core data warehousing concepts in a practical context  
- Design a dimensional model (star schema)  
- Work with realistic, but fictional, business data  
- Build a structured database optimized for analytical queries  
- Translate textbook examples into executable SQL  

---

## 🏗️ Architecture

The project follows a simplified data warehouse structure focused on analytical modeling:

- Central **fact tables** capturing business events  
- Surrounding **dimension tables** providing descriptive context  
- Clear separation between raw data and analytical structures  

---

## 🧩 Data Modeling

This project applies Kimball’s dimensional modeling principles:

- **Fact tables** for measurable business processes  
- **Dimension tables** such as customers, products, dates, etc.  
- Use of **surrogate keys**  
- Handling of **Slowly Changing Dimensions (SCD)**  

### Example schema

- `fact_sales`  
- `dim_customer`  
- `dim_product`  
- `dim_date`  
- `dim_store`  

---

## 📊 Data

All datasets used in this project are **synthetic** and created for educational purposes.  
They are designed to mimic real-world business scenarios while remaining simple and easy to understand.
