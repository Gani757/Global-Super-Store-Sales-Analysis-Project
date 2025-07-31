# Re-run code after kernel reset to regenerate the markdown file

# Global Super Store Sales Analysis

A data analytics project to explore, clean, and visualize retail sales data from a global superstore. The goal is to uncover patterns in sales, profit, discounts, and product performance across countries and customer segments.

---

## **Key Objectives**

-- Analyze product-wise, segment-wise, and country-wise sales and profit  
-- Visualize monthly sales trends and identify peak periods  
-- Understand the impact of discounts on profitability  
-- Recommend bundling strategies to improve product performance  

---

## **Key Insights**

-- **Paseo** is the highest-selling and most profitable product  
-- **USA, Mexico, and France** lead in overall revenue  
-- **Government segment** contributes the most to profit across all regions  
-- High **discounts** negatively affect profit margins  
-- Products like **Montana** and **Velo** can be bundled with Paseo to increase total sales  

---

## **Tools & Technologies**

-- Python  
-- Pandas, NumPy  
-- Matplotlib, Seaborn  
-- Jupyter Notebook  

---

## **Project Structure**

Global_Super_Store_Sales_Analysis/
├── Global Super Store Sales Data Analysis.ipynb
├── Visualizations/
│ ├── monthly_trends.png
│ ├── product_profit.png
│ └── country_segment_sales.png
├── README.md
└── data/
└── GlobalSuperStore.csv


---

## **Dataset Overview**

-- Contains sales, profit, discounts, product names, countries, customer segments, and order dates  
-- Ideal for sales trend analysis, segment performance, and KPI tracking  

---

## **What I Learned**

-- Creating time-based KPIs and trend analysis  
-- Handling real-world data: missing values, skewness, outliers  
-- Building meaningful visualizations to derive business insights  
-- Structuring data projects for portfolios and GitHub  

---

## **Getting Started**

To run this project locally:

1. Clone the repository  
2. Open the notebook `Global Super Store Sales Data Analysis.ipynb`  
3. Install required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`  
4. Load the dataset and run all cells  

---

## **License**

This project is for educational and portfolio purposes only.
"""

# Save to a file
file_path = "/mnt/data/README_Global_Super_Store_Sales_Analysis.md"
with open(file_path, "w") as file:
    file.write(readme_content)

file_path
'/mnt/data/README_Global_Super_Store_Sales_Analysis.md'
