# 🏡 Airbnb Data Analysis and Visualization

## 📖 Overview
This project focuses on analyzing Airbnb open data to discover insights about property prices, host listings, service fees, and customer reviews.  
It uses Python-based data analysis and visualization techniques to understand market trends and user behavior patterns.

---

## 🎯 Objectives
- Clean and preprocess the Airbnb dataset for consistency.  
- Identify neighborhoods with the highest listings and prices.  
- Explore host activity, availability, and review patterns.  
- Visualize trends using statistical charts and plots.  

---

## 🧹 Data Cleaning Process
- Removed duplicate and missing records.  
- Dropped columns with insufficient data (`house_rules`, `license`).  
- Cleaned currency columns by removing `$` and `,`.  
- Corrected spelling errors (e.g., “Brookln” → “Brooklyn”).  
- Adjusted incorrect data types and removed outliers in `availability_365`.

---

## 📊 Exploratory Data Analysis (EDA)
Performed statistical and visual analysis to answer key questions such as:
- Which neighborhoods have the most listings?
- Which areas have the highest average prices?
- How are price and service fee correlated?
- Are verified hosts rated higher by guests?

---

## 📈 Results Summary
- **Brooklyn** and **Manhattan** have the highest number of listings.  
- **Manhattan** shows the highest average property prices.  
- **Verified hosts** tend to receive higher review ratings.  
- **Positive correlation** found between price and service fee.  
- Hosts with multiple listings generally have lower average availability.

---

## ⚙️ Technologies Used
- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
  
---

