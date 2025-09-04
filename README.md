Task 2: Exploratory Data Analysis (EDA)
📌 Objective

Perform detailed exploratory data analysis (EDA) on the Supermart Grocery Sales – Retail Analytics Dataset to uncover meaningful business insights using visualizations and statistical summaries.

🛠 Tools & Libraries

Python

Pandas

NumPy

Matplotlib

Seaborn

📂 Steps Performed

Data Cleaning & Preprocessing

Loaded dataset from Kaggle.

Formatted column names for consistency.

Checked for missing values and duplicates.

Converted order_date to datetime format.

Data Understanding

Used .info(), .describe(), .value_counts() to explore data structure.

Verified categorical and numerical features.

Exploratory Analysis

Distributions: Histograms and boxplots for sales, profit, and discount.

Outliers: Detected using IQR method and visualized with boxplots.

Skewness: Checked using .skew(), applied log transformation to sales and profit.

Groupby + Aggregations:

Category-wise and Sub-category-wise Sales & Profit

Region-wise and State-wise Sales & Profit

Profit Margin by Category

Visualizations

Category vs Profit comparison

Region-wise Sales

Top Sub-categories by Sales

Profit vs Sales scatter plot (colored by category)

Correlation Heatmap (sales, profit, discount, profit_margin)

📊 Key Insights

Technology category yields the highest profit margin.

Certain sub-categories (e.g., Phones, Chairs) dominate sales.

Discounts show a negative correlation with profit.

A few states contribute disproportionately to overall sales.

Data is positively skewed; log transformation helps normalization.

📑 Deliverables

task_02_DA.ipynb → Jupyter Notebook with code and analysis

task_02_DA.pdf → PDF report (exported notebook)

README.md → Documentation of workflow
