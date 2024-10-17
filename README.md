# Churn-Analysis

Predicting customer churn is essential for sustainable revenue growth. It’s usually much more expensive to acquire new customers than to retain existing ones. Plus, when customers stick around longer, they tend to spend more, which increases their lifetime value. This also gives companies the chance to gather valuable data that can be used for targeted marketing and cross-selling, ultimately maximizing revenue.

In this notebook, we’ll:

1. **Explore the Customer Dataset**: We’ll dive deep to uncover behavioral patterns and trends associated with churn.
2. **Build a Predictive Model**: This model will help us identify at-risk customers, enabling the company to take proactive, targeted actions to improve customer retention, reduce churn, and support long-term growth.

## Outline

This project is broken down into 5 steps:

1. Import Dependencies
2. Load and Prepare the Data
3. Exploratory Data Analysis (EDA)
4. Preparing Pre-Processing Pipeline
5. Build and Evaluate the Model

## Data Description

| Column Name | Description |
|----|----|
| **CustomerID** | Unique customer ID |
| **Churn** | Churn Flag |
| **Tenure** | Tenure of customer in organization  |
| **PreferredLoginDevice** | Preferred login device of customer |
| **CityTier** | City tier |
| **WarehouseToHome**| Distance in between warehouse to home of customer |
| **PreferredPaymentMode** | Preferred payment method of customer |
| **Gender** | Gender of customer |
| **HourSpendOnApp** | Number of hours spend on mobile application or website |
| **NumberOfDeviceRegistered** | Total number of deceives is registered on particular customer |
| **PreferedOrderCat** | Preferred order category of customer in last month |
| **SatisfactionScore** | Satisfactory score of customer on service |
| **MaritalStatus** | Marital status of customer |
| **NumberOfAddress** | Total number of added added on particular customer |
| **Complain** | Any complaint has been raised in last month |
| **OrderAmountHikeFromlastYear** | Percentage increases in order from last year |
| **CouponUsed** | Total number of coupon has been used in last month |
| **OrderCount** | Total number of orders has been places in last month |
| **DaySinceLastOrder** | Day Since last order by customer |
| **CashbackAmount** | Average cashback in last month |


As shown from the records above dataset includes a range of features from customer demographics to their purchasing behaviors. Key attributes include:

- Customer Demographics: Gender, City Tier, Marital Status.
- Shopping Preferences: Preferred Login Device, Preferred Payment Mode, Preferred Order Categories.
- Engagement Metrics: Hours Spent on App, Number of Devices Registered, Satisfaction Score.
- Transactional Behavior: Order Amount Hike from Last Year, Number of Addresses, Frequency of Coupon Usage
