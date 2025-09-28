Telco Customer Churn Analysis

📌 Project Overview:
This project analyzes customer churn behavior using the Telco Customer Churn dataset (Kaggle). The main goal was to identify the key factors driving churn, predict churn probability using machine learning, and build interactive dashboards in Power BI to help businesses reduce customer loss.

Data preprocessing and churn prediction were performed using Python, while customer segmentation and insights were visualized in Power BI dashboards.

🎯 Objectives:

- Clean and preprocess the Telco dataset to handle missing values and transformations.
- Build customer profiles vs churner profiles to compare their demographics and service usage.
- Analyze contract types, tenure bins, and payment methods to identify risk patterns.
- Develop a Random Forest model to predict customer churn.
- Visualize predicted churners vs non-predicted churners to understand overall risk.
- Provide actionable insights for customer retention strategies.

🛠 Tools & Techniques Used:

- Python (Pandas, NumPy, Sklearn): Data cleaning, preprocessing, Random Forest model for churn prediction.
- Power BI: Interactive dashboards, gauges, slicers, and comparative analysis of churners vs non-churners.
- Data Cleaning Techniques: Handling missing values, column transformations, feature engineering, exporting to CSV.

📊 Observations from Dashboards:

1️⃣ Client Profile vs Churner Profile (Page 1)

Non-Churners (Blue Section):

- Higher proportion of customers have longer tenure.
- Many are on One-Year or Two-Year contracts, which reduces churn risk.
- Partners present (53%) and Senior Citizens (13%) are less likely to churn.
- Lower average monthly charges (~$61.3) compared to churners.

Churners (Red Section):

- Majority are on Month-to-Month contracts.
- Higher share of Senior Citizens (25%).
- Customers without partners are more likely to churn.
- Average monthly charges are higher (~$74.4), indicating cost sensitivity.

📌 Insight: Long-term contracts and lower charges reduce churn risk, while high monthly bills and no partner increase churn probability.

2️⃣ Phone Services Analysis (Page 2)

Non-Churners (Blue Section):

- More likely to have multiple services (Internet, Tech Support, Online Backup).
- Stronger adoption of value-added services shows better retention.

Churners (Red Section):

- Many customers lack Tech Support or Online Security, leading to dissatisfaction.
- Higher churn seen among customers with only phone services or fiber optic internet.

📌 Insight: Offering bundled services and better customer support can reduce churn.

Predicted Churn vs Non-Predicted Churn (Model Output):

Gauges for Prediction:

- Predicted Churners: ~1.44K customers are at risk of leaving.
- Non-Predicted Churners: ~5.1K customers are safe.
- Slicers Added (Contract Type, Payment Method, and Tenure)

Through these slicers, the gauges dynamically show:

- How churn risk changes across different contracts and payment methods.
- Average monthly charges and total charges for each segment.
- Distribution of churn probability, giving a clear picture of high-risk vs low-risk customers.

📌 Insight: The Random Forest model highlights that a significant proportion of customers are likely to churn in the future, giving the business an early warning to take action.


✨ Key Takeaways:

- Customers with Month-to-Month contracts, high monthly charges, and no additional services are most vulnerable to churn.
- Customers with longer tenure, bundled services, and partner support are less likely to churn.
- The prediction model provides an early churn risk indicator, helping businesses prioritize retention campaigns.

📂 Project Files:

- Telco_Customer_Churn.csv: Original dataset from Kaggle.
- Telco_Customer_Churn_Cleaned.csv: Cleaned dataset after preprocessing in Python.
- Telco_Customer_Churn_Predicted.csv: Model output with Churn_Predicted and Churn_Probability.
- Customer_Visualiation.pbix: Power BI dashboard file.
- Dashboard_Page1.jpg: Screenshot of Client Profile vs Churner Profile.
- Dashboard_Page2.jpg: Screenshot of Phone Services & Predictions.
- README.md: Project documentation (this file).

📢 Conclusion:
The analysis shows that contract type, tenure, payment method, and monthly charges are key drivers of churn. Power BI dashboards provide a clear comparison between churners and non-churners, while the Random Forest model predicts potential churners, allowing proactive interventions. Businesses can use these insights to design better retention strategies, lower churn rate, and increase customer loyalty.