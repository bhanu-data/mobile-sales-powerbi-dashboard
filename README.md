# 📱 Mobile Sales Analytics: Interactive Power BI Dashboard

An interactive business intelligence dashboard built using Microsoft Power BI to analyze mobile sales performance, customer ratings, payment preferences, and product trends across cities, brands, and mobile models.

## 📌 1. Project Overview

The **Mobile Sales Analytics Dashboard** is an interactive Power BI report designed to transform mobile sales data into meaningful business insights. It provides a consolidated view of key performance indicators (KPIs), geographical sales distribution, daily sales trends, customer ratings, payment methods, and brand-level performance.

The dashboard enables users to explore sales patterns through interactive filters and visualizations, helping identify high-performing products, understand customer preferences, and monitor overall sales performance.

## 🎯 2. Business Problem & Objectives

### Business Problem

Mobile retailers generate large volumes of sales and transaction data across different brands, mobile models, cities, and payment methods. Without a centralized analytical view, it can be difficult to monitor sales performance, compare products, identify geographical trends, and understand customer purchasing behavior.

### Project Objectives

- Monitor overall sales performance using key business metrics.
- Analyze sales distribution across cities and geographical regions.
- Compare sales performance across mobile brands and individual models.
- Understand daily sales and quantity trends.
- Evaluate customer ratings to explore customer satisfaction patterns.
- Analyze transaction distribution across different payment methods.
- Enable interactive exploration of sales data through filters and slicers.

## 🛠️ 3. Tech Stack

The dashboard was developed using the following tools and technologies:

- **Microsoft Power BI Desktop:** Primary platform used to develop the dashboard and create interactive data visualizations.
- **Power Query:** Used for data cleaning, transformation, and preparation, in the project.
- **DAX (Data Analysis Expressions):** Used to create calculated measures and KPIs, if applicable.
- **Data Modeling:** Used to organize tables, establish relationships, and support analytical calculations, if applicable.
- **Microsoft Bing Maps:** Geographical visualization of sales distribution across cities, as displayed in the dashboard.

## 📂 4. Data Source

The dashboard is based on a mobile sales dataset containing information about sales transactions, brands, mobile models, customer ratings, payment methods, and geographical locations.

### Key Data Dimensions

- **Sales Metrics:** Sales amount, quantity sold, and transaction counts.
- **Product Information:** Mobile brands and individual mobile models.
- **Geographical Information:** Cities associated with mobile sales.
- **Customer Information:** Customer ratings associated with purchases.
- **Payment Information:** UPI, debit card, cash, and credit card transactions.
- **Time Dimensions:** Month, day name, and daily sales activity.

## 📊 5. Dashboard Features & Visualizations

### 5.1 Key Performance Indicators (KPIs)

The top section of the dashboard provides a consolidated view of the main sales metrics:

- **Total Sales:** Displays the overall sales value.
- **Total Quantity:** Represents the total quantity of mobile units sold.
- **Transactions:** Shows the number of recorded transactions.
- **Average:** Displays the average sales metric defined in the report.

These indicators provide a quick overview of business performance and respond to the dashboard's interactive filters.

### 5.2 Geographical Sales Analysis

**Visualization:** Map — Total Sales by City

The geographical map displays sales distribution across cities in India, helping users explore regional differences in sales performance.

**Analytical purpose:**
- Identify cities with relatively high sales.
- Compare geographical sales distribution.
- Explore regional opportunities for further investigation.

### 5.3 Daily Quantity Analysis

**Visualization:** Line Chart — Total Quantity by Day

This visualization tracks the quantity of mobile units sold across the days represented in the report.

**Analytical purpose:**
- Observe changes in daily sales volume.
- Identify days with relatively high or low quantities sold.
- Investigate fluctuations in purchasing activity.

### 5.4 Customer Ratings Analysis

**Visualization:** Bar Chart — Customer Ratings

The ratings chart displays the distribution of customer ratings from 1 to 5.

**Analytical purpose:**
- Understand the distribution of customer feedback.
- Compare the frequency of different rating levels.
- Identify rating patterns that may warrant further investigation.

### 5.5 Payment Method Analysis

**Visualization:** Pie Chart — Transactions by Payment Method

The payment analysis compares the proportion of transactions made using UPI, debit cards, cash, and credit cards.

**Analytical purpose:**
- Understand customer payment preferences.
- Compare the contribution of different payment methods to transaction volume.
- Support further analysis of payment behavior.

### 5.6 Brand Performance Analysis

**Visualization:** Table — Sales Performance by Brand

The table compares brands using total sales, transactions, and total quantity.

**Analytical purpose:**
- Compare sales performance across mobile brands.
- Evaluate transaction volume by brand.
- Examine differences between sales value and units sold.

### 5.7 Mobile Model Performance

**Visualization:** Bar Chart — Total Sales by Mobile Model

This chart compares sales values across individual mobile models.

