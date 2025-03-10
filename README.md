# Power BI Insurance Data Analysis Project

## Project Overview
This project involves the development of a **Power BI dashboard** for **Altimate Insurance Ltd.** to analyze and visualize key metrics related to insurance policies, claims, customer data, and **customer feedback sentiment analysis**. The dashboard provides insights into premium collections, claim distributions, policy types, customer demographics, and customer satisfaction, enabling stakeholders to make data-driven decisions.

---

## Key Tasks and Features

### 1. Data Loading and Preparation
- Connected to **SQL Server** to load insurance data directly into Power BI.
- Extracted data from multiple tables, including policy details, claim records, customer information, and **customer feedback data**.
- Cleaned and preprocessed the data to handle missing values, duplicates, and inconsistencies.

### 2. Data Modeling
- Established relationships between tables (e.g., policies, claims, customers, and feedback) to enable comprehensive analysis.
- Created calculated columns and measures using **DAX (Data Analysis Expressions)** to derive key metrics.
- Integrated **sentiment analysis** to categorize customer feedback into positive, neutral, and negative sentiments.

### 3. Dashboard Development
- Designed an interactive Power BI dashboard with the following features:
  - **Policy Overview**: Analysis of all policies, including active and inactive statuses.
  - **Claim Analysis**: Breakdown of claims by status (e.g., settled, pending) and policy type.
  - **Premium Analysis**: Visualization of premium amounts collected by different policy types (e.g., travel, health, auto, life, home).
  - **Customer Demographics**: Analysis of claims and policies by age groups (e.g., young adults, adults, elderly).
  - **Customer Feedback Analysis**:
    - **Word Cloud**: Highlights keywords from customer feedback, such as "satisfied," "service," "claim," "policy," "process," "premium," "helpful," and "happy."
    - **Customer Feedback Table**: Lists customer names, satisfaction ratings, and corresponding feedback.
    - **Satisfaction Rating Summary**:
      - **Excellent**
      - **Good**:
      - **Need Improvement**
    - **Common Feedback Trends**:
      - **Positive Comments (Excellent Ratings)**:
        - Fast claim processing.
        - Easy policy management.
        - Good customer service and staff professionalism.
        - Affordable premiums.
        - Clear coverage details.
      - **Neutral to Negative Feedback (Good & Need Improvement Ratings)**:
        - Delays in claim processing.
        - Lack of clarity in policy terms.
        - Difficulty in reaching customer support.

### 4. Visualizations
- Created various visualizations, including:
  - **Bar charts** and **pie charts** for policy and claim distributions.
  - **Tables** for detailed breakdowns of claims by policy type and status.
  - **Word Cloud**: Visual representation of frequently used keywords in customer feedback.
  - **Satisfaction Rating Charts**: Pie charts or bar charts showing the distribution of satisfaction ratings (Excellent, Good, Need Improvement).
  - **Filters** to allow users to drill down into specific segments (e.g., by policy type, age group, or satisfaction rating).

### 5. Insights and Reporting
- Provided actionable insights into:
  - The distribution of policies and claims across different categories.
  - Trends in premium collections and claim payouts.
  - The proportion of active vs. inactive policies.
  - **Customer satisfaction trends** based on feedback sentiment and ratings.
  - Common themes in customer feedback to identify areas for improvement and strengths to maintain.
- Enabled stakeholders to monitor financial performance, identify areas for improvement, and enhance customer experience.

---

## Technologies Used
- **SQL Server**: For storing and managing insurance data and customer feedback.
- **Power BI**: For data visualization and dashboard development.
- **DAX (Data Analysis Expressions)**: For creating calculated columns and measures.
- **SQL**: For querying and extracting data from SQL Server.
- **Sentiment Analysis Tools**: For analyzing and categorizing customer feedback (e.g., Python, Azure Text Analytics, or Power BI's built-in AI capabilities).

---

## How to Use
1. Clone the repository to your local machine.
2. Open the Power BI file included in the repository.
3. Ensure you have access to the SQL Server database or update the connection to your local SQL Server instance.
4. Explore the interactive dashboard to analyze insurance data and customer feedback sentiment.
5. Use filters and slicers to drill down into specific segments (e.g., by policy type, age group, or satisfaction rating).



---

## Screenshots

![Screenshot demo1](https://github.com/Mutiu123/Insurance-Data-Analysis-Using-Power-BI/blob/main/demo/demo.jpg)

## Female Only Filter

![Female Only demo1](https://github.com/Mutiu123/Insurance-Data-Analysis-Using-Power-BI/blob/main/demo/Female%20only%20filter.jpg)

## Health Insurance Filter

![Health Insurance demo1](https://github.com/Mutiu123/Insurance-Data-Analysis-Using-Power-BI/blob/main/demo/Health%20Insurance.jpg)

## Published Customer Feedback

![Published Customer Feedback](https://github.com/Mutiu123/Insurance-Data-Analysis-Using-Power-BI/blob/main/demo/Published%20Customer%20Feedback.jpg)

## Filtered Published Customer Feedback

![Filtered Published Customer Feedback](https://github.com/Mutiu123/Insurance-Data-Analysis-Using-Power-BI/blob/main/demo/Filtered%20Published%20Customer%20Feedback.jpg)