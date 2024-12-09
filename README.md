Comparative Analysis of Airbnb Listings: Visualization and Insights Using Tableau and Power BI
Student’s Name
Shreya Jamsandekar
Introduction
Importance of the Topic:
The rise of platforms such as Airbnb has revolutionized the short-term rental industry by allowing property owners to connect with travelers. This model has provided alternative accommodations to traditional hotels, contributing to the hospitality industry's significant growth. In a city like New York, with its high tourist influx and limited hotel space, Airbnb has become a prominent player.

Analyzing Airbnb listings helps uncover patterns that can provide useful insights for various stakeholders. Hosts benefit by identifying factors that influence the pricing and demand of their properties, enabling them to maximize revenue. Investors can assess market trends to guide property investments, and policymakers can use such analyses to regulate short-term rentals effectively. By understanding the dynamics of Airbnb listings, pricing strategies, guest satisfaction, and room availability, stakeholders can make data-driven decisions.
Importance of Data Visualization:
In an era where data is abundant, visualizing information is crucial for deriving insights. Tools like Tableau and Power BI play a vital role in this process, allowing users to visualize complex datasets and identify trends or outliers quickly. These platforms empower both technical and non-technical users to explore datasets interactively, fostering a better understanding of the data.

Visualizations, when used correctly, simplify complex data, highlight relationships between variables, and support decision-making processes. For Airbnb listings, these visualizations can reveal patterns such as seasonal pricing fluctuations, correlations between reviews and ratings, and neighborhood-based pricing trends. With interactive dashboards, users can filter data in real time, making tools like Tableau and Power BI indispensable in the realm of data analysis.
Dataset
Dataset Description:
The dataset used for this analysis includes detailed information on Airbnb listings in New York City for 2024. The data comprises various features, including property types, prices, ratings, room availability, and reviews. These features make it possible to explore diverse aspects of the short-term rental market and understand factors that drive success on Airbnb. For instance, the dataset can highlight how room type influences pricing, how the number of reviews impacts guest ratings, and how availability fluctuates throughout the year.
Table of Field Names and Descriptions:
Field Name	Description	Descriptive Statistics (example)
id	Unique identifier for each listing	n/a
name	Name of the listing	n/a
host_id	Unique identifier for each host	n/a
neighbourhood_group	The borough where the listing is located	Manhattan (50%), Brooklyn (35%), etc.
price	Price of the listing per night (USD)	Mean: $150, Median: $120, Min: $50, Max: $1000
rating	Average rating of the listing	Mean: 4.3, Min: 1.0, Max: 5.0
number_of_reviews	Total number of reviews for the listing	Mean: 20, Max: 500
room_type	Type of room (Private, Entire home, etc.)	Private (50%), Entire home (45%), etc.
availability_365	Number of available days in the year	Mean: 120, Max: 365
Data Source:
The dataset for this analysis was sourced from Kaggle's repository of Airbnb listings. You can access the dataset via this link: [Kaggle Airbnb Dataset](https://www.kaggle.com/datasets).
Analytical Questions
The analysis of Airbnb listings revolves around key questions that help in uncovering important insights. For this project, five analytical questions have been considered:
1. What factors contribute the most to Airbnb pricing in New York City?
2. Is there a seasonal or monthly trend in Airbnb pricing and availability?
3. Do certain neighborhoods have higher average ratings or reviews?
4. How does the room type affect the pricing of Airbnb listings?
5. What is the relationship between the number of reviews and the average rating of listing?


 
The Power BI dashboard provides a comprehensive visual analysis of Airbnb listings across various dimensions such as neighborhood, room type, price, and availability. The dashboard is interactive, with several key visualizations to explore the dataset dynamically.
•	Treemap of Room Type Prices Across Neighborhoods:
This treemap visually represents the relationship between room types and neighborhoods in terms of pricing. The different room types, such as Entire Home/Apt, Private Room, Hotel Room, and Shared Room, are categorized by color. The size of each block corresponds to the number of listings in a particular neighborhood, providing an intuitive view of how room types dominate different areas. Manhattan and Brooklyn dominate the Entire Home/Apt and Private Room categories, reflecting their popularity among Airbnb listings.
•	Bar Chart of Ratings by Neighborhood Group:
The bar chart compares the average ratings of Airbnb listings across different neighborhoods. This visualization helps to quickly understand which neighborhoods have the highest average ratings. For instance, Manhattan appears to have consistently high ratings, while other boroughs like Brooklyn and Queens also perform well.
•	Line Chart of Monthly Trends in Airbnb Pricing and Availability:
This line chart shows how the sum of prices and availability fluctuates over the months. It indicates clear seasonal trends, with prices and availability peaking toward the end of the year, likely due to increased demand during the holiday season. The dip in the early months could represent a post-holiday lull in demand. This chart helps hosts and investors anticipate pricing strategies based on seasonal trends.
•	Scatter Plot of Reviews, Ratings, and Prices for Airbnb Listings:
The scatter plot displays the relationship between the number of reviews and the average price for different room types. Each point represents an individual listing, color-coded by room type. Listings with a higher number of reviews tend to have a wide variation in pricing, suggesting that the number of reviews alone does not dictate the price. However, certain patterns can be observed, particularly for entire home/apartment listings, which tend to have higher prices compared to shared or private rooms.
Description: The Power BI dashboard provides an interactive, multi-faceted approach to understanding Airbnb listings. Slicers for room type and neighborhood allow users to filter the visualizations dynamically, enabling detailed exploration of relationships between variables such as price, availability, ratings, and reviews. The treemap, bar chart, line chart, and scatter plot work together to provide insights into pricing strategies, seasonal trends, and guest satisfaction across different parts of New York City. This dashboard is particularly useful for hosts looking to optimize their listings and for investors seeking to understand market trends.


 
The Tableau dashboard provides multiple visualizations for analyzing the relationship between ratings, neighborhood groups, and room types in Airbnb listings. The visualizations are dynamic, allowing users to interact with the data across various dimensions, including reviews, prices, and room types.
•	Bar Chart of Rating Distribution by Room Type and Neighborhood Group:
The bar chart on the left categorizes Airbnb listings by rating intervals, ranging from 1.0 to 5.0. Each rating group is color-coded to represent different room types (e.g., Hotel Room, Private Room), and the bars display how these room types are distributed across different neighborhoods such as Manhattan, Brooklyn, Queens, etc. This visualization helps identify how ratings differ across room types and neighborhoods.
•	Pie Charts of Neighborhood Group and Room Type Proportions:
The pie charts at the top of the dashboard illustrate the proportional distribution of room types (Hotel Room, Private Room, Entire Home/Apt, etc.) across various neighborhoods. This provides a quick visual summary of which room types dominate certain neighborhoods, offering insights into the market's structure across New York City's boroughs.
•	Treemap of Average Ratings Across Neighborhoods:
The treemap (labeled as "Visual 4") shows the average ratings of listings within different neighborhoods. Each block represents a neighborhood, and its size reflects the volume of listings. Darker shades indicate higher ratings, with Manhattan leading with a perfect 5.0 rating, while Queens follows with slightly lower averages. This helps in identifying the neighborhoods that tend to have better-rated listings.
•	Bar Chart of Total Prices by Neighborhood Group:
The bar chart (labeled as "Visual 1") provides an aggregate view of total pricing across neighborhoods. Manhattan stands out with the highest total price value, followed by Brooklyn. This suggests that listings in Manhattan are significantly more expensive on average than those in other boroughs.
•	Price Heatmap and Review Distribution:
The dashboard includes a price heatmap that visualizes the pricing range (from $10 to $55) across listings, allowing users to identify how prices vary across room types and neighborhoods. Alongside this, the stacked circles for "Number of Reviews" display the distribution of reviews, where larger circles indicate listings with more reviews. This visualization gives an overview of the relationship between popularity (reviews) and pricing.
Description: This Tableau dashboard offers an insightful overview of Airbnb listing trends, using various visualizations to represent data on room types, neighborhoods, prices, ratings, and reviews. With its interactivity, users can easily filter and explore specific neighborhoods or room types, uncovering key patterns such as how room types and prices vary across New York City's boroughs. The combination of pie charts, treemaps, bar charts, and heatmaps allows for a rich, multifaceted analysis of Airbnb's market dynamics.

References
1.	Airbnb Dataset:
o	Kaggle. (2024). New York City Airbnb Listings. Retrieved from Kaggle Airbnb Dataset
2.	Tableau Documentation:
o	Tableau Software. (n.d.). Tableau Public Documentation and Guides. Retrieved from Tableau Official Documentation
3.	Power BI Documentation:
o	Microsoft. (n.d.). Power BI Documentation and Resources. Retrieved from Power BI Official Documentation
4.	Data Visualization in Business:
o	Few, S. (2012). Show Me the Numbers: Designing Tables and Graphs to Enlighten. Analytics Press.
o	This book provides an in-depth understanding of how to design effective tables and graphs for business analytics.
5.	Data Analytics for Business Decision-Making:
o	Davenport, T. H., & Harris, J. G. (2017). Competing on Analytics: The New Science of Winning. Harvard Business Review Press.


