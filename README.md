# Customer-Behavior-Data-Analysis
Data analysis on customer behavior using python, sql, Powerbi

📌 Overview

This project analyzes customer shopping behavior using transactional data to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior. The goal is to support data-driven business decisions through exploratory analysis, SQL-based insights, and interactive dashboards.

📂 Dataset

Records: 3,900 customer purchases
Columns: 18
Key Features:
Customer demographics (Age, Gender, Location, Subscription Status)
Purchase details (Item, Category, Amount, Season, Size, Color)
Shopping behavior (Discounts, Previous Purchases, Review Ratings, Shipping Type)
Missing Data: Review ratings (handled during cleaning)

🛠 Tools & Technologies

Python: pandas, numpy, matplotlib, seaborn
SQL: PostgreSQL 
BI Tool: Power BI
Reporting: PowerPoint
Database Connectivity: psycopg2 / SQLAlchemy

🔍 Project Steps

Data Loading
Imported dataset into Python using pandas.

Exploratory Data Analysis (EDA)
Summary statistics and structure analysis
Distribution and trend visualizations
Initial business questions exploration

Data Cleaning & Feature Engineering
Handled missing values in review ratings
Standardized column names
Created age groups and customer segments
Removed redundant fields

SQL Analysis
Revenue analysis by gender and age group
Subscriber vs non-subscriber behavior
High-spending discount users
Product performance and customer loyalty analysis
Dashboard Creation
Built an interactive Power BI dashboard with KPIs, filters, and visual insights.

Reporting
Created a structured PowerPoint summarizing insights and business recommendations.

📊 Dashboard Highlights

Total customers and average purchase value

Revenue by category and age group

Subscription distribution

Sales and rating trends

Customer segmentation (New, Returning, Loyal)

📈 Key Results

Loyal customers contribute the majority of purchases

Subscribers and non-subscribers show different revenue patterns

Certain products are highly discount-dependent

Younger and middle-aged customers generate higher revenue

Express shipping users have slightly higher average spend

▶️ How to Run the Project

1.Clone the Repository
git clone https://github.com/Sujal118/Customer-Behavior-Data-Analysis.git


2.Install Dependencies
pip install -r requirements.txt


3.Run Python Analysis
python eda_analysis.py


4.Load Data into Database
Configure database credentials
Run SQL scripts from the /sql folder

5.View Dashboard
Open the .pbix file in Power BI Desktop
