
# Content Popularity Analysis - Accenture Data Science Project

## Project Overview

This project focuses on analyzing the popularity of content categories for a client, as part of the Accenture Data Science Job Simulation. The primary goal was to identify the top 5 content categories based on popularity, clean and merge the necessary datasets, and visualize key insights to support the client's strategic decisions.

## Objectives

- **Data Preparation**: Clean and merge multiple datasets to prepare them for analysis.
- **Top Categories Analysis**: Identify the top 5 content categories with the highest popularity based on reaction scores.
- **Data Visualization**: Create visualizations to present the findings, including category popularity, unique categories, and content posting trends.

## Datasets Used

- **Reactions Dataset**: Contains information about user reactions to content.
- **Content Dataset**: Contains metadata about content, including content ID and category.
- **Reaction Types Dataset**: Defines the types of reactions and associated scores.

## Key Steps

1. **Data Cleaning**:
   - Removed unnecessary columns and handled missing values.
   - Ensured data consistency by dropping irrelevant columns.

2. **Data Merging**:
   - Merged the reactions and content datasets based on `Content ID`.
   - Further merged with reaction types to associate reaction scores with each content category.

3. **Top 5 Categories Analysis**:
   - Grouped data by content category and summed the reaction scores.
   - Identified the top 5 categories with the highest total scores.

4. **Data Visualization**:
   - Created bar charts to visualize the number of reactions to the top categories.
   - Displayed the unique number of categories and reactions to the most popular category.
   - Visualized posting trends by month to identify peaks in content activity.

## Key Findings

- **Top 5 Content Categories**: The analysis identified the top 5 content categories with the highest popularity based on aggregated reaction scores.
- **Most Popular Category**: The category "animals" received the highest number of reactions, making it the most popular.
- **Monthly Trends**: January 2021 had the highest number of content posts, suggesting a period of increased user engagement.

## Visualizations

- **Unique Categories**: A summary visualization showing the number of unique categories in the dataset.
- **Reactions to Most Popular Category**: A bar chart showing the number of reactions to the top content categories.
- **Monthly Posts**: A line chart illustrating the number of posts per month, highlighting the month with the most activity.

## Conclusion

This project successfully identified the most popular content categories and provided actionable insights for the client. The visualizations created offer a clear and concise view of content performance, enabling the client to make informed decisions regarding content strategy.



## Acknowledgments

This project was completed as part of the Accenture Data Science Job Simulation, demonstrating practical data analysis and visualization skills.

