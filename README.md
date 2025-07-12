# Customer-Analysis
📝 Project Description:
This project involves analyzing a telecom company's customer data to understand patterns and reasons behind customer churn, as well as customer behavior and demographics. The dataset contains 7043 rows and 38 columns representing customer demographic information, service usage metrics, subscription details, and churn-related data.

🔍 Key Objectives:
Analyze customer demographics and service usage.

Identify trends and correlations in customer churn.

Clean, preprocess, and visualize the data to derive insights.

Treat missing values and outliers for better model and analysis accuracy.

Create visualizations to explore relationships and distributions across variables.

🛠️ Tools & Technologies Used:
Python

Pandas (for data manipulation)

NumPy (for numerical operations)

Matplotlib and Seaborn (for data visualization)

📂 Project Workflow:
1. Data Collection
Loaded telecom_customer_churn.csv using pandas.

Inspected the structure and types of data.

2. Data Cleaning & Preprocessing
Handled missing values for both numerical and categorical features.

Replaced missing values using:

Median for numerical fields like Avg Monthly Long Distance Charges, Avg Monthly GB Download.

Mode for categorical fields like Offer, Multiple Lines, etc.

Identified and capped outliers in features like:

Total Long Distance Charges

Total Revenue

Number of Referrals

3. Exploratory Data Analysis (EDA)
Generated descriptive statistics for all numerical and object-type columns.

Plotted:

Histograms for distributions.

Boxplots for outlier detection.

Scatter plots to analyze relationships with Avg Monthly GB Download.

Pie chart to visualize Total Extra Data Charges.

Heatmap to detect multicollinearity and strong correlations among numerical variables.

📈 Insights Gathered:
Majority of churners were influenced by dissatisfaction, competitors, or pricing.

Most customers were on month-to-month contracts, which had higher churn risk.

Services like Online Security, Streaming, and Device Protection Plan showed influence on revenue and churn.

Features like Tenure, Monthly Charges, and Total Revenue had strong correlations.

✅ Outcome:
A cleaned and analyzed dataset ready for further modeling (e.g., churn prediction), with business insights into customer behavior, churn causes, and possible retention strategies.

