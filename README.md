# 🍕 Pizza Sales Analysis Dashboard

## 📌 Project Overview

The **Pizza Sales Analysis Dashboard** is an interactive data analytics project developed using **Microsoft Power BI**. The project analyzes pizza sales data and converts raw transactional data into meaningful visual reports and Key Performance Indicators (KPIs).

The dashboard provides an interactive view of sales performance based on revenue, orders, pizza quantity, pizza category, pizza size, and time-based sales trends.

The project demonstrates the complete Power BI data analytics workflow:

**Data Import → Data Cleaning → Data Transformation → Data Modeling → DAX Calculations → Data Visualization → Interactive Dashboard**

---

# 🛠️ Tech Stack

## 1. Microsoft Power BI

**Power BI Desktop** is the primary tool used to develop the dashboard.

Used for:

* Importing the sales dataset
* Creating the data model
* Creating calculated measures
* Designing dashboard pages
* Creating charts and KPI cards
* Adding slicers and filters
* Creating interactive visualizations
* Analyzing sales performance

---

## 2. Power Query

**Power Query** is used for data cleaning and transformation before the data is loaded into the Power BI model.

### Operations performed:

* Data type conversion
* Column transformation
* Data cleaning
* Handling missing or inconsistent values
* Removing unnecessary columns
* Formatting date and numeric fields
* Creating required transformed columns
* Preparing structured data for analysis

Power Query follows the **ETL (Extract, Transform, Load)** process inside Power BI.

---

## 3. DAX

**DAX (Data Analysis Expressions)** is used to create calculated measures and perform analytical calculations.

### Key calculations include:

* Total Revenue
* Total Orders
* Total Pizzas Sold
* Average Order Value
* Average Pizzas Per Order
* Daily Sales
* Monthly Sales
* Category-wise Sales
* Size-wise Sales
* Pizza-wise Sales

### Example DAX Measures

```DAX
Total Revenue =
SUM(pizza_sales[total_price])
```

```DAX
Total Orders =
DISTINCTCOUNT(pizza_sales[order_id])
```

```DAX
Total Pizzas Sold =
SUM(pizza_sales[quantity])
```

```DAX
Average Order Value =
DIVIDE([Total Revenue], [Total Orders])
```

```DAX
Average Pizzas Per Order =
DIVIDE([Total Pizzas Sold], [Total Orders])
```

These measures are used throughout the dashboard to dynamically calculate results based on selected filters.

---

# 📂 Dataset

The project uses a **Pizza Sales transactional dataset**.

The dataset contains information related to pizza orders and includes fields such as:

* Order ID
* Order Date
* Order Time
* Pizza Name
* Pizza Category
* Pizza Size
* Quantity
* Unit Price
* Total Price

The transactional data is transformed and analyzed using Power Query and DAX.

---

# 🧹 Data Preparation

The raw dataset was processed before visualization.

### Data preparation workflow:

```text
Raw Dataset
     ↓
Data Import
     ↓
Power Query
     ↓
Data Cleaning
     ↓
Data Transformation
     ↓
Data Modeling
     ↓
DAX Measures
     ↓
Power BI Visualizations
```

### Data cleaning activities:

* Verified column data types
* Converted date columns into appropriate date formats
* Converted numerical columns into numeric data types
* Checked missing values
* Removed unnecessary fields
* Standardized column values
* Prepared the dataset for analysis

---

# 📊 Dashboard Components

The dashboard contains different visualizations to analyze pizza sales.

## KPI Cards

The main KPI cards display:

* **Total Revenue**
* **Total Orders**
* **Total Pizzas Sold**
* **Average Order Value**
* **Average Pizzas Per Order**

These KPIs provide a quick overview of overall sales performance.

---

# 📈 Sales Trend Analysis

Time-based visualizations are used to analyze sales trends.

The dashboard provides:

* Daily sales analysis
* Monthly sales analysis
* Order trends
* Revenue trends
* Quantity trends

These visualizations help identify periods with higher or lower sales.

---

# 🍕 Pizza Category Analysis

Sales performance is analyzed based on pizza categories.

The dashboard can compare:

* Revenue by category
* Orders by category
* Quantity sold by category

This helps determine which categories contribute most to overall sales.

---

# 📏 Pizza Size Analysis

Pizza sales are analyzed based on size.

The dashboard provides comparisons between different pizza sizes such as:

* Small
* Medium
* Large
* Extra Large

The analysis can be performed using revenue, order quantity, and number of pizzas sold.

---

# 🏆 Top & Bottom Performing Pizzas

The dashboard identifies pizza products based on their sales performance.

### Top-performing analysis:

* Top pizzas by revenue
* Top pizzas by quantity
* Top pizzas by number of orders

### Bottom-performing analysis:

* Lowest revenue-generating pizzas
* Lowest quantity-selling pizzas
* Lowest order-count pizzas

This allows product-level performance to be analyzed easily.

---

# 🎛️ Interactive Filters

Power BI slicers and filters are used to make the dashboard interactive.

Users can filter the report based on dimensions such as:

* Date
* Pizza Category
* Pizza Size
* Pizza Name

When a filter is selected, the KPI cards and visualizations update dynamically.

---

# 📊 Visualizations Used

The dashboard uses Power BI visualizations such as:

* KPI Cards
* Bar Charts
* Column Charts
* Line Charts
* Pie / Donut Charts
* Tables
* Slicers

Each visualization is selected based on the type of information being analyzed.

---

# 🧮 Data Analysis Techniques

The project demonstrates the following Power BI concepts:

* Data Cleaning
* Data Transformation
* Data Modeling
* Calculated Measures
* DAX Functions
* Aggregations
* Filtering
* Slicers
* Time-based Analysis
* Category Analysis
* Product-level Analysis
* Interactive Data Visualization

---

# 🔄 Power BI Workflow

The complete implementation follows this workflow:

```text
              Pizza Sales Dataset
                       ↓
                 Power BI Import
                       ↓
                  Power Query
                       ↓
              Data Transformation
                       ↓
                 Data Modeling
                       ↓
                 DAX Measures
                       ↓
              Report Development
                       ↓
            Interactive Dashboard
                       ↓
               Sales Analysis
```

---

# 📁 Project Structure

```text
Pizza-Sales-PowerBI/
│
├── Pizza_Sales_Dashboard.pbix
│
├── pizza_sales.csv
│
├── README.md
│
└── screenshots/
    ├── dashboard1.png
    └── dashboard2.png
```

### Files

| File                         | Description                   |
| ---------------------------- | ----------------------------- |
| `Pizza_Sales_Dashboard.pbix` | Power BI Desktop project file |
| `pizza_sales.csv`            | Pizza sales dataset           |
| `README.md`                  | Project documentation         |
| `screenshots/`               | Dashboard preview images      |

---

# 💻 Technologies Used

| Technology           | Purpose                                 |
| -------------------- | --------------------------------------- |
| **Power BI Desktop** | Dashboard development and visualization |
| **Power Query**      | Data cleaning and transformation        |
| **DAX**              | Calculations and analytical measures    |
| **Excel / CSV**      | Source data                             |
| **Git**              | Version control                         |
| **GitHub**           | Project repository and portfolio        |

---

# 🎯 Project Objective

The objective of this project is to demonstrate the ability to:

* Work with raw sales data
* Clean and transform data
* Create analytical DAX measures
* Build interactive Power BI dashboards
* Analyze sales trends
* Compare product and category performance
* Present data through clear and interactive visualizations

---

# 👩‍💻 Author

**Thambutuku Shalini**

B.Tech – Computer Science and Engineering

GitHub: **Shalini5254**
