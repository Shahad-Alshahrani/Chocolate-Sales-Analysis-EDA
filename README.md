# 🍫 Chocolate Sales Analysis — Exploratory Data Analysis

<img width="100%" height="100%" alt="Dashboard Choco" src="https://github.com/user-attachments/assets/ff68fad9-9318-4e6f-855e-23ec4df8cde5" />


## 📌 Project Overview

This project presents an **Exploratory Data Analysis (EDA)** of chocolate sales data for **2022**. The analysis focuses on understanding overall sales performance, identifying top-performing products and sales representatives, comparing sales across countries, and analyzing monthly sales patterns.

The goal is to extract meaningful business insights from the sales data and identify areas of strong performance and potential opportunities for improvement.

## 📊 Key Performance Indicators (KPIs)

* **Total Sales:** $6,183,625
* **Total Boxes Shipped:** 177,007
* **Sales Transactions:** 1,094
* **Sales Persons:** 25
* **Countries:** 6
* **Products:** 22
* **Average Sales per Transaction:** ~$5,652
* **Average Boxes per Transaction:** ~162

The dataset contains **1,094 records and 6 original columns**, with no missing values or duplicate records.

## 📈 Sales Performance

The analysis shows a total sales value of **$6.18 million** across the eight months covered in the dataset, with **177,007 boxes shipped**.

The typical transaction generated approximately **$4,800–$5,000**, while larger transactions reached more than **$22,000**, indicating significant variation in order value.

### 🔍 Key Observations

* **Strong overall sales volume:** More than $6.1M in sales was generated during the analyzed period.
* **High transaction variability:** Sales amounts vary considerably between transactions, with several high-value orders.
* **No data quality issues:** The dataset contains no missing values or duplicate records.
* **Seasonal variation:** Monthly sales differ noticeably, with January recording the highest sales and April the lowest.

## 🌍 Sales by Country

Sales were analyzed across **six countries**:

| Country          | Total Sales |
| ---------------- | ----------: |
| 🇦🇺 Australia   |  $1,137,367 |
| 🇬🇧 UK          |  $1,051,792 |
| 🇮🇳 India       |  $1,045,800 |
| 🇺🇸 USA         |  $1,035,349 |
| 🇨🇦 Canada      |    $962,899 |
| 🇳🇿 New Zealand |    $950,418 |

### 🔍 Key Observations

* **Australia** generated the highest total sales at approximately **$1.14M**.
* The **UK, India, and USA** also showed strong and relatively similar performance.
* **New Zealand** recorded the lowest sales among the six markets, followed closely by Canada.
* The relatively close sales values across countries suggest that performance is distributed across multiple markets rather than being dependent on a single country.

## 🍫 Product Analysis

The dataset contains **22 chocolate products**.

### 🏆 Top 5 Products

| Product                 | Total Sales |
| ----------------------- | ----------: |
| **Smooth Sliky Salty**  |    $349,692 |
| **50% Dark Bites**      |    $341,712 |
| **White Choc**          |    $329,147 |
| **Peanut Butter Cubes** |    $324,842 |
| **Eclairs**             |    $312,445 |

The analysis ranked products according to their total sales to identify the strongest-performing products.

### 🔍 Key Observations

* **Smooth Sliky Salty** is the highest-selling product, generating approximately **$350K**.
* **50% Dark Bites** follows closely, indicating strong demand for dark chocolate products.
* The top-performing products have relatively close sales values, suggesting demand is spread across several products.
* The lowest-performing product in the analysis was **70% Dark Bites**, with approximately **$212K** in sales.

## 👤 Sales Representative Performance

Sales performance was also analyzed by individual sales representatives.

### 🏆 Top 5 Sales Persons

| Sales Person        | Total Sales |
| ------------------- | ----------: |
| **Ches Bonnell**    |    $320,901 |
| **Oby Sorrel**      |    $316,645 |
| **Madelene Upcott** |    $316,099 |
| **Brien Boise**     |    $312,816 |
| **Kelci Walkden**   |    $311,710 |

### 🔍 Key Observations

* **Ches Bonnell** achieved the highest sales among the 25 sales representatives.
* The top five representatives performed at a very similar level, with each generating more than **$311K**.
* This relatively narrow performance gap suggests that sales are not concentrated around a single representative.

## 📅 Monthly Sales Trends

Sales were analyzed by month to identify periods of stronger and weaker performance.

| Month        | Total Sales |
| ------------ | ----------: |
| **January**  |    $896,105 |
| **February** |    $699,377 |
| **March**    |    $749,483 |
| **April**    |    $674,051 |
| **May**      |    $752,892 |
| **June**     |    $865,144 |
| **July**     |    $803,425 |
| **August**   |    $743,148 |

### 🔍 Key Observations

* **January** recorded the highest monthly sales at approximately **$896K**.
* **June** was the second strongest month with approximately **$865K**.
* **April** recorded the lowest monthly sales at approximately **$674K**.
* Sales recovered after April, reaching stronger levels during May, June, and July.

## 💡 Strategic Recommendations

1. **Focus on High-Performing Products:**
   Maintain strong inventory levels for products such as **Smooth Sliky Salty**, **50% Dark Bites**, and **White Choc** to support continued demand.

2. **Strengthen Lower-Performing Products:**
   Investigate the reasons behind weaker sales of products such as **70% Dark Bites** and consider targeted promotions, product positioning, or bundling strategies.

3. **Market-Specific Strategies:**
   Continue supporting high-performing markets such as **Australia**, while developing targeted campaigns to improve performance in **New Zealand and Canada**.

4. **Leverage Top Sales Representatives:**
   Analyze the sales approaches used by the highest-performing representatives and use successful practices to improve overall sales team performance.

5. **Plan Around Monthly Trends:**
   Prepare inventory and marketing campaigns ahead of high-performing periods such as **January and June**, while investigating the causes behind weaker performance in **April**.

## 🛠️ Tools & Technologies

* **Programming Language:** Python
* **Data Manipulation:** Pandas
* **Numerical Analysis:** NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Google Colab / Jupyter Notebook
* **Analysis Type:** Exploratory Data Analysis (EDA)

## 🔎 Data Preparation

The analysis included:

* Checking dataset dimensions and data types.
* Converting the **Date** column into datetime format.
* Cleaning the **Amount** column by removing `$` and comma separators and converting it to numeric values.
* Checking for missing values.
* Checking for duplicate records.
* Creating additional **Year, Month, and Day** features for time-based analysis.

  ## 📊 Interactive Power BI Dashboard

To make the analysis more accessible and easier to understand, I developed an **interactive Power BI dashboard** based on the findings from the Python EDA.

The dashboard provides a clear and interactive way to explore the sales data, allowing users to navigate between different views and analyze performance without having to work directly with Python code.

This makes the insights easier for non-technical users and decision-makers to navigate, understand, and use for business decisions.


## 📌 Conclusion

The analysis provides an overview of chocolate sales performance across **products, countries, sales representatives, and months**.

Overall, the business generated **$6.18M in sales from 177K shipped boxes**, with Australia emerging as the strongest market and **Smooth Sliky Salty** as the top-performing product. Monthly analysis also revealed noticeable fluctuations, with January and June representing particularly strong sales periods.
These findings can support better **inventory planning, product strategy, market targeting, and sales-team performance management**.


## 🛠️ Tools Used
* Data Source: Kaggle
* Analysis: Python
* Visualization: Power BI
