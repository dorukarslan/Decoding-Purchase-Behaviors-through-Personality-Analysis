# Customer Essence: Decoding Purchase Behaviors through Personality Analysis

<p align="center">
  <img src="https://github.com/dorukarslan/Decoding-Purchase-Behaviors-through-Personality-Analysis/assets/79598598/8d3bb7c3-9ff4-4bc6-b6a3-246bcc6614b6" width="50%" height="50%">
</p>


- [Click here for the rendered document](https://dorukarslan.github.io/Decoding-Purchase-Behaviors-through-Personality-Analysis/)
- [Click here for the PDF document](https://github.com/dorukarslan/Decoding-Purchase-Behaviors-through-Personality-Analysis/blob/main/Customer-Essence.pdf)


  
## **Introduction**

This project aims to explore the Customer Personality Analysis dataset to reveal the relationship between customer features and their purchase behavior. The analysis investigates various aspects of customer demographics and behavior to understand how these factors influence spending patterns.

## **Objectives**

The primary goal of this analysis is to:

- Conduct Univariate Analysis on customer demographics such as age, marital status, education, etc.
- Analyze Multivariate relationships, focusing on how different factors like income, age, marital status, etc., relate to spending behaviors.
- Understand the impact of having children, education level, and campaign interactions on customer spending.

# Ask

• The project explores the relationship between various customer characteristics (like age, income, marital status, etc.) and their purchasing behavior, particularly focusing on how these attributes influence spending patterns across different product categories and channels.

• The problem is to identify key factors and patterns in customer data that can predict or explain spending behavior. This could involve understanding which demographic groups are more likely to spend on certain products, how marital status or the presence of children affects spending, or how effective marketing campaigns are in influencing purchases.

• Key metrics include total spending across product categories, frequency of purchases, responsiveness to marketing campaigns, and website engagement metrics. Additionally, demographic metrics like age group distributions, income levels, and family composition (kids at home, marital status) will be crucial.

Stakeholders include the marketing team, sales department, product development team, and senior management of the company for whom this analysis is being conducted. Each of these groups has a vested interest in understanding customer behavior to inform strategy, product offerings, and marketing campaigns.

# Prepare

**Data Source:**

[Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis/)    

   
The dataset is sourced from Kaggle, contributed by Dr. Omar Romero-Hernandez. It comprises detailed customer profiles including demographic information, product spending, promotion responses, and purchase methods, structured across several categories. The main focus of analysis will be on these key areas:

- **People Content:** Includes customer ID, birth year, education, marital status, income, number of children and teenagers in the household, date of enrollment with the company, recency of purchase, and complaint history.
- **Product Spending:** Details the amount spent on wines, fruits, meat, fish, sweets, and gold products in the last two years.
- **Promotion Responses:** Captures data on the number of purchases made with a discount, and responses to various marketing campaigns.
- **Purchase Places:** Includes the number of purchases made through the web, catalog, and in stores, along with monthly web visits.

**Data Limitations:**

While the dataset provides a comprehensive view of customer behavior and preferences, it may not represent the broader market due to its specific data collection methods and customer base. Additionally, the data might be limited by the time frame it covers, potentially not reflecting current market trends or recent changes in consumer behavior.

**Data Credibility:**

The credibility of the data is assessed based on the ROCCC criteria:

- **Reliability:** The dataset, coming from a reputable academic source, is reliable for the analysis of customer behavior and spending patterns.
- **Original:** Sourced directly from Kaggle, ensuring the data's originality without third-party alterations.
- **Comprehensive:** Offers a broad view of customer demographics, spending habits, and responses to marketing activities.
- **Current:** While reasonably recent, the exact time frame of the data collection should be considered to assess its current relevance.
- **Cited:** Properly sourced and credited to its original contributor, maintaining academic and research integrity.

# Process

In this stage, we focus on tool selection, data integrity, cleaning, and preparation for analysis.

### **Tool Selection:**

For this analysis, I chose the following tools, primarily for their specific strengths:

- **R Language**: Ideal for statistical analysis and data manipulation.
- **Tidyverse Package**: Provides a cohesive set of functions for data manipulation.
- **Lubridate Package**: Simplifies handling date-time data.
- **Cluster Package**: Useful for cluster analysis.
- **KableExtra Package**: Enhances the presentation of tables in the output document.

### **Ensuring Data's Integrity:**

- **Data Verification**: Checked consistency and accuracy of data fields.
- **Handling Missing Data**: Missing values were identified and handled appropriately, especially in key columns like 'Income'.
- **Duplicate Records Analysis**: Duplicate entries were identified and analyzed to avoid skewed results.

### **Data Cleaning Steps:**

1. **Missing Data Analysis**: Calculated and visualized the percentage of missing values to identify which columns required attention.
2. **Income Data Handling**: Replaced missing values in the 'Income' column with the median of non-NA values to maintain data integrity.
3. **Duplicate Record Handling**: Identified and removed any duplicate entries to ensure data accuracy.

### **Verification of Clean Data:**

- **Data Overview**: Post-cleaning, an overview of the data was conducted to confirm the structure and key fields.
- **Numeric Summary**: A summary of numeric attributes was provided to understand the distribution and range of values.
- **Data Visualization**: Utilized boxplots and bar plots for visual inspection, particularly in understanding the age distribution of customers.

# Analyze

In the Analyze phase of our analysis, we focused on organizing, formatting, and deriving insights from the data. We explored various aspects of customer demographics and behaviors, uncovering surprising trends and relationships that provide answers to our business questions.

1. **Demographics:** The customer base is mature (median age 53) and well-educated, with a majority in relationships, indicating a focus on middle-aged adults and family-oriented products.
2. **Spending Habits:** Customers prefer quality products, notably wines and meats, with a strong middle-class presence (income $40,000 - $80,000) suggesting a market for affordable yet quality products.
3. **Purchasing Behavior:**
    - Families with children tend to have targeted child-centric marketing opportunities.
    - Single customers, with slightly higher spendings, indicate more disposable income.
    - Childless customers exhibit higher discretionary spending.
4. **Marketing and Campaigns:** Low campaign acceptance rates point to a need for more effective marketing strategies. Engaged customers spend more, underscoring targeted campaigns' success.
5. **Purchasing Channels:** Store purchases dominate, but a significant online presence shows the need for a dual retail approach. Older customers and childless individuals are more inclined toward online shopping.
6. **Online Engagement:** Higher web activity is associated with lower spending, suggesting a more deal-savvy customer segment.
7. **Customer Satisfaction and Spending:** Non-complainers tend to spend more, linking satisfaction with higher spending. However, the relationship between recency of purchase and expenses shows no clear pattern, hinting at sporadic purchasing behaviors.

**Surprises and Trends:**

- The higher engagement of single customers in certain spending categories was unexpected, suggesting they may have more disposable income.
- The significant online shopping activity among older customers was a notable discovery, challenging stereotypes about this demographic's shopping preferences.

The analysis reveals a customer base that is mature, educated, and family-oriented, with a preference for quality products. Responsiveness to marketing campaigns and customer satisfaction are crucial in influencing spending, while web engagement and family structure show varied impacts on purchase behaviors. These insights are invaluable for developing tailored marketing strategies and product offerings.

**Impact of Insights:**

These insights help tailor marketing strategies and product development to match the preferences and behaviors of different customer segments. Understanding the nuances in customer profiles enables us to target communications more effectively and optimize our product offerings. For a comprehensive understanding, detailed visualizations and methodologies are available in the accompanying HTML document generated from our R project analysis.


# Act

The Act phase is the culmination of our analysis, where we leverage the insights gained to inform decisions and propose additional actions. Based on our comprehensive study of the Customer Personality Analysis dataset, here are the top high-level insights and recommendations for further exploration:

**Top High-Level Insights:**

1. **Targeted Marketing for Mature Customers:** Focus on middle-aged and senior adults, tailoring products and services to their preferences, particularly in quality wines and meats.
2. **Family-Oriented Product Strategies:** Given the majority of customers are in relationships and have children, develop family-centric marketing campaigns and product packages.
3. **Enhanced Campaigns for Engagement:** Redesign marketing campaigns to increase engagement, focusing on the segments that showed higher responsiveness.
4. **Online and Store Dual Strategy:** Strengthen both online and in-store shopping experiences, catering to the preferences of both older and younger customer segments.
5. **Customer Satisfaction and Retention:** Emphasize on customer satisfaction, as it correlates with higher spending. Develop strategies to reduce complaints and enhance customer experience.

**Additional Deliverables for Further Exploration:**

1. **Longitudinal Spending Analysis:** Examine customer spending over time to understand trends and predict future purchasing behaviors.
2. **Marketing Campaign Effectiveness Analysis:** Detailed analysis of past marketing campaigns to identify what works and what doesn't, helping to refine future marketing strategies.
3. **Product Preference and Feedback Surveys:** Conduct surveys to gather direct customer feedback on product preferences, satisfaction levels, and areas for improvement.
4. **Social Media Sentiment Analysis:** Analyze customer sentiment and trends on social media platforms to gauge brand perception and identify potential areas for improvement in customer engagement.
