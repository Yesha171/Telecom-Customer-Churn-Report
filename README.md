# Telecom-Customer-Churn-Report

## Problem Statement

Customer churn, or the rate at which customers discontinue their service, is a significant challenge for telecommunications companies. Retaining existing customers is often more cost-effective than acquiring new ones. Understanding why customers churn and identifying at-risk customers is crucial for implementing effective retention strategies. This project aims to analyze customer data to identify patterns and factors associated with churn and provide actionable insights.

## Overview

This report analyzes a dataset of telecom customer information, including demographic details, service subscriptions, usage patterns, and contract details.  The primary objective is to understand the drivers of customer churn and build a model to identify at-risk customers. The analysis uses Power BI to visualize the data and highlight churn patterns. 

The dataset includes factors like:

*   **Customer Profile:** Information about total customers, senior citizens, their monthly and total charges, gender, tenure and phone, internet and tech support
*  **Churner Profile:** Information about the customers who left, senior citizens, their monthly and total charges, gender, tenure and phone, internet and tech support
*   **Customer Details:** Specifics about a chosen customer including personal information, tenure in the company, phone services, contract details and churn risk index
*   **Churn Reasons:** Aggregated data about the number of customers in different risk categories and average total charges based on risk category

## Key Findings

Based on the data analysis, here are the most important insights:

*   **Churn Rate:**  A considerable number of customers have churned (1869 customers).  The average monthly charge for churned customers was 74 compared to the overall average of 64.76.
*   **Senior Citizen Churn:** A smaller number of Senior Citizen have churned (476), compared to the total amount of senior citizens (1142)
*   **Tenure Impact:** The majority of churn occurs within the first 20 months of a customer's tenure (1251 churners), suggesting a need to focus on early customer engagement.
*   **Contract Type:** Customers with month-to-month contracts have a higher churn rate compared to those with longer-term contracts.
*   **Risk Identification:** We have identified different levels of churn risk from 'Non Risky', 'Low Risky', 'Risky' and 'High Risky', which will allow for targeted intervention to reduce churn. The average total charges of these risk categories range from 0.3M to 10.1M.

## Conclusion

This analysis highlights critical areas that contribute to customer churn. Key factors include:
   * Short-term contracts
   * Low customer engagement in early months
   * High monthly rates.

By understanding these drivers, the company can focus its resources on at-risk customers, offer incentives for long-term contracts, and work to improve customer satisfaction to reduce churn.

## Visualizations

*   **CUSTOMER CHURN ANALYSIS:** This dashboard provides a comprehensive overview of the customer base and churned customer base. It compares demographic and service related characteristics.

*   **CUSTOMER DETAILS:** This interactive dashboard allows users to examine individual customer data, including demographics, service subscriptions, churn risk, and specific contract information.

*   **CHURN REASONS:** This visualization aggregates all the customers with a risk of churn, grouping them into levels and analysing average total charges based on the risk levels.

*   **Ask a Question** This section allows the user to ask and get any relevant information about the data that they want.

## Recommendations

Based on the analysis, here are some suggestions for actions that could be taken:

1.  **Enhance early customer engagement:** Focus on strategies to keep new customers engaged in the first few months, such as introductory offers, onboarding services, and proactive communication.
2.  **Incentivize longer-term contracts:** Offer discounts, value-added services, and other benefits to incentivize customers to choose longer-term contracts, which can improve retention.
3.  **Address pricing concerns:** Review and potentially adjust pricing structures to remain competitive and improve customer satisfaction.
4.  **Target high-risk customers:** Implement targeted retention efforts (like personalized offers and engagement programs) for customers identified as high-risk.
5.  **Continuous monitoring:** Continuously monitor customer metrics to understand the effectiveness of retention efforts and implement improvements.
