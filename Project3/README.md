# 📁 Project 3: Sales and Customers Join Analysis

## 🟡 Intermediate Level

### 🧾 Dataset Files

* `customers.csv` — Contains customer information:

  * `customer_id`
  * `name`
  * `region`

* `sales.csv` — Contains sales transactions:

  * `sale_id`
  * `customer_id`
  * `amount`
  * `date`

---

### 🎯 Goals

1. Merge the two datasets using `customer_id`.
2. Compute the **total sales per customer**.
3. Find **customers who made no sales**.
4. Calculate the **average sale amount per region**.
5. Determine the **top 3 customers with highest total sales**.
6. Find the **region with the lowest total sales**.
7. Calculate **monthly total sales trends** (extract month from `date` and group).
8. **Visualize**:

   * Total sales per region (bar chart)
   * Monthly sales trend (line chart)
9. Identify **outlier sales amounts** using basic statistical thresholds (mean ± 2\*std).
10. *(Introduction to ML)* Create a **simple linear regression** to predict sales amount based on month (using scikit-learn).

---

### 🧠 Concepts Covered

* Merging DataFrames (`pd.merge`)
* Aggregation with `groupby`, `agg`, and `pivot_table`
* Left joins to detect unmatched records
* Handling missing data after joins
* Date processing with `pd.to_datetime` and extracting components
* Data visualization using **Matplotlib** or **Seaborn**
* Basic outlier detection
* Introduction to **scikit-learn** for regression

# 🗂️ 4. Boolean Indexing (Filtering)
## ✅ Uses conditions to select rows.

* df[df['age'] > 25]          **# Rows where 'age' > 25**
* df[df['status'] == 'active']
* ✔ Returns a filtered DataFrame containing only rows meeting the condition.