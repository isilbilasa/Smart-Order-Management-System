# 🎯 Smart Order Management System (v2)

A Python-based order management system that analyzes e-commerce order data using core data structures (List, Dictionary, Set, Tuple) without using loops or functions.

---

## 📖 Table of Contents
- About the Project  
- Features  
- Technologies  
- Project Logic  
- Technical Analysis  
- Installation & Usage  
- Conclusion  
- Author  

---

## 🧐 About the Project

This project explores how data structures and basic control mechanisms form the foundation of modern software systems.

It demonstrates that:
- Data should not only be stored, but stored in the **most appropriate structure**
- Even without loops and functions, a **functional system can be built**
- Decision-making mechanisms (**Boolean & If/Else**) directly represent real-world business rules

---

## ✨ Features

- ✔️ **Order Analysis**  
  Tracks total, paid, and unpaid orders  

- ✔️ **Customer Management**  
  Removes duplicate records and creates a unique customer list  

- ✔️ **Inventory Analysis**  
  Extracts unique product types from all orders  

- ✔️ **Data Integrity**  
  Protects financial summaries using immutable data structures  

---

## 🛠 Technologies

- **Language:** Python 3.x  
- **Environment:** Jupyter Notebook (.ipynb)  

**Core Concepts:**
- Data Structures → List, Dictionary, Set, Tuple  
- Logic → Boolean, If / Elif / Else  

---

## 🏗 Project Logic

The system is designed with minimal tools to maximize clarity and data accuracy:

- **Raw Data Input**  
  Orders are stored as dictionaries inside a list  

- **Manual Analysis**  
  Payment status is evaluated using index-based access and conditional checks  

- **Deduplication**  
  Sets are used to automatically remove duplicate customers and products  

- **Secure Summary**  
  Tuples are used to "seal" financial results (customer, total)  

---

## 📊 Technical Analysis

| Data Structure | Purpose | Why It Was Chosen |
|----------------|--------|------------------|
| **List** | Orders & Items | Maintains order and supports dynamic grouping |
| **Dictionary** | Order Details | Provides fast access via key-value structure |
| **Set** | Unique Data | Automatically removes duplicates |
| **Tuple** | Financial Summary | Immutable structure prevents data corruption |

---

## 🚀 Installation & Usage

### 1. Clone the repository
```bash
git clone https://github.com/isilbilasa/smart-order-management.git
cd smart-order-management
```

### 2. Run the project
```bash
jupyter notebook smart_order_management.ipynb
```
## 📝 Conclusion
This project proves that choosing the right data structure is not only about making code work — it is essential for:  
- Data integrity
- System reliability
- Scalability
  
Even with basic programming constructs, a well-designed system can effectively model real-world workflows.
## 👤 Author
Işıl Bilasa  
GitHub: @isilbilasa

