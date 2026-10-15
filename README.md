
# 🧾 Churn Analysis & Customer Intelligence

_Analyzing customer churn patterns, subscription trends, and revenue insights to evaluate customer retention and subscription performance using SQL and Python._

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#feature-engineering">Feature Engineering</a>
- <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author--contact">Author & Contact</a>

---
<h2><a class="anchor" id="overview"></a>Overview</h2>

This project analyzes customer behavior, subscription patterns, and retention trends to gain insights into customer churn and subscription performance. A structured data analysis workflow was developed using SQL for data extraction and Python for data cleaning, feature engineering, EDA, and visualization to identify key customer and revenue trends.

---
<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

Customer retention is critical for sustainable growth in the highly competitive OTT streaming industry. This project aims to:
- Understand customer churn and retention patterns
- Identify subscription plans with higher churn
- Examine regional differences in customer retention
- Evaluate revenue trends and financial performance
- Explore customer support experiences and subscription preferences

---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- The customer_churn database in SQL contains three tables: Customer, Subscription, and Support
- Created an exported_churn_data table in CSV format for further analysis

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- SQL & Python Integration (numpy, pandas, sqlite3, matplotlib, seaborn)
- GitHub

---
<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
Customer-Churn-Analysis/
├── README.md
├── .gitignore
├── Customer Churn Report.pdf
└── churn analysis.ipynb
```

---
<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

- Customer Table
  - Rename Columns
  - Drop Unnecessary Columns
  - Change Data Type
  - Data standardization
  - Fix Missing Values Using Existing Data
- Subscription Table
  - Change Data Type to Date
- Support Table
  - Drop Unnecessary Columns
  - Change Data Type to Date

---
<h2><a class="anchor" id="feature-engineering"></a>Feature Engineering</h2>

- Create new calculated cols
- Data transformation
- Use filters 

---
<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

1. Churn Rate: 28.6%   |  Retention Rate:  71.4%
2. Most of the churn is from basic subscription plan – nothing to worry in terms of major revenue impact 
3. Most of the churn happened in the month of Sep 2024 and, most affected state is Karnataka 
4. Average Tenure (Days): 1,451  |  ARPU is Rs 18.8 
5. Revenue loss due to churn = 74 
6. % Revenue loss = 18% 

---
<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

- Evaluate Basic plan pricing and subscription value
- Promote annual plans to encourage longer subscriptions
- Focus retention efforts on high-churn states
- Monitor revenue trends across subscription plans
- Use customer and support data to improve retention strategies

---
<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Prachi Verma**  
🔗 [LinkedIn](https://www.linkedin.com/in/prachi-verma-p05v09t29/) 
