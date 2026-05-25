# Titanic

🚢 Titanic Data Analysis using SQL

📊 End-to-End Data Cleaning & Insight Generation

📌 Project Overview

This project focuses on analyzing the famous Titanic dataset using SQL Server.
It demonstrates how to clean raw data, handle missing values, and extract meaningful insights using SQL queries.

🧠 Objectives
Perform data cleaning & preprocessing
Handle null values and duplicates
Generate business insights using SQL
Practice real-world data analysis techniques
🗂️ Dataset Information

The dataset contains passenger details such as:

PassengerId
Name
Age
Gender (Sex)
Ticket details
Fare
Cabin
Survival status
⚙️ Steps Performed
🔹 1. Database Setup
Created database: TITANIC
Loaded dataset into TITANIC_DATASET
🔹 2. Data Cleaning

✔️ Checked null values in all columns
✔️ Identified duplicate records (Name & Ticket)
✔️ Removed extra spaces using TRIM()
✔️ Handled missing values:

Age → replaced with average age
Cabin, Embarked → replaced with 'Not Defined'
🔹 3. Data Analysis & Insights
📊 Passenger Insights
Total passengers count
Survived vs Unsurvived passengers
Gender-wise survival analysis
👨‍👩‍👧 Demographic Analysis
Survival based on Age groups
Passenger class (Pclass) distribution
Gender distribution across classes
👪 Family Analysis
Passengers traveling with siblings/spouses (SibSp)
Passengers traveling with parents/children (Parch)
💰 Fare Analysis
Average fare
Minimum & Maximum fare
Total fare collected
Fare distribution by gender
📍 Embarkation Analysis
Passenger count by embarkation point
📈 Key Insights
👩 Females had a higher survival rate than males
🎟️ Passengers in 1st class had better survival chances
👶 Children (Age ≤ 10) showed higher survival probability
💸 Higher fare passengers were more likely to survive
🛠️ SQL Concepts Used
GROUP BY, HAVING
CASE WHEN
Aggregate functions (COUNT, AVG, SUM, MIN, MAX)
Data cleaning functions (TRIM)
Subqueries
Transactions (BEGIN TRANSACTION)
🚀 How to Use
Clone this repository
Open SQL Server Management Studio (SSMS)
Run the SQL script
Explore insights using queries
💡 Future Improvements
Create views for reusable insights
Build stored procedures
Connect with Power BI / Tableau dashboard
Apply advanced analytics (ML models)
👨‍💻 Author

Anshu Das
📊 Data Analyst | SQL Enthusiast

⭐ Support

If you like this project, don’t forget to star ⭐ the repo and share!

If you want, I can also:

Add badges (GitHub style)
Make it more colorful with icons & design
Or create a LinkedIn post for this project 🚀
