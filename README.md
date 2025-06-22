## 📘 Power BI Project Report – *Adventure_Works.pbix*

**Author:** Anshul Taliyan
**Tool Used:** Microsoft Power BI Desktop
**Project Type:** Business Intelligence Dashboard (Practice Project)

---

### 🎯 Objective

The objective of this project is to build an interactive dashboard using Power BI to gain meaningful insights from business data. The report demonstrates the use of data visualization, transformation, and modeling techniques to answer business questions and support decision-making.

---

### 📁 Data Overview

* **Source:** Custom dataset (imported via Excel or CSV)
* **Data Categories:**

  * Product/Service Information
  * Sales or Booking Data
  * Customer Details
  * Region/Location-based Metrics
  * Date and Time Dimensions

---

### 🔧 Data Transformation (Power Query)

* Cleaned null and inconsistent values
* Removed duplicates
* Changed data types appropriately
* Added custom columns (e.g., Month Name, Year, Category Split)
* Merged and appended tables as needed

---

### 📐 Data Modeling

* Established **relationships** between dimension and fact tables (e.g., Sales ↔ Product, Customer ↔ Orders)
* Created a **calendar table** for time-based slicing
* Implemented a **star schema** for optimal performance

---

### 📊 Measures & Calculated Columns (DAX)

Some important DAX formulas used:

* **Total Sales:** `SUM(Sales[Amount])`
* **Profit Margin:** `DIVIDE(Sales[Profit], Sales[Revenue])`
* **YTD Sales:** `TOTALYTD([Total Sales], 'Date'[Date])`
* **Top Performing Product:** `RANKX` used to rank products by revenue
* **Customer Count:** `DISTINCTCOUNT(Customer[ID])`

---

### 📈 Visualizations Included

The report contains multiple pages with the following types of visuals:

#### **1. Overview Dashboard**

* Total Sales, Revenue, Profit (KPI Cards)
* Sales Trend Line by Month
* Map Visual (Sales by Region)

#### **2. Product Analysis**

* Bar Chart: Revenue by Product Category
* Pie Chart: Sales Distribution
* Table: Top 10 Products by Sales

#### **3. Customer Insights**

* Funnel Chart: Customer Journey (Leads → Orders → Conversions)
* Donut Chart: Customer Segmentation
* Customer Retention Trend

#### **4. Time-Based Analysis**

* Line Chart: Monthly/Quarterly Sales
* Slicer: Year, Month, and Quarter Filters
* Matrix Table: Sales by Product and Month

#### **5. Interactive Features**

* Cross-filtering between visuals
* Slicers for Region, Category, and Time
* Drill-through to individual product/customer level

---

### 📌 Key Insights Derived

* Identified peak months for sales activity
* Recognized underperforming product categories
* Evaluated customer engagement based on segmentation
* Detected regional trends in revenue and booking behavior

---

### 🧠 Learning Outcome

* Developed end-to-end reporting skills in Power BI
* Enhanced data modeling with proper relationships and DAX usage
* Built an executive-ready dashboard for decision-makers
* Strengthened data storytelling through visuals and interactivity

---

### 📎 Future Enhancements

* Add real-time data refresh capability
* Incorporate R or Python visuals for advanced analysis
* Embed Power BI report into a website or internal portal
