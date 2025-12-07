# FNP Excel Sales Analytics Project (Power Query • Power Pivot • DAX)

Did a complete end-to-end sales analytics solution built using Excel’s modern BI stack.  
It transforms raw transactional data into a fully automated dashboard that highlights revenue trends, delivery performance, and customer behavior across multiple dimensions.

The dashboard is driven by:
- Power Query (ETL automation)
- Power Pivot (Data modeling)
- DAX (Business KPIs)
- Slicers & PivotCharts (Interactive insights)

---

## 🔍 Project Overview
The goal of the project was to replicate a real business reporting workflow — from messy raw files to a clean, refreshable analytics dashboard that decision-makers can rely on.

Using datasets for:
- **Orders**
- **Customers**
- **Products**

 The project uncovers insights around:
- Revenue trends over time  
- Delivery speed performance  
- Best-selling products  
- City-level demand  
- Occasion-driven purchasing behavior  
- Daily ordering patterns  
- Monthly seasonality  

All insights update instantly with a single data refresh.

---

## 🧼 Data Cleaning with Power Query
Power Query was used to automate all transformations, including:
- Normalizing inconsistent date formats  
- Extracting Month, Day, and Hour fields  
- Cleaning typos in product names  
- Handling nulls and duplicates  
- Standardizing customer fields  
- Building “Days to Deliver” from Delivery_Date – Order_Date  
- Ensuring data types are correct  
- Preparing fact and dimension tables  

This makes the dashboard refresh-ready and eliminates manual work.

---

## 🧩 Data Modeling in Power Pivot
A star schema model was created:

**Fact Table**
- Orders

**Dimension Tables**
- Customers
- Products
- Calendar fields from Power Query

Relationships allow fast calculations, proper aggregation, and accurate drill-down.

---

## 📐 KPIs Built Using DAX
Key business metrics powered by DAX include:

- **Total Revenue**
- **Average Delivery Days**
- **Average Customer Spending**
- **Product Revenue**
- **Total Revenue by Occasion**
- **Order Count by City**
- **Daily Order Performance**
- **Monthly Seasonality Patterns**

These DAX measures drive all the charts and KPI cards on the dashboard.

---

## 📊 Dashboard Features (Based on the Actual Design)
The dashboard includes:

### ✔ KPI Cards
- Total Revenue  
- Average Delivery Days  
- Average Customer Spending  

### ✔ Interactive Slicers
- Delivery Month  
- Order Month  
- Occasion  
- Category  
- Product  
- City  
- Day of Week  

### ✔ Visual Insights
- **Sales Performance by Products**  
- **Monthly Sales Performance (Trend Line)**  
- **Top Ten Cities by Order Count**  
- **Total Revenue by Occasion**  
- **Product Popularity by Occasion**
- **Daily Order Performance (Day-of-week trend)**  

Your dashboard layout is clean, consistent, and follows BI best practices — white background, blue theme, aligned charts, and well-structured slicers.

---

## 💡 Key Insights Identified
From the dashboard we observe:

- Revenue spikes during certain months (seasonality visible in the line chart).  
- Product categories such as **Colors** and **Soft Toys** outperform others significantly.  
- Certain cities like **Bhatpara**, **Bidhannagar**, and **Dhanbad** generate higher order counts.  
- Occasions such as **Anniversary** and **Diwali** contribute heavily to revenue.  
- Orders are not evenly distributed across weekdays — mid-week performance is stronger.  
- Average delivery time is around **5.53 days**, meaning operations could be optimized.

These insights reflect real business-use analytics.

---

## 🛠 Skills Demonstrated
This project demonstrates proficiency in:

- Power Query (ETL)
- Data modeling in Power Pivot
- DAX calculations
- Dashboard design principles
- KPI development
- Sales analytics interpretation
- Storytelling with data

---

## 📁 Files Included
- Cleaned datasets (Customers, Orders, Products)  
- Power Query M-code transformations  
- Power Pivot model  
- DAX measures  
- Final dashboard (Excel)  


