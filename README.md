# Instacart-Customer-Purchase-Behaviour-Analysis
Cleans and analyses Instacart grocery order data to uncover customer purchasing patterns, reorder behaviour, and ordering trends through exploratory data analysis.

## Project Overview
This project applies exploratory data analysis (EDA) techniques to real-world grocery order data from **Instacart**, a grocery delivery platform.

The objective is to clean and analyse multiple related datasets in order to uncover **customer purchasing patterns**, **ordering behaviour**, and **product-level insights**. The analysis focuses on understanding when customers place orders, how frequently they reorder products, and which items are most commonly purchased.

---

## Business Objective
The main objectives of this project are to:
- Clean and prepare large, multi-table datasets for analysis
- Explore customer ordering habits over time
- Identify popular and frequently reordered products
- Analyse reorder behaviour at product and customer level
- Communicate insights clearly using visualisations

---

## Datasets
The project uses five datasets provided by Instacart:

| File | Description |
|----|----|
| `instacart_orders.csv` | Order-level information |
| `products.csv` | Product details |
| `order_products.csv` | Items included in each order |
| `aisles.csv` | Grocery aisle information |
| `departments.csv` | Grocery department information |

The datasets are modified versions of the original Kaggle Instacart dataset, including missing and duplicate values for data cleaning practice.

---

## Project Structure

### Step 1 — Data Loading & Overview
- Load all datasets using appropriate `read_csv()` parameters
- Review data structure, size, and column types
- Perform initial observations

### Step 2 — Data Preprocessing
- Correct data types (IDs, numeric fields)
- Identify and handle missing values
- Detect and remove duplicate records
- Document preprocessing decisions and reasoning

### Step 3 — Exploratory Data Analysis
The analysis is divided into three sections:

#### [A] Order Timing & Frequency
- Validate order hour and day values
- Orders by hour of day
- Orders by day of week
- Time between consecutive orders

#### [B] Product Popularity
- Order hour comparison (Wednesday vs Saturday)
- Distribution of number of orders per customer
- Top 20 most frequently ordered products

#### [C] Reorder Behaviour
- Number of items per order
- Top 20 most frequently reordered products
- Reorder proportion by product
- Reorder proportion by customer
- Top 20 products added first to cart

All visualisations include clear titles, axis labels, and legends where applicable.

---

## Key Insights
- Customer ordering activity varies significantly by time of day and day of week
- A small subset of products accounts for a large share of total orders
- Reorder behaviour reveals strong customer loyalty to specific items
- Ordering patterns provide valuable signals for inventory planning and marketing strategy

*(Detailed findings are documented within the notebook.)*

---

## Tools & Technologies
- Python  
- Jupyter Notebook  
- pandas  
- matplotlib  
- Exploratory Data Analysis (EDA)

---

## Repository Structure
instacart-purchase-behaviour-analysis/
├── notebooks/ # Full EDA notebook
├── data/ # Instacart datasets (or platform reference)
└── README.md

---

## Conclusion
This project demonstrates the complete EDA workflow on a complex, real-world dataset.  
It highlights the importance of data cleaning, structured analysis, and effective visual communication when deriving insights from large-scale customer data.

---

## Author
**Erika González**  
MBA | Marketing & Data Analytics  
Focus areas: Data Analysis, Customer Behaviour, Marketing Intelligence
