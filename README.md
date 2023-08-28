# F&B_Service_Satisfaction_Rate_Insights_Using_Power-BI
Created Interactive Dashboard of Food & Beverages Services (Opportunity Analysis of a Major Food and Beverage services in United airlines)

# Dashboard

![customer comment](https://github.com/Ash-pixel10/redesigned-journey/assets/83878199/6dd4fa11-ab8a-4fd5-bcbd-6134080b9a3b)

# Project Objective

As United Airlines is on its journey to becoming the largest airline in the world, our focus continues to be on what our customers think of our products and service and ensuring they are taken care of in the friendly skies. As an analyst, you are required to leverage data to help in identifying opportunity areas in United’s current Food &Beverage(F&B) service and make recommendations which can help in increasing F&B (Food &Beverage) service satisfaction rate by identifying pain points for our customers and challenges in our current inventory planning.

# Background

Various studies suggest that airline F&B service has a significant impact on customer experience and loyalty generation. F&B is also one of the key concerns of unhappy customers as captured in their feedback forms. We have spent the last few years focusing on improving F&B service by partnering with global & regional vendors, encouraging customers to prebook their meals wherever applicable and improving forecasts for inventory. However, with constant network expansion plans and evolving demand, this continues to be an area of focus. Customers who pre-order their meals have a better satisfaction rate compared to those who do not. However, a small fraction of travelers prebook meals at this point.

Meal options can vary by market and haul type (Haul type is defined based on how long the flight is based on duration/miles). Some short haul markets (specially <500 miles) would not offer any meal-service which can be of concern specially for customers with multiple connections.

United uses a hub-and-spoke model to connect passengers between different cities. In a hub-and-spoke model, there is a central airport, called the hub, that serves as a connecting point for flights to and from other airports, called spokes. This helps in consolidating traffic from multiple spokes into the hub, and then flying larger aircraft on the hub-to-hub routes and can lead to lower operating costs for airlines. However, from the perspective of Inflight service, hub-spoke model can result in better customer experience on hub flights compared to spoke flights.

# Case Statement

United measures F&B satisfaction using our NPS (Net Promoter Score) survey. Customers are asked - How satisfied were you with the food & beverage served on your flight from [CITY] to [CITY]? Customers can score between 0-5 and can also provide additional feedback under - Is there anything else you would like to share about the food & beverage served on your flight from [CITY] to [CITY]?

% Inflight Satisfaction = Satisfied Sample/Total Sample*100

Satisfied Sample = Score is either 4 or 5 (Score ranges from 0-5)

# Deliverables

• Perform root cause analysis to identify    key drivers of F&B satisfaction score during summer months
• Use survey comments to understand major themes related to F&B that customers are complaining about
• Showcase your coding skills, write queries in SQL/Python/R to summarize data at different levels and draw meaningful conclusions
• Tell a story from the data and share some initial recommendations. What further deep dives would you like to do to gain better understanding of underlying issues?

# Process 

To tackle the challenge of increasing F&B service satisfaction for United Airlines, you can use Power BI to perform the analysis and create a presentation for your findings and recommendations. Here's a step-by-step guide on how to proceed:

Step 1: Data Import and Preparation in Power BI

1.1. Import the following datasets into Power BI:

Survey data for inflight satisfaction scores.
Survey data for customer comments/feedback.
Inflight service pre-order data.
Inflight service inventory data (only for Business/First Class).

1.2. Clean and preprocess the data within Power BI:

Handle missing values, outliers, and data inconsistencies.
Ensure data types are appropriate for analysis.

Step 2: Descriptive Analysis

2.1. Create visualizations to understand satisfaction scores:

Create a histogram to visualize the distribution of satisfaction scores.
Calculate summary statistics (mean, median, standard deviation) for satisfaction scores.

2.2. Identify key drivers of satisfaction:

Use visualizations like scatter plots or correlation matrices to identify relationships between variables (e.g., pre-order rate, inventory levels) and satisfaction scores.
Filter data to focus on the summer months and analyze satisfaction during this period.

Step 3: Customer Comments Analysis

3.1. Text analysis of customer comments:

Use Power BI's text analytics capabilities to perform sentiment analysis on customer comments.
Extract keywords and themes from comments using NLP techniques within Power BI.

3.2. Create visualizations to understand major themes:

Create word clouds or bar charts to visualize the frequency of themes mentioned in customer comments.

Step 4: Root Cause Analysis

4.1. Combine findings from satisfaction scores and customer comments to identify potential root causes of low satisfaction during summer months.

4.2. Use additional data such as pre-order and inventory data to correlate with satisfaction scores within Power BI.

Step 5: SQL/Python/R Queries (using Power Query in Power BI)

5.1. Write Power Query code to:

Summarize satisfaction scores by different attributes (e.g., route, class).
Calculate the percentage of satisfied customers during summer months.
Analyze pre-order and inventory data to identify any issues.





By using Power BI for our analysis and presentation, I have created interactive dashboards and reports that enable stakeholders to explore the data and gain a better understanding of the issues related to F&B service satisfaction. This approach combines data analysis and visualization to drive data-informed decision-making for United Airlines.
