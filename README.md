# BUSINESS-ANALYSIS-ON-WZ_SHOPPING-MALL
# BUSINESS ANALYTICAL PROBLEM SOLVED FOR WZ SHOPPING MALL USING THEIR BUSINESS DATA.
# CUSTOMER, PURCHASE, AND CAMPAIGN DATA ANALYSIS REPORT

## INTRODUCTION
In this project, I performed an in-depth analysis of customer, purchase, and campaign data to uncover actionable business insights. The analysis encompassed data cleaning, exploratory data analysis (EDA), customer segmentation, churn prediction, and sales forecasting. The aim was to leverage data to drive informed decision-making and improve business strategies.

## DATA IMPORT AND PREPROCESSING
I imported the following datasets:
1. Customers Data (`customers.xlsx`): Contains information about customer IDs, sign-up dates, and churn status.
2. Purchases Data (`purchases.xlsx`): Includes data on purchase dates, amounts, and associated campaigns.
3. Products Data (`products.xlsx`): Details about product IDs, categories, and prices.
4. Campaign Performance Data (`campaign_performance.xlsx`): Metrics such as ROI, CAC, customer retention, and campaign reach.

After importing the data, I checked for and handled any missing values and duplicates. I also converted date columns to datetime format for better analysis.

## EXPLORATORY DATA ANALYSIS (EDA)
1. Distribution of Purchase Amounts: 
   - I plotted the distribution of purchase amounts to understand the spending behavior of customers.
2. Purchases Over Time:
   - I visualized the number of purchases over time to identify trends and patterns in purchasing behavior.
3. Churn Rate Calculation:
   - I calculated the churn rate, which is a critical metric for understanding customer retention.

## CUSTOMER PREDICTION
To segment the customers, I aggregated purchase data by customer and performed the following steps:
1. Data Aggregation:
   - Aggregated total spending, average spending, and purchase count for each customer.
2. Data Standardization:
   - Standardized the aggregated data to ensure each feature contributes equally to the clustering algorithm.
3. K-Means Clustering:
   - Applied K-Means clustering to segment customers into distinct groups based on their purchasing behavior.
   - Visualized the customer segments using pair plots.

## CHURN PREDICTION
I built two models to predict customer churn: Random Forest and K-Nearest Neighbors (KNN).

1. Random Forest Model:
   - Prepared the data by selecting relevant features and splitting it into training and test sets.
   - Trained the Random Forest model and evaluated its performance.
   - Achieved an accuracy of 75% with a precision of 0.83 and recall of 0.87 for non-churned customers.

2. K-Nearest Neighbors (KNN) Model:
   - Similarly prepared the data and trained the KNN model.
   - Evaluated the model, achieving an accuracy of 79% with a precision of 0.82 and recall of 0.94 for non-churned customers.

## CAMPAIGN PERFORMANCE ANALYSIS
I analyzed the performance of various marketing campaigns by calculating key metrics and visualizing the results.

1. Calculation of Metrics:
   - Calculated the average purchase amount, ROI, CAC, customer retention, and campaign reach for each campaign.
2. Visualization:
   - Created bar plots to compare the performance of different campaigns across these metrics.

## SALES FORECASTING
I performed sales forecasting using the Exponential Smoothing method to predict future sales trends.

1. Monthly Sales Aggregation:
   - Aggregated monthly sales data to ensure I had at least 24 months of data.
2. Model Fitting:
   - Fitted the Exponential Smoothing model to the historical sales data.
3. Sales Forecasting:
   - Forecasted sales for the next 12 months and visualized the results alongside the observed sales.

## CONCLUSION
This comprehensive analysis provided valuable insights into customer behavior, campaign performance, and future sales trends. By leveraging advanced machine learning techniques and time series modeling, I was able to derive actionable insights to drive data-informed decision-making. These insights can help in optimizing marketing strategies, improving customer retention, and better forecasting future sales.

## FUTURE WORK
Future work could involve:
1. Enhancing the churn prediction model by incorporating more features and trying different algorithms.
2. Conducting A/B testing to validate the impact of different marketing campaigns.
3. Expanding the forecasting model to include external factors such as seasonality and market trends.
   
