#📊 Amazon Electronics Sales Analysis

📦 Overview
This project analyzes an Amazon sales dataset to identify the most selling and in-demand products in the electronics category.
By treating rating count as a stand-in for sales, the goal is to extract insights into:

What consumers actually want

Which brands are winning

What pricing strategies might be killing it

Ideal for:
📈 E-commerce businesses
🧠 Data analysts
🚀 Product launch wizards

📁 Dataset Details
Source: Amazon sales dataset (source Kaggle)

Filtered Scope:
Only electronics category products are included — surgically extracted from a larger multi-category dataset.

🧾 Columns Used:
->Product
->Product Name
->Category
->Rating Count (proxy for sales)
->Actual Price
->Discounted Price
->Ratings

🧹 Data Preprocessing
🔍 Extracted brand names from Product Name using Excel magic

🎯 Filtered down to only electronics products

🧠 Parsed specific product names for cleaner analysis

🎯 Project Goals
🏆 Identify top-selling, most demanded electronics products

📊 Analyze trends in rating counts, actual vs. discounted prices

📈 Provide actionable insights for product strategy & marketing

🛠 Tools Used
🧮 Excel
Brand extraction

Category filtering

🐍 Python
pandas: data cleaning & manipulation

matplotlib / seaborn: plotting those pretty graphs

📓 Jupyter Notebook
Used for the full-blown, annotated analysis

🚀 How to Use
Clone this repo


🔍 Key Findings
🧠 Rating count used as a smart substitute for sales data

🥇 Top Product: Wired Earphones — especially models like boAt Bassheads 100
→ Discounted Price ~ ₹379

💡 Insight: Cheaper products with high ratings dominate — value for money is king 👑

⚠️ Known Issues
Rating count is a proxy, not an actual sales figure

Some subcategory data may be missing

🔮 Future Improvements
Add review sentiment or return rate metrics
Expand to other product categories
Create an interactive dashboard using Tableau or Streamlit
