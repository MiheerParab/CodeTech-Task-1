# CodeTech-Task-1
📊 Amazon Sales Dataset: Exploratory Data Analysis (EDA)
📝 Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on the Amazon Sales Dataset. The primary goal is to derive meaningful insights and understand patterns, trends, and relationships within the data. The analysis helps in identifying factors influencing sales and customer behavior.

📂 Dataset Information
Dataset Source: [Provide dataset link or mention source]
Description: The dataset includes various features such as product categories, prices, ratings, reviews, and sales performance.
Size: [Number of rows/columns, size in MB]
Key Columns:
Product ID: Unique identifier for products.
Product Category: Categories of items sold.
Price: Selling price of products.
Rating: Customer ratings (out of 5).
Reviews: Number of reviews per product.
Sales: Sales volume for each product.
🔧 Project Workflow
1. Data Loading and Inspection
Imported the dataset using Pandas.
Inspected the structure of the dataset (.info(), .describe()).
2. Data Cleaning
Handled missing values by imputation or removal.
Corrected data types for numerical and categorical variables.
Removed duplicate rows to ensure data integrity.
3. Data Transformation
Scaled and normalized numerical features.
Encoded categorical variables for analysis.
4. Exploratory Data Analysis
Performed univariate and multivariate analysis.
Explored correlations between features like price, rating, and sales.
Identified outliers and anomalies using visualization tools.
Visualized sales trends across categories, price ranges, and time.
5. Key Insights
Determined the most profitable categories and products.
Analyzed the impact of ratings and reviews on sales.
Identified the optimal price range for maximizing sales.
6. Data Visualization
Used Matplotlib, Seaborn, and Plotly to create insightful plots:
Bar plots for category-wise sales.
Heatmaps for feature correlation.
Box plots for price distribution.
Line plots for sales trends over time.
🛠️ Technologies Used
Programming Language: Python
Libraries:
Data Manipulation: Pandas, NumPy
Data Visualization: Matplotlib, Seaborn, Plotly
Statistical Analysis: SciPy, Statsmodels
📈 Results
Products priced between $50 and $100 had the highest sales volume.
Categories like Electronics and Books contributed significantly to total sales.
Higher-rated products (4.5+) showed increased sales, emphasizing the importance of customer satisfaction.
🗂️ Repository Structure
plaintext
Copy code
📦 Amazon-Sales-EDA
 ┣ 📂 data
 ┃ ┣ 📜 amazon_sales.csv          # Raw dataset
 ┃ ┣ 📜 cleaned_amazon_sales.csv  # Cleaned dataset
 ┣ 📂 notebooks
 ┃ ┣ 📜 amazon_sales_eda.ipynb    # Jupyter notebook with complete EDA
 ┣ 📂 visuals
 ┃ ┣ 📜 sales_trend.png           # Sales trends visualization
 ┃ ┣ 📜 category_analysis.png     # Category-wise analysis
 ┣ 📜 README.md                   # Project documentation
 ┣ 📜 requirements.txt            # Python dependencies
📌 Key Plots and Insights
1. Sales by Category
Visualization: Bar chart showing the top-performing categories.
Insight: Electronics had the highest sales volume.
2. Correlation Heatmap
Insight: Sales positively correlate with the number of reviews and ratings.
3. Price vs. Sales
Insight: Products in the mid-price range outperform cheaper or premium products.
🚀 How to Run the Project
Clone this repository:
bash
Copy code
git clone https://github.com/your-username/amazon-sales-eda.git
cd amazon-sales-eda
Install required dependencies:
bash
Copy code
pip install -r requirements.txt
Run the Jupyter notebook:
bash
Copy code
jupyter notebook notebooks/amazon_sales_eda.ipynb
🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

📜 License
This project is licensed under the MIT License.

👤 Author
Name: Miheer Parab
LinkedIn: Miheer Parab
Email: YourEmail@example.com