**Analytical purpose:**
- Identify high-performing mobile models.
- Compare sales contributions across products.
- Support product-level performance analysis.

### 5.8 Day-of-Week Sales Analysis

**Visualization:** Line and Area Chart — Total Sales by Day Name

This visualization compares sales across the days of the week.

**Analytical purpose:**
- Explore differences in sales between weekdays and weekends.
- Identify days with relatively high or low sales.
- Investigate recurring patterns in customer purchasing activity.

### 5.9 Interactive Filters & Slicers

The dashboard includes interactive controls for:

- Month
- Mobile Model
- Payment Method
- Brand
- Day Name

These controls allow users to filter the report and examine sales performance across different dimensions.

## 💡 6. Business Impact & Potential Insights

The dashboard provides a foundation for data-driven retail analysis by bringing key sales indicators and product-level metrics into one interactive report.

Potential business applications include:

- **Sales Monitoring:** Track overall sales performance and transaction volume.
- **Regional Analysis:** Explore geographical differences in mobile sales.
- **Product Strategy:** Compare brands and mobile models to identify products for further analysis.
- **Customer Experience:** Examine rating distributions to identify areas for customer satisfaction research.
- **Payment Strategy:** Understand payment method preferences when planning payment experiences.
- **Sales Planning:** Investigate daily and weekday sales patterns to support promotional planning.

### Key Findings


### Key Findings

- **Overall Sales Performance:** The dashboard reports total sales of **769M**, providing a high-level view of mobile sales performance across the dataset.
- **Sales Volume:** A total quantity of **19K units** is displayed, highlighting the overall volume of mobile products sold.
- **Transaction Activity:** The dashboard records approximately **4K transactions**, offering an overview of sales activity.
- **Average Sales Metric:** The displayed average is **40K**, providing an additional measure for evaluating sales performance.
- **Brand Performance:** The brand comparison table shows Apple with the highest displayed total sales among the five visible brands, at **16,161,573**, followed by Vivo at **15,008,428**, Samsung at **16,003,805**, OnePlus at **15,371,943**, and Xiaomi at **14,375,337**.
- **Mobile Model Performance:** The mobile model chart shows iPhone SE with approximately **60M** in sales, followed by OnePlus Nord at **58M** and Galaxy Note 20 at **56M**.
- **Payment Preferences:** UPI accounts for **26.25%** of transactions, followed by debit card at **25.89%**, cash at **25.03%**, and credit card at **22.83%**.
- **Customer Ratings:** The visible ratings chart shows **185 five-star ratings**, **137 four-star ratings**, **119 three-star ratings**, and **67 two-star ratings**. These displayed counts suggest that five-star ratings are the most frequent among the categories shown.
- **Day-of-Week Sales Trends:** The chart shows higher sales on Monday, Tuesday, and Wednesday, at approximately **26.4M**, **26.4M**, and **26.2M**, respectively. Sales are lower on Thursday through Sunday, with Sunday showing approximately **23.2M**.
- **Geographical Analysis:** The city map enables comparison of sales distribution across Indian cities, helping users explore regional differences and identify locations for further investigation.

**Business Takeaway:** The dashboard brings together sales KPIs, product performance, payment preferences, customer ratings, and geographical distribution in one interactive report. These insights can support further investigation into high-performing products, customer preferences, and variations in sales performance.


## 🖼️ 7. Dashboard Preview

![Mobile Sales Analytics Dashboard] https://github.com/bhanu-data/mobile-sales-powerbi-dashboard/blob/main/Mobile%20Sales%20Dashboard.png

## 📁 8. Repository Structure

```text
mobile-sales-powerbi-dashboard/
│
├── Mobile_Sales_Dashboard.pbix
├── dashboard_overview.png
└── README.md
```

## 🚀 9. How to Explore the Project

1. Clone or download this repository.
2. Open `Mobile_Sales_Dashboard.pbix` using Microsoft Power BI Desktop.
3. If prompted, configure the required data source or file path.
4. Refresh the data if the source is available and refresh is required.
5. Explore the report using the available filters and slicers.
6. Review the charts, KPI cards, and tables to investigate sales patterns.

## 🔮 10. Potential Future Enhancements

- Add month-over-month and year-over-year sales comparisons, where suitable data is available.
- Introduce profit and profit-margin analysis if cost and revenue data are available.
- Add sales growth indicators and target-versus-actual performance.
- Create drill-through pages for detailed brand and mobile model analysis.
- Improve geographical analysis with regional comparisons and additional location details.
- Publish the report through an appropriately secured Power BI sharing solution.

## 👨‍💻 11. Author

**Bhanu Pratap Singh**

Data Analyst | Business Intelligence | Power BI | SQL | Python

GitHub: [Your GitHub Profile](https://github.com/YOUR-USERNAME)

---

*This project demonstrates the use of interactive business intelligence visualizations to explore sales performance, product trends, customer ratings, and payment behavior using Microsoft Power BI.*
