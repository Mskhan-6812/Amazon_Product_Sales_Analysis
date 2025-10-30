# 🛒 Amazon Product Sales Analysis using Power BI

This project provides analytical insights into **Amazon product sales performance** using **Microsoft Power BI**.  
It highlights sales trends, top-performing products, and category performance through interactive visualizations.

---

## 🖼️ Dashboard Preview
![Amazon Sales Dashboard](Images/Dashboard_Preview.png)

> 📊 This dashboard visualizes Amazon's YTD & QTD Sales, Top Products, and Category Performance.

---

## 🎯 Project Objectives
- Analyze product-wise and category-wise sales performance  
- Identify top and least selling products  
- Understand customer purchase behavior and seasonal trends  
- Support data-driven marketing and pricing strategies  

---

## 🧰 Tools & Technologies Used
| Tool / Technology | Purpose |
|--------------------|----------|
| **Microsoft Excel** | Data Cleaning & Pre-Processing |
| **Power BI Desktop** | Data Visualization & Report Creation |
| **DAX (Data Analysis Expressions)** | KPIs and Calculations |
| **Power Query** | Data Transformation and Data Modeling |

---

## 📊 Dashboard Features
1. **Sales Overview Dashboard** – YTD & QTD sales, reviews, and product sold count  
2. **Sales by Month and Week** – Monthly and weekly sales trend visualization  
3. **Sales by Product Category** – Category-wise revenue breakdown  
4. **Top 5 Products by Sales & Reviews** – Identifies top contributors  
5. **Dynamic Filters** – Filter by product category or quarter  

---

## 📈 Key Insights
- 🥇 *Men Shoes* generated the highest total revenue (43.18%)  
- 📸 *Camera* category contributed 22.62% of total sales  
- 📅 Sales spiked in **November–December** (holiday season)  
- 💳 Credit card payments made up over **40%** of total sales  
- 👥 Top 10 customers contributed ~60% of total revenue  

---

## 🧮 DAX Measures Used
| Measure | Formula Description |
|----------|---------------------|
| **Total Sales** | `SUM(Payments[Payment_Value])` |
| **Total Quantity Sold** | `SUM(Order_Items[Quantity])` |
| **Average Order Value** | `DIVIDE([Total Sales], DISTINCTCOUNT(Orders[Order_ID]))` |
| **Monthly Growth %** | `DIVIDE(([Total Sales] - [Prev Month Sales]), [Prev Month Sales])` |

---

## 🚀 Future Enhancements
- Real-time integration with **Amazon API**  
- Predictive sales analytics using **Power BI AI visuals**  
- Customer segmentation for personalized recommendations  

---

## 🧑‍💻 Author
**Md Sahanwaj Khan**  
Master of Computer Applications (MCA)  
Galgotias College of Engineering and Technology  
📧 [your_email_here@gmail.com]  

---

## 📂 Project Files
| File Name | Description |
|------------|-------------|
| `Amazon_Sales_Analysis_Dashboard.pbix` | Power BI dashboard file |
| `Amazon_Sales_Data.xlsx` | Dataset used for analysis |
| `Amazon_Product_Sales_Analysis_Report.docx` | Detailed project report |
| `Amazon_Dashboard_Background.jpg` | Dashboard background image |
| `Images/Dashboard_Preview.png` | Screenshot of dashboard preview |

---

## 🌐 Project Repository Link
👉 [GitHub Repository – Amazon Product Sales Analysis](https://github.com/Mskhan-6812/Amazon_Product_Sales_Analysis)


