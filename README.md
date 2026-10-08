# 🛒 E-Commerce Sales Analytics

## 📌 Project Overview

**E-Commerce Sales Analytics** is a data analysis project developed using **Python** to analyze e-commerce sales performance and generate meaningful business insights.

The project uses a dataset containing **5,000 orders and 12 columns**, covering information about orders, customers, product categories, regions, pricing, discounts, payments, delivery, customer ratings, and revenue.

The analysis focuses on understanding sales performance, revenue trends, customer behavior, product categories, regional performance, payment preferences, delivery performance, and relationships between numerical variables.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Analyze overall sales and revenue performance
* Identify revenue trends over time
* Analyze product category performance
* Compare sales performance across regions
* Understand customer ratings and delivery performance
* Analyze the relationship between discounts and revenue
* Identify customer payment preferences
* Explore relationships between numerical variables
* Generate meaningful business insights using data visualization

---

## 📊 Dataset Overview

The dataset contains **5,000 records and 12 columns**.

| Column             | Description                          |
| ------------------ | ------------------------------------ |
| `order_id`         | Unique order identification number   |
| `order_date`       | Date of the order                    |
| `customer_id`      | Customer identification number       |
| `product_category` | Product category                     |
| `region`           | Sales region                         |
| `quantity`         | Quantity of products ordered         |
| `unit_price`       | Price per unit                       |
| `discount`         | Discount applied to the order        |
| `payment_method`   | Payment method used                  |
| `delivery_days`    | Number of days required for delivery |
| `customer_rating`  | Customer rating                      |
| `revenue`          | Revenue generated from the order     |

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical analysis
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook**

---

## 🔍 Project Workflow

### 1. Data Loading & Initial Analysis

The dataset was loaded using Pandas and examined using:

* `head()`
* `tail()`
* `shape`
* `columns`
* `info()`
* `describe()`
* `dtypes`
* `nunique()`

### 2. Data Preprocessing

The project includes data quality checks and preprocessing such as:

* Missing value analysis
* Duplicate record checking
* Data type handling
* Date conversion
* Feature creation
* Data filtering and aggregation

### 3. Exploratory Data Analysis (EDA)

Exploratory analysis was performed to understand:

* Sales performance
* Revenue distribution
* Product categories
* Regional performance
* Payment methods
* Customer ratings
* Delivery performance
* Discount patterns
* Relationships between numerical variables

---

## 📈 Data Visualizations

Multiple visualization techniques were used to identify patterns and trends in the dataset.

The project includes:

* 📊 Bar Charts
* 📈 Line Charts
* 🥧 Pie / Donut Charts
* 📦 Box Plots
* 📉 Histograms
* 🔵 Scatter Plots
* 🔥 Correlation Heatmaps
* 🎻 Violin Plots
* 🌊 Area Charts
* 📊 Stacked Bar Charts
* 🔢 Pair Plots

These visualizations help convert raw e-commerce data into understandable business insights.

---

## 📌 Key Analysis Areas

### 💰 Revenue Analysis

Revenue was analyzed across:

* Product categories
* Regions
* Time periods
* Orders
* Quantity
* Discounts

### 🛍️ Product Category Analysis

Product categories were compared based on:

* Total revenue
* Customer ratings
* Sales performance
* Regional contribution

### 🌎 Regional Analysis

Sales performance was analyzed across the available regions:

* East
* West
* North
* South

### 💳 Payment Analysis

Customer payment preferences were analyzed using:

* Card
* COD
* Wallet

### 🚚 Delivery Analysis

Delivery performance was analyzed using:

* Delivery days
* Delivery categories
* Customer ratings

### ⭐ Customer Rating Analysis

Customer ratings were analyzed to understand customer satisfaction patterns across product categories and other business factors.

### 🏷️ Discount Analysis

The relationship between **discount percentage and revenue** was explored using statistical analysis and scatter plots.

---

## 📊 Statistical Analysis

The project uses statistical techniques to understand the numerical variables and their relationships.

Key variables analyzed include:

* Quantity
* Unit Price
* Discount
* Delivery Days
* Customer Rating
* Revenue

Correlation analysis and pair plots were used to identify relationships between numerical variables.

---

## 📌 Dataset Statistics

Some important dataset statistics:

* **Total Orders:** 5,000
* **Unique Customers:** 989
* **Product Categories:** 4
* **Regions:** 4
* **Payment Methods:** 3
* **Average Quantity per Order:** 4.04
* **Average Unit Price:** 308.42
* **Average Discount:** 18.00%
* **Average Delivery Time:** 6.12 days
* **Average Customer Rating:** 2.97
* **Average Revenue per Order:** 1,021.96

---

## 💡 Business Insights

The analysis helps identify:

* Which product categories generate higher revenue
* Which regions perform better
* How revenue changes over time
* Customer payment preferences
* Customer rating patterns
* Delivery performance
* The relationship between discounts and revenue
* Important numerical factors associated with sales performance

These insights can support better **sales planning, customer experience improvement, pricing decisions, and business strategy**.

---

## 📁 Project Structure

```text
E-Commerce-Sales-Analytics/
│
├── main project new (3).ipynb
├── E-Commerce Sales Analytics.csv
├── README.md
└── images/ppt
    └── dashboard / visualization screenshots
```

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Open Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open the project notebook

Open:

```text
main project new .ipynb
```

Make sure the dataset file is available in the same project folder.

---

## 📚 Dataset Source

The dataset used for this project is available on Kaggle:

**E-Commerce Sales Analytics Dataset**

https://www.kaggle.com/datasets/abbas829/e-commerce-sales-analytics-dataset

---

## 👨‍💻 Author

**Abhijith P**

Aspiring Data Analyst | Accounting & Finance Background

**Skills:** Python • SQL • Excel • Power BI • Data Visualization • Data Analytics

---

## ⭐ Conclusion

This project demonstrates how **Python-based data analysis and visualization** can be used to transform e-commerce data into meaningful business insights.

The project covers the complete analytical workflow from **data loading and preprocessing to exploratory analysis, statistical analysis, visualization, and business insights**.
