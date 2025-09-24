**Project Name** - **Flipkart Customer Support Data Analysis**

**Project Summary**  

Flipkart Customer Support Data Analysis
This project aimed to perform an exploratory data analysis (EDA) on the Flipkart customer support dataset to identify factors that influence customer satisfaction, with the ultimate goal of improving support strategies and optimizing agent performance.

The project was executed in a series of steps:

Data Cleaning and Preparation: The raw dataset was cleaned by handling missing values through dropping non-critical columns and imputing remaining missing data with the mode. Data types were also corrected, converting price and time-related columns to a suitable numerical or datetime format.

Exploratory Data Analysis (EDA): Key trends and insights were uncovered through data visualization. The analysis revealed that:

The majority of customers provided a high CSAT score of 5, indicating generally high satisfaction.
The most frequent customer issues were 'Order Related' and 'Product Queries'.
The Morning shift handles the highest volume of inquiries, and a significant portion of agents have a tenure of more than 90 days, suggesting an experienced workforce.
While most issues are resolved quickly, there is no strong correlation between call handling time and the CSAT score.
Machine Learning Model: A RandomForestClassifier was trained to predict customer satisfaction (CSAT Score) based on the cleaned data.

New features, such as the day of the week and time of day, were engineered from the timestamp data.
The model achieved a high accuracy of 0.95, demonstrating its effectiveness in predicting customer satisfaction outcomes, particularly for the most frequent scores.
The findings provide actionable insights that can help Flipkart improve its customer support by focusing on the most common issues and tailoring strategies to meet customer expectations, which can ultimately lead to increased brand loyalty and customer retention.

**Problem Statement**

The core problem statement for this project is to understand the factors influencing customer satisfaction at Flipkart by analyzing a customer support dataset. By performing exploratory data analysis and building a predictive machine learning model, the project aims to identify key trends and patterns that can help Flipkart improve its customer support strategies, leading to:

Faster issue resolution.
More tailored support for diverse customer needs.
Optimization of service agent performance.
Improved satisfaction metrics like the CSAT score.
Ultimately, increased brand loyalty and customer retention.

**Conclusion**

The exploratory data analysis of the Flipkart dataset successfully achieved its primary goal of identifying the key factors that influence customer satisfaction. By visualizing trends and patterns, the project provides a data-driven foundation for strategic decision-making to improve customer experience and optimize agent performance.

The project concludes that customer satisfaction, as measured by the CSAT score, is not a random metric but is significantly influenced by three main categories of factors:

Service Metrics: There is a clear relationship between efficiency and satisfaction. The scatter plots and pair plot confirm that longer response times and connected handling times are associated with a decrease in CSAT scores. This highlights the critical need for a streamlined, efficient service process.

Agent Expertise and Experience: The heatmap is a powerful tool in this regard, revealing that newer agents ("On Job Training" and "1-3 months") have lower CSAT scores for specific issue categories. This indicates that providing targeted training to new hires on these particular topics could significantly boost customer satisfaction and agent performance from the start.

Issue and Product Specifics: The analysis reveals that certain issue categories and product types consistently have lower average CSAT scores. This points to systemic problems that require a more in-depth, root-cause analysis beyond a single agent's performance.

In summary, the project provides a clear roadmap for Flipkart to move forward. The recommendation is to shift from a reactive support model to a proactive, data-informed one. By using these insights to implement targeted training programs, optimize call routing, and address specific product-related issues, Flipkart can effectively improve its support strategies, leading to higher CSAT scores, increased customer loyalty, and ultimately, greater brand retention.
