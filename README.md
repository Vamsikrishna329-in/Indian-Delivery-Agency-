# Indian-Delivery-Agency
The last minute delivery and fast delivery agency which delivery the from fresh fruit and vegetables to electronic items with in minutes in the major cities and towns.
# Executive Summary
This project analyzes a dataset of 5,000 customer reviews and transaction records for quick-commerce delivery platforms (e.g., Zepto, JioMart, Blinkit, Swiggy Instamart). The analysis evaluates critical operational metrics, including delivery times, customer ratings, order types, and geographical performance. A key finding is that a significant portion of deliveries (58.5%) exceeded the 30-minute mark, a crucial threshold in the quick-commerce industry. Additionally, over half of the customer base utilized discounts. By surfacing these trends, the analysis provides a foundation for optimizing delivery logistics and enhancing customer satisfaction.
# Business Problem
In the highly competitive quick-commerce sector, companies differentiate themselves through rapid delivery and reliable service. The core business challenges addressed in this analysis include:
Delivery Bottlenecks: Identifying how often and where delivery times exceed acceptable thresholds (e.g., >30 minutes), which directly impacts customer retention.
Resource Allocation: Understanding order volume distribution across different cities and categories (Essentials, Pharmacy, Grocery, etc.) to optimize driver deployment and inventory.
Performance Monitoring: Benchmarking delivery agents against one another to identify training needs or routing inefficiencies.
Discount Strategy: Evaluating the frequency of discount usage to understand customer price sensitivity and promotional effectiveness.
# Business Development
Insights from this data can be leveraged to drive strategic growth and operational efficiency:
Targeted Logistics Improvements: By isolating the cities and order types with the highest average delivery times, the business can deploy hyper-local micro-fulfillment centers or increase delivery fleet density in underperforming areas.
Customer Retention Strategies: Since over 50% of orders use discounts, the business can design targeted loyalty programs rather than relying solely on flat discounts, protecting profit margins while maintaining order volume.
Service Standardization: By evaluating average ratings and customer service scores across different agents, the company can standardize training for underperforming agents to improve overall order accuracy and customer feedback.
# Methodology
The analysis was conducted using a Python-based data science stack, following these steps:
Data Ingestion & Inspection: Loaded the 5,000-row dataset using Pandas and examined data types, memory usage, and structural integrity using .info() and .head().
Data Cleaning: Checked for missing values and standardized the dataset by replacing any nulls with zeroes (fillna(0)).
Data Filtering & Subsetting: Created targeted dataframes to analyze specific operational concerns, such as isolating deliveries taking longer than 30 minutes and filtering for transactions where discounts were applied.
Exploratory Data Analysis & Visualization: Utilized Matplotlib and Seaborn to generate statistical visualizations. Generated bar charts and box plots to analyze review counts, average ratings, order distributions, and delivery time variances across cities and product categories.
# Skills Demonstrated
Programming: Python
Data Manipulation: Pandas (filtering, grouping, aggregating, handling missing values)
Data Visualization: Matplotlib, Seaborn (Bar charts, Box plots for distribution analysis)
Exploratory Data Analysis (EDA): Identifying central tendencies, variance, and segmenting data by categorical variables (City, Agent Name, Order Type).
# Results
Based on the data processing and filtering, the analysis yielded the following operational results:
Total Volume: The dataset successfully processed 5,000 distinct delivery orders across multiple major Indian cities (e.g., Delhi, Lucknow, Ahmedabad, Chennai, Pune).
Delayed Deliveries: 2,926 orders (58.52% of total volume) took longer than 30 minutes to deliver, indicating a significant operational gap in the "quick commerce" promise.
Promotional Dependency: 2,537 orders (50.74%) were completed with a discount applied, highlighting a highly price-sensitive customer base.
Visual Insights Generated: The graphical outputs mapped key performance indicators, successfully identifying:
Which delivery agents command the highest review volumes and average ratings.
The most popular order types and the cities driving the highest order volumes.
The distribution and outliers in delivery times across different geographical locations, clearly mapped via box plots to pinpoint regional logistical strengths and weaknesses.
