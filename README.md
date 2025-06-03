# Customer Churn Analysis

This project explores customer churn behavior using a telecom dataset. The goal is to identify key factors influencing customer churn and support business decisions to improve retention.

## Objective

To analyze customer churn patterns using exploratory data analysis (EDA) and visualization techniques. The goal is to uncover trends and relationships between service features and churn, 
enabling data-driven retention strategies.

## Tools Used

- Python 
- Pandas
- Seaborn & Matplotlib for visualization
- Jupyter Notebook

## Key Features

- Loaded and cleaned telecom customer data.
- Conducted univariate and bivariate analysis on service features.
- Visualized churn patterns across different service categories.
- Used stacked bar charts and countplots to compare churn rates.
- Annotated plots with actual values and percentages for better readability.

## Key Insights

- Internet Service Impact:
      - Customers using **Fiber optic** internet have a significantly higher churn rate compared to those using DSL.
      - Those with no internet service show very low churn, likely because they are less engaged or use fewer services.
- Optional Add-on Services Reduce Churn:
      - Features such as **OnlineSecurity**, **OnlineBackup**, **DeviceProtection**, and **TechSupport*** correlate with lower churn when subscribed to.
      - Customers who do not use these services or have "No internet service" in these fields generally churn less, indicating disengaged or legacy users.
- Streaming Services and Churn:
      - Users who subscribe to **StreamingTV** and **StreamingMovies** are more likely to churn than those who do not.
      - However, the churn rate difference is less stark than in other service categories.
- Senior Citizens and Churn:
      - **Senior citizens** are more likely to churn than younger customers.
      - This group may need targeted engagement strategies to reduce attrition.
- Multiple Lines and Phone Service:
      - Customers with **Multiple Lines** or **Phone Service** have a mixed churn pattern, showing that these features alone are not strong churn predictors.

