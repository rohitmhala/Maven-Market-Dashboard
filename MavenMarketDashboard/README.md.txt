# Retail Business Analytics Dashboard

## 🎯 Project Objective

To gain actionable insights into customer behavior, product performance, sales trends, return patterns, and store profitability using Power BI dashboards. This analysis will help support better business decisions and improve operational efficiency across departments.

## 📦 Dataset

[Access the dataset here](./MavenMarket.zip)  


The raw data was transformed and visualized using Power BI, and insights were extracted from the following dashboards.

## ❓ Questions Answered Using Dashboards

1. Who are our top customers and how loyal are they?
2. What customer segments (gender, tier, marital status) generate the most revenue?
3. Which products and brands are the most/least profitable?
4. What are the most returned products and when do returns spike?
5. How do sales and profits vary by month and region?
6. Which cities and stores generate the most profit?

## 🔗 Power BI Dashboard Link

[Dashboard](MavenMarketDashboard.pbix)


## ⚙️ Process

## 1. Data Collection

This project uses the **Maven Market** dataset, which was sourced directly from the [GitHub repository]

The dataset includes structured retail business data across multiple dimensions:

- 🧾 Sales transactions  
- 🛍️ Product catalog  
- 👥 Customer records  
- 🔁 Return logs  
- 🏬 Store information

No manual data extraction from systems like POS, CRM, or inventory platforms was performed.

### 2. **Data Cleaning and Preparation**
- Removed duplicates, handled null/missing values, and ensured data consistency across tables.
- Standardized date formats, categorized continuous variables, and formatted currency and percentage fields.
- Mapped categorical values such as customer tiers, product types, and store locations.

### 3. **Data Modeling in Power BI**
- Imported cleaned datasets into Power BI.
- Created a star schema by defining relationships between dimension tables (Customer, Product, Store) and fact tables (Sales, Returns).
- Added calculated columns and measures using DAX (Data Analysis Expressions) for metrics like:
  - Total Sales
  - Gross Profit
  - Profit Margin
  - Return Rate
  - Monthly Trends

### 4. **Dashboard Design & Visualization**
- Designed five interactive dashboards tailored for key business areas: Customers, Products, Returns, Sales, and Stores.
- Used filters, slicers, cards, and interactive charts (bar, line, pie, map visuals) to allow deep data exploration.
- Each dashboard was focused on answering a specific business question and highlighting KPIs.

### 5. **Insight Extraction**
- Key takeaways were noted directly from the dashboards using visual summaries.
- High-return products, top-performing cities, and high-LTV customers were identified.
- Sales and return trends were analyzed over time to inform seasonal planning.

### 6. **Export and Documentation**
- Exported final dashboards as high-resolution images for documentation.
- Performed OCR (Optical Character Recognition) to transcribe visual text insights where necessary.
- Compiled screenshots and findings into this README and a detailed report.

## 🖼️ Dashboard Screenshots

### 1. Customer Insights
![Customer Insights](images/Customer%20Insights.png)

### 2. Product Analysis
![Product Analysis](images/Product%20Analysis.png)

### 3. Return Analysis
![Return Analysis](images/Return%20Analysis.png)

### 4. Sales Analysis
![Sales Analysis](images/Sales%20Analysis.png)

### 5. Store Analysis
![Store Analysis](images/Store%20Analysis.png)


## 👤 Author
Rohit Mhala  
*Data Science Student | Power BI Enthusiast*
