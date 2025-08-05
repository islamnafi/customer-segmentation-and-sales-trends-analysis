This project involves detailed exploratory data analysis (EDA) on a sales dataset using Python, with a focus on deriving insights from customer demographics and sales behavior. The analysis leverages `pandas`, `matplotlib`, and `seaborn` for data wrangling and visualization.

---

## Project Objective

To explore and analyze a retail sales dataset to understand:
- Customer demographics (age, gender, marital status, etc.)
- Buying behavior based on product category and occupation
- Sales contribution by gender, state, and age group

---

## Tools and Libraries Used

- Python
- Pandas: Data manipulation and cleaning
- Matplotlib: Basic plotting
- Seaborn: Statistical data visualization
- Jupyter Notebook

---

## Dataset Overview

The dataset includes the following features:

- User_ID: Unique identifier for customers
- Cust_name, Product_ID
- Gender, Age, Age Group, Marital_Status
- State, Zone, Occupation
- Product_Category, Orders, Amount

Initial dataset size: 11,251 rows × 15 columns

After cleaning:
- Removed null values in Amount
- Dropped unused columns: Status, unnamed1

---

## Key Analyses Performed

- Gender Distribution: Count of male vs female customers
- Sales by Gender: Total purchase amount by gender
- Age Group vs Gender: Distribution and buying trends
- Marital Status Impact: Buying behavior based on marital status
- Occupation Analysis: Order and amount distribution across professions
- Product Category Insights: Popular product types among customers

All visualizations include proper axis labels, legends, and bar annotations for clarity.

---

## Visualizations

- Bar plots for gender, age group, marital status, occupation
- Sales distribution by gender and occupation
- Sales insights by product category

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sales-data-analysis-using-pandas-and-seaborn.git
   
2. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn

3. Run the analysis:
   Open the Jupyter Notebook or .py file and execute step by step.
