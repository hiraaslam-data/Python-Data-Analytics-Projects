# EDA on Retail Sales (Superstore)

An Exploratory Data Analysis (EDA) project on the Sample Superstore retail dataset. It finds sales and profit patterns and ends with business recommendations.

**Notebook:** `EDA_on_Retail_Sales.ipynb`
**Input:** `samplesuperstore.csv`

## What this project does
1. Loads the data and checks its shape, data types and summary statistics
2. Finds the Top 10 sub-categories by total sales
3. Plots a correlation heatmap of Sales, Quantity, Discount and Profit
4. Prints a business summary: total revenue, total profit, average discount
5. Shows the customer segment distribution (Consumer, Corporate, Home Office)
6. Compares average profit across regions

## Key insights
- Phones and Chairs are among the top revenue drivers; Bookcases sell much less
- Discount and Profit are negatively correlated (-0.22): higher discounts reduce profit
- The Consumer segment has the most orders
- The Central region has lower average profit, linked to higher discounts

## Business recommendations
1. **Limit discounts** above 20%
2. **Promote high performers** like Phones and Chairs
3. **Review regional strategy**, especially pricing and promotions in the Central region

## Tools & libraries
Python, pandas, matplotlib, seaborn

## How to run
```bash
pip install pandas matplotlib seaborn
jupyter notebook EDA_on_Retail_Sales.ipynb
```
Place `samplesuperstore.csv` in the same folder as the notebook.

## Skills shown
Exploratory data analysis, data visualization, correlation analysis, business insight writing
