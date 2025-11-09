# 📊 Sales Performance Analysis

## 🧠 Project Overview
This project — **Sales Performance Analysis** — explores and visualizes company sales data using **Python**.  
It helps identify key trends, top-performing products, customer behavior, and revenue insights that can support better business decisions.

---

## 🧩 Dataset Information
**File Used:** `Superstore.csv`  
This dataset contains detailed information about sales transactions including product categories, regions, sales, profit, and customer data.

### Key Columns:
- `Order ID` – Unique identifier for each order  
- `Order Date`, `Ship Date` – Dates for order and shipment  
- `Customer Name` – Customer who made the purchase  
- `Category`, `Sub-Category` – Product classification  
- `Region` – Geographic area of the sale  
- `Sales`, `Profit`, `Quantity`, `Discount` – Sales performance metrics  

---

## 🧹 Data Preprocessing
Data was cleaned and transformed using **Pandas** to ensure quality and accuracy.

### Steps Performed:
1. Loaded the dataset using `pd.read_csv()`.  
2. Checked for missing values and duplicates.  
3. Converted `Order Date` and `Ship Date` into datetime format.  
4. Created new columns:
   - `Year` and `Month` extracted from `Order Date`
   - `Profit Margin = Profit / Sales`
5. Removed unnecessary or null entries.

---

## 🧮 Exploratory Data Analysis (EDA)
The notebook (`sales_performance_analysis.ipynb`) includes descriptive analysis and visualizations.

### Key Analyses:
- **Sales by Category:** Identify which product categories drive the most sales.  
- **Profit by Sub-Category:** Determine most and least profitable items.  
- **Sales by Region:** Visualize revenue contribution by region.  
- **Monthly Sales Trend:** Observe seasonality and time-based patterns.  
- **Top 10 Customers:** Discover customers contributing the highest sales.  

---

## 📈 Visualizations
The project uses **Matplotlib** and **Seaborn** for clear, professional charts.

### Visuals Included:
- Bar chart – *Sales by Category*  
- Column chart – *Profit by Sub-Category*  
- Line chart – *Monthly Sales Trend*  
- Pie/Bar chart – *Sales by Region*  
- Horizontal bar chart – *Top 10 Customers*  

---

## ⚙️ Tools & Libraries
- **Python 3**
- **Jupyter Notebook**
- **Pandas** – Data manipulation  
- **Matplotlib** – Visualization  
- **Seaborn** – Enhanced visualization styling  

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/HimashMadushanka/Sales_Performance_Analysis.git
   cd Sales_Performance_Analysis
