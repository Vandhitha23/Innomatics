🍔 Food Delivery Data Analysis
📌 Overview
This project combines food delivery data from multiple files into one final dataset and performs basic analysis to extract insights.
📂 Datasets
orders.csv – Order transactions
users.json – User details (city, membership)
restaurants.sql – Restaurant details (cuisine, rating)
🔗 Data Integration
Joined using LEFT JOIN
Keys used:
user_id (orders ↔ users)
restaurant_id (orders ↔ restaurants)
🛠 Tools
Python
Pandas
SQLite
Google Colab
📊 Output
final_food_delivery_dataset.csv
✅ Conclusion
This project successfully demonstrates how data from different formats (CSV, JSON, and SQL) can be merged into a single, well-structured dataset using Python and pandas. By applying LEFT JOINs, all order records were preserved while enriching them with user and restaurant details.
The final consolidated dataset enabled meaningful analysis such as revenue trends, user membership impact, city and cuisine performance, and restaurant rating insights. Overall, this project reflects a practical, real-world data analytics workflow and shows how raw data can be transformed into valuable business insights.
