# Instacart-E-commerce-Analysis



📌 1. Project Title
E-Commerce Customer Order Behavior Analysis (Instacart Dataset)

🧠 2. Problem Statement
The project aims to analyze Instacart’s online grocery store dataset to understand customer ordering patterns, product preferences, and shopping behaviors. This helps businesses:

Improve product placement

Optimize inventory

Personalize recommendations

🧰 3. Tools & Libraries Used
Python

pandas: Data manipulation

numpy: Numerical operations

matplotlib & seaborn: Data visualization

Jupyter Notebook: For exploration and presentation

🧪 4. Exploratory Data Analysis (EDA)
📂 Datasets Used:
orders.csv: Contains info about all customer orders

order_products__prior.csv: Items from previous orders

order_products__train.csv: Items from the training set (for modeling)

products.csv: Product information

departments.csv: Department categories

aisles.csv: Aisle categories

🔍 Key Steps in EDA:
Data Loading:

All CSVs are loaded and inspected using .head(), .info(), .shape().

Data Cleaning:

Checked for null values

No missing values were found in most files

Merged orders, products, departments, aisles, and prior orders into a single DataFrame

Feature Engineering:

Combined datasets to analyze which products are being ordered

Created new columns to analyze frequency, reorders, department-wise stats

Visualizations:

📊 Most Frequently Ordered Products

📊 Top Departments and Aisles

⏱️ Orders by Day of Week / Hour of Day

🔁 Reorder Analysis (How often people reorder products)

👨‍👩‍👧‍👦 Customer Segments: Like new users vs repeat customers

🔑 5. Key Insights

Insight	Description
🥑 Most Popular Products	Bananas, Bag of Organic Bananas, and Strawberries are most ordered.
🏬 Popular Departments	Produce, dairy eggs, snacks dominate orders.
⏰ Order Time Patterns	Most orders happen between 9 AM and 3 PM.
📅 Day-wise Trends	Sunday and Monday are the peak shopping days.
🔁 Reorders	A large percentage of products are reorders—showing loyalty.
🧾 Basket Size	Most customers order between 5–15 items per order.
🧾 6. Conclusion
This project gives a comprehensive view of customer purchase behavior on an e-commerce platform. The insights can help marketing teams personalize recommendations and improve customer experience.

