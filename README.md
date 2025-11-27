# Customer-churn-analysis
Customer Churn Analysis using Python &amp; Power BI
📊 Customer Churn Analysis – Python & Power BI
🔍 An end-to-end data analysis and business intelligence project exploring customer churn using Python (EDA + Feature Engineering) and Power BI (Interactive Dashboard).
🚀 Project Summary

This project analyzes customer churn patterns, identifies high-risk customer segments, and uncovers key business drivers using Python for data preparation & feature engineering and Power BI for visualization & insights.

The final deliverable is a fully interactive Power BI dashboard and a detailed churn analysis report suitable for business stakeholders.

🛠️ Tech Stack

📁 Project Structure
├── data/
│   └── customer_churn.csv
├── analysis/
│   └── customer_churn.ipynb
├── dashboard/
│   └── First_project.pbix
└── README.md

📘 Objective

To understand customer churn behavior, engineer meaningful features, uncover patterns, and build an interactive dashboard that helps businesses:

Identify high-risk customers

Detect churn-driving factors

Make data-backed retention decisions

📊 Workflow

🔹 1. Data Cleaning (Python)

Handled missing values

Normalized column formats

Converted dates

Corrected data types

Extracted City and State from address

🔹 2. Feature Engineering (Python)

Created advanced customer metrics:

Feature	Description
AgeGroup	Categorized age brackets
TenureGroup	Groups based on customer years
SpendPerYear	Total spend normalized per year
SitesPerYear	Number of sites per year
EngagementScore	Tenure × Sites
LoyaltyScore	Total purchase ÷ (Years + 1)
LocationRisk	State-level churn probability
CompanyRisk	Company-level churn probability

These features help uncover patterns that raw data cannot reveal.

🔹 3. Exploratory Data Analysis

Churn distribution

Correlation analysis

Box plots, histograms, scatterplots

Segment-level churn behavior

State-wise churn hotspots

🔹 4. Power BI Dashboard

Created an interactive dashboard with:

KPI Cards

✔️ Churn Rate
✔️ Total Customers
✔️ Churned Customers

Customer Segments

Churn by AgeGroup

Churn by Tenure

Churn by Account Manager

Engagement & Behavior

Churn vs SpendPerYear

Churn vs SitesPerYear

Churn vs LoyaltyScore

EngagementScore trends

Geographical Insights

Churn by State

LocationRisk analysis

📈 Key Insights

✔️ Customers with < 3 years of tenure churn significantly more.
✔️ Higher churn among customers with multiple sites.
✔️ Lack of an Account Manager strongly correlates with churn.
✔️ Low SpendPerYear and LoyaltyScore indicate churn-prone customers.
✔️ Some states show statistically higher churn rates.

📝 Business Recommendations

Improve onboarding for early-tenure customers

Provide special support to high-site customers

Assign account managers to at-risk segments

Offer engagement incentives to low-spend customers

Investigate high-churn states for service gaps or competition

🖥️ Dashboard Preview

(Add your dashboard screenshot here)


🧰 How to Run This Project
1️⃣ Clone the repository
git clone <your-repo-link>

2️⃣ Install required Python libraries
pip install -r requirements.txt

3️⃣ Open the analysis notebook
jupyter notebook analysis/customer_churn.ipynb

4️⃣ Open the dashboard

Open the Power BI file:

dashboard/First_project.pbix

✔️ Final Deliverables

Cleaned & engineered dataset

Python Notebook with EDA & feature engineering

Interactive Power BI Dashboard

Professional written report

GitHub portfolio-ready repository

🙌 Acknowledgements

This project was created to strengthen end-to-end data analytics skills including Python, Power BI, and business storytelling.

⭐ If you like this project

Give the repo a ⭐ on GitHub — it helps!
