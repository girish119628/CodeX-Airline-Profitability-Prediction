# CodeX-Airline-Profitability-Prediction

✈️ Project Overview

This project aims to predict airline profitability using Machine Learning techniques. By analyzing key operational and financial metrics such as Revenue, Cost Efficiency, Flight Delays, Load Factor, and Fuel Consumption, we provide actionable insights to optimize airline operations.

📌 Key Features

1. Predicts Airline Profitability – Helps airlines maximize revenue & reduce costs.
2. Data-Driven Insights – Identifies factors affecting profit (Revenue, Delays, Costs, etc.).
3. Machine Learning Model – Stacked ensemble model for high accuracy.
4. SHAP Interpretability – Explains the impact of each feature on profitability.
5. Business Recommendations – Optimize flight schedules, fuel efficiency, and pricing strategies.

📂 Repository Structure

📂 CodeX  (Main Repository)
│── 📁 data/               # CSV Datasets
│   ├── flight_data.csv  
│   ├── processed_data.csv  
│
│── 📁 notebooks/          # Jupyter Notebooks
│   ├── CodeX.ipynb
│
│── 📁 reports/            # Presentations & Documentation
│   ├── Business_Report.pdf
│   ├── Airline_Profitability_Presentation.pptx
│
│── 📁 resources/          # Supporting Resources (e.g., video links)
│   ├── README.md
│   ├── Google_Drive_Link.txt  # Video Explanation Link
│
│── 📜 LICENSE             # Open-source License
│── 📜 CONTRIBUTING.md      # Contribution Guidelines
│── 📜 .gitignore          # Ignore unnecessary files (e.g., .DS_Store, .ipynb_checkpoints)
│── 📜 README.md           # Project Overview

📊 Dataset Description

The dataset includes historical flight performance data with the following key attributes:

Flight Number – Unique identifier for each flight.

Delay (Minutes) – Flight delays impacting operational efficiency.

Aircraft Utilization (Hours/Day) – How efficiently aircraft are used.

Revenue (USD) – Total revenue generated per flight.

Operating Cost (USD) – Total cost incurred for each flight.

Profit (USD) – Revenue - Operating Cost.

Load Factor (%) – Seat occupancy percentage.

Fuel Efficiency (ASK) – Cost of fuel per Available Seat Kilometer.

Profit Margin (%) – Ratio of profit to revenue.

Is_Holiday_Season – 1 if the flight occurs during a peak season.

📌 Target Variable: Profit (USD)

🤖 Machine Learning Approach

📌 Model Selection

We implemented the following models and chose the best-performing one:

Linear Regression ✅

Random Forest Regressor ✅

XGBoost Regressor ✅

LightGBM Regressor ✅

Stacked Model (Best Performance) 🚀

📊 Model Performance

Model

MAE (Lower Better)

RMSE (Lower Better)

R² Score (Higher Better)

LightGBM (Before Tuning)

94.27

120.18

0.999956

Stacked Model (Final) 🚀

25.33 ✅

34.89 ✅

0.999996 ✅

🔹 Feature Importance (SHAP Analysis): Revenue, Cost Efficiency, Delays, Fuel Cost are top contributors.

📈 Visualizations & Insights

📊 Exploratory Data Analysis (EDA):

Histogram & Box Plots – Check data distribution & outliers.

Scatter Plots – Analyze relationships (e.g., Revenue vs. Profit).

SHAP Feature Importance – Explainability of ML predictions.

📊 Top 5 Analysis:

Category

Top 5 Flight Numbers

Key Metric

Most Profitable

FLXXX, FLXXX, FLXXX

Highest Profit

Least Profitable

FLXXX, FLXXX, FLXXX

Loss-Making Flights

Most Delayed

FLXXX, FLXXX, FLXXX

Longest Delays

Least Delayed

FLXXX, FLXXX, FLXXX

Most Efficient Flights

🚀 How to Use This Repository?

Clone the Repository

git clone https://github.com/your-username/CodeX.git
cd CodeX

Run Jupyter Notebook (Ensure Python & dependencies are installed)

jupyter notebook

Explore the Data & Models

Open notebooks/CodeX.ipynb

Run the model training & evaluation steps.

Check the Business Report & Presentation in reports/

Watch the Video Explanation (link in resources/Google_Drive_Link.txt)
