# **New York City Taxi and Limousine Commission (TLC) Data Analysis**

## **📌 Project Overview**
Since 1971, the NYC Taxi and Limousine Commission (TLC) has regulated and overseen New York City's taxi cabs, for-hire vehicles, commuter vans, and paratransit vehicles. This project analyzes trip data from the **2017 Yellow Taxi Trip Data table** (sampled from 113 million records) to gain insights into ride patterns, fare estimation, and tipping behavior.

## **📊 Objectives**
- Understand **trip patterns, durations, and fares**.
- Identify key insights about **passenger behavior and payment methods**.
- Apply **statistical methods** to uncover relationships between variables.
- Develop **predictive models** to estimate taxi fares and identify generous tippers.

## **🔍 Key Questions Explored**
1. What are the **peak ride times** on a typical day?
2. How does **total income vary by time of day**?
3. What is the **average daily and monthly income** for taxi drivers?
4. Can we identify **annual trends in rides and revenue**?
5. Which **drop-off locations attract high-paying customers**?
6. Do **credit card users pay more** than cash users?

## **🛠️ Data Processing & Analysis**
- **Data Cleaning:** Fixed data types, removed redundant columns, and reordered data.
- **Feature Engineering:** Constructed new columns to improve insights.
- **Exploratory Data Analysis (EDA):** Used Python for statistical analysis and visualizations.
- **Visualization Tools:** Power BI and Python to enhance insights.
- **A/B Testing:** Evaluated statistical differences between customer groups.
- **Predictive Modeling:**
  - **Regression models** for taxi fare estimation.
  - **Classification models** to predict generous tippers.

## **📈 Key Insights & Findings**
- **Peak Ride Times:** 75% of rides occur between **6 AM and 8 PM**.
- **Revenue Trends:**
  - Morning pickups generate **$93,000 annually ($255 daily)**.
  - Afternoon pickups generate **$95,000 annually ($261 daily)**.
  - Evening pickups generate **$89,000 annually ($243 daily)**.
- **Average Daily Metrics:**
  - **62 rides per day** with **$997 income**.
  - **1,872 passengers per month**, covering **5,503 miles on average**.
- **Seasonal Trends:**
  - March, October, April, and May have **the highest ride volumes**.
  - **Income drops from March to April** while ride durations increase.
  - November and December have the **longest rides**, despite lower ride counts.
- **Top Drop-Off Locations for High-Spenders:**
  - March: IDs **236, 170, 237**
  - October: IDs **236, 161, 237**
  - April: IDs **236, 161, 237**
  - Standard Rate **(Rate 1)** applied to these locations impacts fares.
- **Payment Behavior:**
  - Customers **paying with credit cards** tend to pay **higher fares**.
  - **34% of passengers tip 20% or more** of their fare.

## **🏆 Business Recommendations**
- **Target High-Tip Customers:** Focus on passengers using **credit cards**.
- **Optimize Work Hours:** Drive during **morning, afternoon, and evening peaks**.
- **Strategic Routing:** Prioritize pickups and drop-offs at **high-revenue locations**.
- **Leverage Predictive Models:** Use insights to **adjust fares dynamically**.

## **📂 Project Structure**

📦 NYC-Taxi-Data-Analysis

├── 📄 README.md (Project Overview)

├── 📁 data  -  <a href = https://github.com/Titanking333/Taxi-Data-Project/blob/main/2017_Yellow_Taxi_Trip_Data.csv> Dataset  </a>.

├── 📁 notebooks - <a href = https://github.com/Titanking333/Taxi-Data-Project/blob/main/New%20York%20City%20Taxi%20and%20Limousine%20Commission%20(TLC).ipynb> Cleaning Scripts,EDA, Feature Engineering, Model Training </a>

├── 📁 models (Saved Machine Learning Models)

├── 📁 dashboards -  <a href = https://github.com/Titanking333/Taxi-Data-Project/blob/main/Taxi%20data%20Insight%20Report.pbix> Power BI Dashboards & Visualizations (General) </a> & <a href = https://github.com/Titanking333/Taxi-Data-Project/blob/main/Taxi%20Total%20amount%20and%20tip%20above%20average.pbix> Power BI Dashboards & Visualizations (Ballers) </a>

├── 📁 reports (MS Word Report)


## **📢 Acknowledgments**
Dataset Source: **Google Advanced Data Analytics Course - NYC Open Data Program**

Note: This dataset was created for educational purposes and may not fully represent NYC taxi riders' behavior. 🚕




