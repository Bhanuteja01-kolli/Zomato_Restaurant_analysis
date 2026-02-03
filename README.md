# 🍽️ Zomato Bangalore Restaurants Analysis (EDA)

A data-driven exploratory analysis of Zomato Bangalore restaurant listings to understand customer preferences, restaurant performance, and business growth opportunities.

---

## 📌 Project Overview

Zomato is one of India’s leading restaurant discovery and food delivery platforms.  
This project analyzes the **Zomato Bangalore dataset** to generate insights that help:

- Zomato decide which restaurants to promote
- Restaurant owners choose the right location, cuisine, and pricing
- Understand how ratings, cost, and services affect customer engagement

The analysis follows a **Netflix-style EDA approach**, focusing on clear storytelling and business insights rather than heavy technical jargon.

---

## 🎯 Business Objectives

- Identify high-performing restaurant types and cuisines
- Compare Delivery vs Dine-out restaurants
- Analyze the impact of online ordering and table booking on ratings
- Find the best locations to open new restaurants
- Provide actionable recommendations for business growth

---

## 📂 Dataset Information

- **Dataset Name:** Zomato Bangalore Dataset  
- **Records:** Restaurant listings in Bangalore  
- **Key Columns:**
  - `name` – Restaurant name  
  - `online_order` – Online ordering availability  
  - `book_table` – Table booking availability  
  - `rate` – Restaurant rating  
  - `votes` – Number of votes  
  - `location` – Area in Bangalore  
  - `rest_type` – Restaurant type  
  - `cuisines` – Cuisines served  
  - `approx_cost(for two people)` – Cost for two  
  - `listed_in(type)` – Delivery / Dine-out  

⚠️ The dataset is **messy** and contains missing values, text-based numerical columns, and multi-valued categorical fields.

---

## 🧹 Data Pre-processing

The following cleaning steps were performed:

- Converted ratings (`4.2/5`) into numeric values
- Converted cost column into numeric format
- Removed duplicate records
- Handled missing values
- Unnested multi-valued columns:
  - `cuisines`
  - `rest_type`

---

## 📊 Exploratory Data Analysis

### 🔹 Non-Graphical Analysis
- Value counts of online ordering and table booking
- Unique restaurant types, cuisines, and locations

### 🔹 Visual Analysis
- **Univariate Analysis**
  - Ratings distribution
  - Cost distribution
  - Votes distribution
- **Bivariate Analysis**
  - Rating vs Online Order
  - Rating vs Table Booking
  - Rating vs Restaurant Type
  - Rating vs Top Locations

### 🔹 Missing Value & Outlier Analysis
- Identification of missing ratings, cuisines, and restaurant types
- Outlier detection in cost and votes
- Outliers retained as they represent real business cases

---

## 💡 Key Insights

- Restaurants offering **online ordering** tend to have higher ratings
- **Mid-range priced restaurants** perform better than very expensive ones
- **Casual Dining and Cafes** receive more consistent ratings
- Certain locations show higher competition and customer engagement
- A small number of restaurants receive very high votes, indicating strong brand trust

---

## 🚀 Recommendations

- Promote online ordering among partner restaurants
- Encourage mid-range pricing strategies
- Focus on high-demand cuisines
- Expand restaurant partnerships in high-performing locations
- Support new restaurants in improving profile completeness on Zomato

---

## 🛠️ Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📄 Project Output

- Jupyter Notebook (EDA)
- PDF report (Notebook → Print → Save as PDF)
- Graph screenshots for visualization support

---

## 👤 Author

**Bhanuteja Kolli**  
Aspiring Data Scientist | Python | EDA | Machine Learning  



