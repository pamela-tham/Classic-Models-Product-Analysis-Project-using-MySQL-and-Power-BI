# 🚗 Classic Models Database Analysis 🚗

Welcome to the **Classic Models Database Analysis** project! This project aims to analyze sales and performance data of a fictional company that sells classic car models. The data is sourced from the [MySQL Tutorial Sample Database](https://www.mysqltutorial.org/getting-started-with-mysql/mysql-sample-database/), which is widely used for learning relational database structures and SQL querying. 

Through this analysis, we aim to gain insights into product performance, customer behaviour, and sales trends to support business decision-making.



---

## 🔧 Tools & Technologies Used

- **MySQL**:  
  The **Classic Models Database** is set up and hosted in a **MySQL** environment. This database contains information about classic cars, customers, orders, payments, and more.

- **Power BI**:  
  Used to perform **Exploratory Data Analysis (EDA)** and visualize the data.  
  - **Power Query**: Used to **extract**, **transform**, and **clean** the data from the MySQL database.
  - **DAX Measures**: Used to calculate custom metrics like revenue, cost, profit , average price etc.

---

## 📊 Project Overview

The goal of this project is to perform detailed analysis on the **sales and performance** of the company using data from the **Classic Models Database**. The data is extracted from MySQL, transformed in **Power BI** using **Power Query**, and then visualized in multiple dashboards for actionable insights.

---

## 🧹 Data Collection & Cleaning

### 1. **Setup MySQL Database**
   - The **Classic Models Database** was set up by running the provided **SQL script** in a MySQL environment.
   - Imported the database into **Power BI** by connecting to the MySQL database directly.

### 2. **Data Extraction**
   - Extracted relevant data from the following tables:
     - **Customers**: Customer details
     - **Orders**: Order details, including status and shipping information
     - **Products**: Information about products and product lines
     - **Payments**: Payment details for each order
     - **Offices**: Information about office locations and sales regions

### 3. **Data Cleaning & Transformation**
   - **Power Query** was used to clean the data by:
     - Renaming columns for clarity
     - Ensuring correct **data types** (e.g., dates, numeric)
     - Handling **missing values**, **duplicates**, and **inconsistent entries**
     - **Formatting errors** were addressed (e.g., currency formatting, date formatting)
   - Established **relationships between tables** in Power BI to enable a comprehensive analysis.
   - Used **DAX measures** to calculate essential metrics like **total revenue**, **profit**, and **order quantities**.

---

## 📈 Dashboards Created

Three dashboards were created to provide key insights and facilitate easy analysis:

### 1. **Executive Dashboard**
   - **Purpose**: Provides an overview of the company’s performance with high-level KPIs.
   - **Metrics**: 
     - Total **revenue** and **profit** by product line
     - **Top-performing products**
     - **Sales by region**
     - **Top countries** for sales and revenue
     - **Yearly sales trend**
    
       ![image](https://github.com/user-attachments/assets/6ffbf47b-43ea-497e-b36a-8d67b5f1323c)


### 2. **Product Analysis Dashboard**
   - **Purpose**: Focuses on the performance of various products and product lines.
   - **Metrics**:
     - **Total sales revenue** by product line
     - **Top-selling products** by order quantity
     - **Cancelled products**
     - **Most profitable products** by revenue
![image](https://github.com/user-attachments/assets/40021910-6fa9-4b60-a126-fb56509cd6e8)

### 3. **Customer Analysis Dashboard**
   - **Purpose**: Analyzes customer behavior and trends.
   - **Metrics**:
     - Customer distribution by **country**
     - **Sales by customer demographics** (e.g., age, region)
     - **Repeat customer analysis**
     - **Top customers by revenue**
  ![image](https://github.com/user-attachments/assets/6f3be2df-1520-44b8-b22e-fff3631c5030)

---

## 💡 Insights from the Analysis

Here are some key findings from the analysis:

### 1. **Most Successful Product Line**
   - **Classic Cars** is the most successful product line with:
     - **Revenue**: $1.85M
     - **Sales Orders**: 17,000 orders
   - **Trains** is the least successful product line with only:
     - **Revenue**: $88K
     - **Sales Orders**: 1,400 orders

### 2. **Top-Ordered Products**
   - The **1992 Ferrari 360 Spider Red** is the most ordered product, signaling its high demand and popularity among customers.
   - The **Mayflower (ship model)** is the most cancelled product, indicating low customer satisfaction or issues with availability.

### 3. **Top Profitable Countries**
   - The top three profitable countries in terms of revenue are:
     - **USA**: $1.6M (50% of total orders in 2004-2005)
     - **France**: Significant contribution to revenue
     - **Spain**: Continues to be a high-revenue region
   - **Philippines** is the least profitable market with only **$16K** in revenue, followed by **Australia**.

---

## 💡 Actionable Insights & Recommendations

### 1. **Focus on Expanding Classic Cars Product Line**
   - Given the success of the **Classic Cars** product line, consider increasing marketing efforts and expanding the product offerings to target more customers.
   - Evaluate the potential for **cross-selling** or bundling **Classic Cars** with complementary products (e.g., accessories or memorabilia).

### 2. **Reevaluate the Trains Product Line**
   - The **Trains** product line is underperforming significantly. A detailed investigation is needed to understand the reasons behind its poor performance (e.g., low demand, pricing issues, lack of promotional efforts).
   - Consider **discontinuing** or **rebranding** the product line or introducing new models to increase interest.

### 3. **Boost Marketing in Underperforming Markets**
   - **Philippines** and **Australia** have low sales. Investigate the reasons behind this through customer surveys, market research, and competitive analysis.
   - Tailor marketing strategies to **local tastes** and adjust **pricing strategies** for these regions to increase market penetration.

### 4. **Address Product Cancellations**
   - Focus on the **Mayflower ship model** to identify reasons for cancellations. Consider improving product descriptions, availability, or customer service to reduce cancellations.
   - Offer **promotions** or **discounts** to incentivize customers to proceed with orders.

### 5. **Leverage USA Market for Future Growth**
   - Since **USA** is the most profitable market, further **customize** offerings to U.S. customers' preferences. Investigate the possibility of launching new products or services tailored to this market.

---

## 🖼️ Visual Dashboards

Here are some sneak peeks from the dashboards:

### 1. **Executive Dashboard**  
   ![Executive Dashboard](https://via.placeholder.com/800x400.png?text=Executive+Dashboard)

### 2. **Product Analysis Dashboard**  
   ![Product Analysis Dashboard](https://via.placeholder.com/800x400.png?text=Product+Analysis+Dashboard)

### 3. **Customer Analysis Dashboard**  
   ![Customer Analysis Dashboard](https://via.placeholder.com/800x400.png?text=Customer+Analysis+Dashboard)


---

## 📝 Conclusion

This project provides valuable insights into the **sales performance**, **product popularity**, and **regional trends** of the **Classic Models** company. By focusing on high-performing product lines and investigating underperforming regions, the company can improve its **sales strategy** and achieve better market penetration.

### Let's continue driving business growth with **data-driven decisions**! 🚗📊✨

---

*Happy analyzing!* 🎉
