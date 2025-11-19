# 🎬 **Netflix Recommendation Project (SVD-Based)**

This project is a simple and clear **movie recommendation system** built using **Singular Value Decomposition (SVD)**. It uses customer movie ratings to understand user preferences and recommend the **Top 5 movies** for each customer.

---

## 📂 **Datasets Used**

### **1️⃣ Customers Dataset**

* **Cust_ID** – Unique customer ID
* **Ratings** – Rating given by the customer (example: RP4)

### **2️⃣ Movie Titles Dataset**

* **Movie_ID** – Unique ID of each movie
* **Year** – Release year
* **Name** – Movie title

This project mainly works with **ratings**. For example, users who rated movies as **RP4** are analyzed to predict better movie recommendations.

---

## 🧠 **Project Goal**

To predict which movies a customer is likely to enjoy by analyzing their past ratings. Using SVD, the system learns hidden patterns and recommends the **Top 5 movies** with the highest predicted ratings.

---

## 🔍 **How It Works**

1. Load both datasets
2. Create a user–movie rating matrix
3. Apply **SVD (Matrix Factorization)**
4. Predict missing ratings
5. Recommend the **Top 5 movies** per customer
6. Convert Movie_ID → Movie Name

---

## 📦 **Technologies Used**

* Python
* Pandas
* NumPy
* SciPy / Surprise (SVD)
* Jupyter Notebook

---

## 🎯 **Key Features**

* Simple and clean SVD-based model
* Ratings-only recommendation logic
* Predicts missing ratings
* Provides **Top 5 personalized movie recommendations**
* Easy-to-understand code for beginners

---

## 📘 **Example Output**

For a given customer:

* **Input:** Ratings (e.g., RP4)
* **Output:** Top 5 recommended movie names

---

## 📝 **Notes**

This project is great for beginners learning about **Collaborative Filtering**, **Matrix Factorization**, and how real recommendation systems like Netflix work.

---
