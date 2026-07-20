# 📈 Banking Stock Performance Analysis Dashboard

An end-to-end Data Analytics project that demonstrates the complete analytics workflow, starting from raw data preprocessing, building a simple Data Warehouse, designing SQL-based Key Performance Indicators (KPIs), and developing an interactive Power BI dashboard for business analysis.

This project aims to transform raw historical banking stock market data into meaningful business insights that can support investment analysis and decision-making through interactive data visualization.

---

# 🎯 Project Objectives

The primary objectives of this project are:

* Perform data cleaning and preprocessing using Python.
* Build a simple Data Warehouse using a Star Schema model.
* Design analytical KPIs using SQL queries.
* Develop an interactive Power BI dashboard.
* Generate actionable insights from historical banking stock data.
* Demonstrate an end-to-end Data Analytics workflow suitable for Business Intelligence projects.

---

# 📂 Dataset

This project utilizes historical stock price data from several major Indonesian banking companies.

The dataset contains daily trading information, including:

* Date
* Stock Code
* Open Price
* High Price
* Low Price
* Close Price
* Adjusted Close Price
* Trading Volume

After preprocessing, the cleaned dataset is stored for further analysis and visualization.

---

# ⚙️ Project Workflow

```text
Raw Dataset
      │
      ▼
Data Cleaning & Preprocessing (Python)
      │
      ▼
Feature Engineering
      │
      ▼
Simple Data Warehouse
      │
      ▼
SQL KPI Calculation
      │
      ▼
Power BI Dashboard
      │
      ▼
Business Insights
```

---

# 🛠️ Tools & Technologies

| Technology       | Purpose                       |
| ---------------- | ----------------------------- |
| Python           | Data Cleaning & Preprocessing |
| Pandas           | Data Manipulation             |
| Jupyter Notebook | Data Processing               |
| SQL              | KPI Calculation               |
| SQL Server       | Data Warehouse                |
| Power BI         | Dashboard Development         |
| Git & GitHub     | Version Control & Portfolio   |

---

# 📁 Repository Structure

```text
banking-stock-performance-analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── pemrosesan_data.ipynb
│
├── sql/
│   ├── create_tables.sql
│   ├── insert_data.sql
│   └── kpi_queries.sql
│
├── powerbi/
│   └── Dashboard.pbix
│
├── docs/
│   └── KPI.pdf
│
├── images/
│   ├── dashboard.png
│   ├── workflow.png
│   └── star_schema.png
│
└── README.md
```

---

# 🏗 Data Warehouse Design

A simple Star Schema is implemented to support analytical queries.

### Dimension Tables

* Dim Date
* Dim Stock
* Dim Time (if applicable)

### Fact Table

* Fact Trading

The warehouse structure enables efficient aggregation, filtering, and KPI calculations for Power BI reporting.

---

# 📊 Key Performance Indicators (KPIs)

The dashboard includes several business-oriented KPIs, including:

### 📌 Total Trading Volume

Measures the total number of traded shares during the observation period.

---

### 📌 Average Adjusted Close Price

Displays the average adjusted closing price across all banking stocks.

---

### 📌 Average Year-over-Year (YoY) Growth

Calculates the average annual stock price growth for each company.

---

### 📌 Average Daily Volatility

Measures average daily market fluctuations based on the difference between High and Low prices.

---

### 📌 All-Time High

Shows the highest stock price achieved during the analysis period.

---

### 📌 All-Time Low

Shows the lowest stock price recorded during the analysis period.

---

# 📈 Power BI Dashboard

The dashboard provides interactive visualizations that allow users to explore stock performance through multiple perspectives.

Dashboard features include:

* Executive KPI Cards
* Stock Performance Trends
* Trading Volume Analysis
* Year-over-Year Growth Comparison
* Daily Volatility Analysis
* Interactive Filters
* Company-Level Drilldown
* Time-Based Analysis

> **Dashboard Preview**

Replace the image below with your dashboard screenshot.

```markdown
![Dashboard](images/dashboard.png)
```

---

# 💡 Business Insights

Some key insights generated from the dashboard include:

* Trading volume varies significantly across banking companies, indicating differences in market liquidity.
* Adjusted closing prices reveal long-term stock performance after considering corporate actions.
* Certain banking stocks consistently outperform others in terms of annual growth.
* Daily volatility analysis helps identify stocks with higher investment risk.
* Historical price trends enable users to evaluate long-term market behavior.

The dashboard supports quick exploration and decision-making through interactive filtering and visual analytics.

---

# 🚀 Skills Demonstrated

This project demonstrates practical skills in:

* Data Cleaning
* Data Transformation
* Feature Engineering
* Data Warehousing
* SQL Query Development
* Business Intelligence
* KPI Design
* Data Visualization
* Dashboard Development
* Analytical Thinking
* GitHub Portfolio Development

---

# 📚 Learning Outcomes

Through this project, I gained hands-on experience in building a complete Data Analytics pipeline, from transforming raw datasets into structured analytical models to presenting business insights using interactive dashboards.

This project strengthened my understanding of data preprocessing, Data Warehouse concepts, SQL analytics, and Business Intelligence reporting using Power BI.

---

# 🔮 Future Improvements

Potential enhancements for future versions include:

* Automating the ETL pipeline.
* Connecting Power BI directly to SQL Server.
* Adding forecasting models using Machine Learning.
* Deploying dashboards through Power BI Service.
* Integrating real-time stock market data.
* Expanding the Data Warehouse with additional financial indicators.

---

# 📷 Project Screenshots

## Dashboard

```markdown
images/dashboard.png
```

## Star Schema

```markdown
images/star_schema.png
```

## Workflow

```markdown
images/workflow.png
```

---

# 👨‍💻 Author

**Armanta Tarigan**

Information Systems Graduate | Data Analyst Enthusiast

**Skills**

* Python
* SQL
* Power BI
* Data Warehouse
* Data Visualization
* Business Intelligence
* ETL
* Data Analytics

---

# ⭐ Support

If you find this project useful, feel free to give this repository a ⭐ on GitHub.

Thank you for visiting this project!
