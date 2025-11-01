# TASK-7-Get-Basic-Sales-Summary-from-a-Tiny-SQLite-Database-using-Python 

### 🎯 Objective
Use SQL inside Python to pull simple sales information (like total quantity sold and total revenue) and visualize it using a bar chart.

---

### 🧰 Tools & Libraries Used
- **Python**
- **SQLite** (built into Python)
- **pandas**
- **matplotlib**
- **jupiter notebook

---

### 🗂️ Dataset
A small SQLite database file named `sales_data.db` was created.  
It contains one table: **sales**, with the following columns:
- `product` — Name of the product  
- `quantity` — Quantity sold  
- `price` — Price per unit  

### ⚙️ Steps Performed

1. **Install Required Libraries**
2. **Import Libraries**
3. **Create and Connect to SQLite Database**
4. **Create Table and Insert Sample Data**
5. **Run SQL Query to Get Sales Summary**
6. **Visualize the Results**
   ```python
   df.plot(kind='bar', x='product', y='revenue', title='Revenue by Product', legend=False)
   plt.ylabel('Revenue')
   plt.xlabel('Product')
   plt.show()
   ```

---

### 📊 Output
**Printed Table**

**Bar Chart**  
A simple bar chart showing total revenue by product.

---

### 🧩 Learning Outcomes
By completing this task, I learned how to:
- Connect Python with a SQLite database.
- Execute basic SQL queries inside Python.
- Use pandas to read SQL query results.
- Visualize sales data using matplotlib.
- Create a simple data summary and chart from scratch.

---

### 📁 Files Included
- `sales_data.db` — SQLite database file  
- `task7_sales_summary.ipynb` — Jupyter Notebook file  
- `sales_chart.png` - chart
