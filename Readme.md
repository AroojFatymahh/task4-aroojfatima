#  Data Analytics Project 4 – E-Commerce Sales Data Analysis

## Project OverviewS

This project performs **Data Cleaning, Exploratory Data Analysis (EDA), and Data Visualization** on an e-commerce sales dataset using Python. The objective is to transform raw sales data into meaningful business insights that support data-driven decision-making.

The project demonstrates essential data analytics skills, including data preprocessing, statistical analysis, visualization, and interpretation of results.

---

#  Objectives

* Clean and preprocess the dataset.
* Handle missing values and duplicate records.
* Perform Exploratory Data Analysis (EDA).
* Visualize sales trends and customer behavior.
* Identify business patterns and generate actionable insights.
* Present findings through professional visualizations.

---

#  Dataset Information

The dataset contains **1,200 records** and **14 columns** related to e-commerce orders.

### Features

| Column          | Description                 |
| --------------- | --------------------------- |
| OrderID         | Unique order identifier     |
| Date            | Order date                  |
| CustomerID      | Customer identifier         |
| Product         | Product purchased           |
| Quantity        | Quantity ordered            |
| UnitPrice       | Price per unit              |
| ShippingAddress | Customer shipping address   |
| PaymentMethod   | Payment method used         |
| OrderStatus     | Current order status        |
| TrackingNumber  | Shipment tracking number    |
| ItemsInCart     | Number of items in the cart |
| CouponCode      | Coupon applied              |
| ReferralSource  | Customer acquisition source |
| TotalPrice      | Total order amount          |

---

# Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* OpenPyXL

---

# Project Workflow

## 1. Data Loading

* Imported Excel dataset
* Displayed dataset preview
* Examined structure and dimensions


## 2. Data Cleaning

Performed the following preprocessing steps:

* Checked missing values
* Replaced missing values using the mode
* checked duplicated records
* Validated unique values


## 3. Exploratory Data Analysis (EDA)

Performed:

* Descriptive statistics
* Correlation analysis
* Distribution analysis
* Categorical feature analysis
* Numerical feature analysis

## 4. Data Visualization

The following visualizations were created:

* Orders Over Time
* Top Selling Products
* Revenue by Product
* Quantity vs Total Price
* Correlation Heatmap



# Key Insights

* Sales fluctuate over time with identifiable peak periods.
* A small number of products contribute significantly to total sales.
* Revenue varies considerably across products..
* Most purchases fall within a moderate price range.
* Customers typically buy a small number of items per order.
* Correlation analysis reveals relationships among numerical variables that can support future business decisions.

---

# Project Structure

```text
DA Proj 4/
│
├── data/
│   └── Dataset for Data Analytics.xlsx
│
├── notebook/
│   └── data_analytics.ipynb
│  
│
├── README.md
└── requirements.txt
```

---

#  How to Run the Project

1. Clone or download the repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook

4. Open:

data_analytics.ipynb
```

5. Run all notebook cells in order.



# Requirements

* pandas
* numpy
* matplotlib
* seaborn
* openpyxl
* jupyter

---

#  Learning Outcomes

This project demonstrates practical experience in:

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Business Data Visualization
* Statistical Analysis
* Business Insight Generation
* Python for Data Analytics

# Future Improvements

* Build an interactive dashboard using Power BI or Tableau.
* Develop sales forecasting models using machine learning.
* Create customer segmentation based on purchasing behavior.
* Deploy an interactive analytics dashboard using Streamlit or Dash.
* Integrate real-time sales data for live reporting.