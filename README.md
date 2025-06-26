# Airbnb-Data-Analysis-Airbnb-Data-Analysis-
Data analysis of Airbnb listings using Python and Power BI.
# Comprehensive Analytical Report for the Airbnb Project: From Raw Data to Interactive Dashboards

## Introduction
This project represents a comprehensive analysis of a dataset from the Airbnb platform, with the objective of exploring the factors that influence the short-term rental market. The data was cleaned and processed using the Python language, and subsequently, an interactive dashboard was built in Microsoft Power BI to present the findings in a visual and insightful manner. This report documents the key analyses that were performed.

## Methodology
This project was executed in two main phases:

1.  **Processing and Exploration Phase (Python):** A comprehensive data cleaning process was performed using Python and the Pandas library. This stage involved correcting data types, handling missing values, and conducting an initial Exploratory Data Analysis (EDA) to understand the data's characteristics and statistical distributions before moving to the visualization phase.
2.  **Dashboard Building Phase (Power BI):** After preparing a clean and reliable data file, the analysis was moved to Microsoft Power BI. An interactive dashboard was built to focus on presenting the most important insights and conclusions visually and dynamically for the end-user.

---

## Key Analyses Presented in the Dashboard

### 1. Question: What are the main Key Performance Indicators (KPIs) that summarize the market?
* **Visual Used:** `Card Visuals`.
* **Insight:** Three main indicators were displayed: the **overall average price**, the **total count of listings**, and the **overall average review score**. These cards provide a quick and immediate overview of the market's scale and general quality level.

### 2. Question: What are the most common property types and what is their market value?
* **Visuals Used:**
    * A **Bar Chart** to display the `count` of listings for each property type.
    * Another **Bar Chart** to display the `average price` for each type.
* **Insight:** The market is dominated by "Entire rental units" by count. However, in terms of value, properties that offer more privacy and space, such as an "Entire home," have a higher average price. This demonstrates that **privacy and space are primary drivers of value**.

### 3. Question: How does the size of a property affect its price?
* **Visuals Used:**
    * A **Bar Chart** showing the "Average price by accommodation capacity (`accommodates`)".
    * Another **Bar Chart** showing the "Average price by number of bedrooms (`bedrooms`)".
* **Insight:** A strong and direct positive correlation exists. The `Bar Charts` clearly show that the average price increases consistently with each additional bedroom or person that the property can accommodate.

### 4. Question: What is the impact of being a "Superhost"?
* **Visuals Used:**
    * A **Pie Chart** to determine their percentage in the market.
    * **Bar Charts** to compare their average `response rate` and `acceptance rate` with regular hosts.
* **Insight:** The `Pie Chart` shows that Superhosts are a small, elite group. The `Bar Charts` confirm that they are not just higher-priced, but are also more professional and reliable, boasting significantly higher response and acceptance rates, which justifies the trust guests place in them.
