# sales-records-dataset-analysis
Data analysis pipeline

Sales Records Data Analysis
This project provides a comprehensive analysis of business sales data using Python. It covers the entire data science workflow, including data cleaning, exploratory data analysis (EDA), and interactive data visualization to uncover trends in profitability, customer demographics, and regional performance.

📊 Project Overview
The objective of this analysis is to transform raw sales records into actionable business insights. By cleaning a dataset of 1,000 transactions, the project identifies key drivers of revenue and profit across different product categories and geographical regions.

🛠️ Tech Stack
Language: Python

Libraries: * Pandas & NumPy: Data manipulation and numerical analysis.

Matplotlib & Seaborn: Static statistical visualizations.

Plotly Express: Interactive charts and bubble plots.

Openpyxl: Handling Excel file formats.

📂 Dataset Description
The analysis was performed on a dataset containing 1,000 rows and 14 initial columns, including:

Transaction Details: Order ID, Order Date, Payment Method.

Customer Info: Name, Gender, Region.

Product Info: Category (Electronics, Clothing, Furniture), Product Name.

Financial Metrics: Quantity, Unit Price, Total Sales, Discount, and Profit.

🔍 Key Analysis Steps
Data Cleaning:

Identified and handled missing values across all columns (ranging from 3.9% to 5.9% per column).

Removed duplicates and handled null values in critical fields like Order_ID, Total_Sales, and Profit.

Standardized data types for dates and financial figures.

Exploratory Data Analysis (EDA):

Descriptive statistics to understand mean sales (~₦424,735) and profit margins.

Distribution analysis of sales rep performance and payment methods (Cash, Online, POS, Transfer).

Advanced Visualization:

Profit Analysis: Correlation between Unit Price and Profit.

Regional Performance: Breakdown of sales and quantity sold by territory (West, East, South, etc.).

Product Insights: Identifying top-performing categories (e.g., Laptops in Electronics).

📈 Results
Cleaned Output: The final processed dataset was exported as sales_records_cleaned.xlsx with 945 high-quality rows for further reporting.

Visualizations: The notebook includes interactive bubble charts using Plotly to visualize the relationship between unit price, profit, and quantity sold.

<img src="path/to/your/image.png" alt="Sales Analysis Chart" width="500">
