# Google-Play-Store-Apps-Data-Cleaning-and-EDA
Data cleaning and exploratory data analysis on Google Play Store apps using Python to identify popular categories, top apps, and key performance trends.

## Project Overview
With millions of mobile applications available on the Google Play Store, understanding app performance, popularity, and user behavior has become increasingly important for developers and businesses. This project focuses on **cleaning, analyzing, and extracting insights** from a real-world Google Play Store dataset using **Python and advanced data analysis libraries**.

The goal of this project is to transform raw app data into a clean, analysis-ready dataset and perform **exploratory data analysis (EDA)** to answer key business-driven questions related to app popularity, categories, installs, ratings, and app characteristics.

---

## Problem Statement
Today, over **1.85 million apps** are available for users to download, with **Android users having access to more than 2.56 million apps** through the Google Play Store. These applications play a significant role in modern digital lifestyles.

**Objectives of this project include:**
- Identifying the **most popular app categories**
- Finding the **apps with the highest number of installs**
- Analyzing **app size distribution**
- Understanding the relationship between **ratings, reviews, installs, and pricing**
- Extracting insights that can guide app development and business strategy

---

## Dataset Description
- **Rows:** 10,841  
- **Columns:** 20 (raw), refined during cleaning  
- **Source:** Google Play Store public dataset

### Key Columns
- App Name
- Category
- Rating
- Reviews
- Size
- Installs
- Type (Free / Paid)
- Price
- Content Rating
- Genres
- Last Updated
- Android Version

---

## Tools & Technologies
- **Python**
- **Jupyter Notebook**
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical operations
- **Matplotlib & Seaborn** – Data visualization
- **Datetime utilities** – Date feature handling
- **EDA techniques** – Statistical and visual analysis

---

## Data Cleaning & Preparation
A comprehensive data cleaning process was applied to improve data quality and reliability:

- Removed duplicate records
- Handled missing and null values (ratings, sizes, versions)
- Converted `Installs` and `Price` from string format to numeric
- Cleaned and standardized `Size` values (MB / KB → numeric)
- Converted `Last Updated` into datetime format
- Removed irrelevant columns and corrected data types
- Filtered invalid or inconsistent records

The cleaned dataset was structured to support meaningful analysis and visualization.

---

## Exploratory Data Analysis (EDA)
The cleaned data was analyzed to uncover trends and patterns across the Play Store ecosystem.

### Key Analyses Performed
- Category-wise app distribution
- Most popular app categories by installs
- Top apps by number of installs
- Relationship between app ratings and reviews
- Free vs Paid app comparison
- App size distribution and its impact on installs
- Content rating and genre-level insights

Multiple visualizations were created to support intuitive interpretation of trends.

---

## Key Insights
- Certain categories dominate the Play Store in terms of app count and installs
- Free apps significantly outperform paid apps in total installs
- Apps with higher reviews tend to have better ratings
- App size shows varying influence depending on category
- A small number of apps contribute to a large share of total installs

---

## Project Outcome
- Delivered a **clean, analysis-ready dataset**
- Extracted **actionable insights** from real-world app data
- Demonstrated strong skills in **data cleaning, EDA, and visualization**
- Built a project suitable for **Data Analyst / Data Scientist roles**

---

## Files Included
- Raw dataset (CSV)
- Jupyter Notebook (.ipynb) containing:
  - Data cleaning
  - EDA
  - Visualizations
  - Insights

---

## Author
**Mayur Bhamare**  
Data Analyst | Python | EDA | Data Visualization
