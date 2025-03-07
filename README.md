<h1 align="center">Data Analyst Roadmap 📊</h1>

**I am sharing my journey of **#100DaysofData** into Data Analytics.

Learning through the resources provided by **COACHX.LIVE classes** and all the guided projects.

**Data Analytics** is the process of exploring and analyzing large datasets to find hidden patterns, unseen trends, discover correlations, and derive valuable insights to make business predictions.

It helps in Improved Decision Making, Better Customer Service, Efficient Operations, Effective Marketing and Improves the Speed and Efficiency of the business.

Businesses use many modern tools and technologies to perform Data Analytics. 

📌 Follow me for Hands-on projects, business insights & job-ready skills on 
        www.linkedin.com/in/priyankataklikar
        
## Technologies Learned ⚙️

* <a href="https://www.javatpoint.com/dbms-tutorial">Database Management System (DBMS)</a><a href="https://www.javatpoint.com/dbms-tutorial" target="_blank" rel="noreferrer">
* <a href="https://www.tpointtech.com/sql-tutorial">Structure Query Langauge (SQL)</a><a href="https://www.tpointtech.com/sql-tutorial" target="_blank" rel="noreferrer">
* <a href="https://docs.python.org/3/tutorial/">Python</a><a href="https://docs.python.org/3/tutorial/" target="_blank" rel="noreferrer">
* <a href="https://www.khanacademy.org/math/statistics-probability">Statistics & Probability</a><a href="https://www.khanacademy.org/math/statistics-probability" target="_blank" rel="noreferrer">

<h1 align="center">Day 1: 100 Days of learning Data Analysis</h1> 

🔹 Announcing My 100-Day Data Analyst Challenge! 🔹
Over the next 100 days, I’ll be sharing daily learnings on Excel, SQL, Power BI, and Python, covering real-world case studies, projects, and insights.

🎯 Goal: Build a strong portfolio and share my journey as a data analyst.

👥 How You Can you Connect and Join:
🔹 Follow along and share your thoughts.
🔹 Try the examples & post your solutions.
🔹 Ask questions or suggest topics.

<h2 align="center">Excel 📊</h2>

<h2 align="center">Day 2: Excel for Data Analysis</h2> 

🚀 Day 2: Basic Excel Functions for Data Analysis

💡 Why Excel first?
Excel is the foundation of data analysis. From data cleaning to visualization and reporting, mastering Excel will help me build a strong analytical mindset before diving into advanced tools.

✅ Excel functions for data analysis

Explored some fundamental Excel functions that every Data Analyst must know!

📊 Key Functions & Their Uses:

✅ SUM(range): Adds up all the values in a range. 

✅ AVERAGE(range): Calculates the mean of selected numbers. 

✅ COUNT(range): Counts the number of numeric values.

✅ COUNTA(range): Counts all non-empty cells (including text & numbers).

✅ MIN(range): Returns the smallest value in a range.

✅ MAX(range): Returns the largest value in a range.

✅ ROUND(value, decimals): Rounds a number to the specified decimal places.

🛠 Example: Suppose we have a Sales Dataset 📈:

![image](https://github.com/user-attachments/assets/50a00647-1945-48fe-91ea-66c66fa68efb)

📌 Applying the functions:
 
➡️ Total Sales: =SUM(B2:B6) → ₹50,500

➡️ Average Sales: =AVERAGE(B2:B6) → ₹10,100

➡️ Total Products Sold: =COUNTA(A2:A6) → 5

➡️ Highest Sale: =MAX(B2:B6) → ₹15,300

➡️ Lowest Sale: =MIN(B2:B6) → ₹5,000

➡️ Rounded Avg Sales (No Decimal): =ROUND(AVERAGE(B2:B6),0) → ₹10,100

<h2 align="center">Day 3: Excel for Data Analysis</h2> 

🚀 Day 3: Mastering Conditional Functions in Excel!

Today in my #100DaysOfData journey, I explored some powerful conditional functions in Excel that help analyze data based on specific conditions. 

These functions are essential for data analysts when filtering, summarizing, and extracting insights from datasets.

📌 Key Conditional Functions & How They Work

✅ IF(logical_test, value_if_true, value_if_false)
 👉 Returns different values based on a condition.
 📌 Example: Identify if a purchase amount is above ₹10,000
 =IF(B2>10000, "High Value", "Regular")
 
✅ COUNTIF(range, criteria)
 👉 Counts the number of cells that meet a specific condition.
 📌 Example: Count how many customers spent more than ₹10,000
 =COUNTIF(B2:B20, ">10000")
 
✅ SUMIF(range, criteria, sum_range)
 👉 Sums values based on a condition.
 📌 Example: Total sales from purchases above ₹10,000
 =SUMIF(B2:B20, ">10000", B2:B20)
 
✅ AVERAGEIF(range, criteria, average_range)
 👉 Finds the average of values that meet a condition.
 📌 Example: Average purchase amount for high-value customers
 =AVERAGEIF(B2:B20, ">10000", B2:B20)
 
✅ SUMIFS(sum_range, criteria_range1, criteria1, ...)
 👉 Sums values based on multiple conditions.
 📌 Example: Total sales from high-value customers who purchased electronics
 =SUMIFS(C2:C20, B2:B20, ">10000", D2:D20, "Electronics")
 
✅ COUNTIFS(criteria_range1, criteria1, ...)
 👉 Counts cells based on multiple conditions.
 📌 Example: Count customers who spent more than ₹10,000 and purchased electronics
 =COUNTIFS(B2:B20, ">10000", D2:D20, "Electronics")
 
✅ AVERAGEIFS(average_range, criteria_range1, criteria1, ...)
 👉 Finds the average of values based on multiple conditions.
 📌 Example: Average purchase amount for high-value customers buying electronics
 =AVERAGEIFS(C2:C20, B2:B20, ">10000", D2:D20, "Electronics")
 
✅ MAXIFS(max_range, criteria_range1, criteria1, ...)
 👉 Finds the maximum value based on a condition.
 📌 Example: Highest purchase amount among high-value customers
 =MAXIFS(C2:C20, B2:B20, ">10000")
 
✅ MINIFS(min_range, criteria_range1, criteria1, ...)
 👉 Finds the minimum value based on a condition.
 📌 Example: Lowest purchase amount among high-value customers
 =MINIFS(C2:C20, B2:B20, ">10000")

📌** Using the formulas above, we can:**
 ✅ Identify high-value customers (IF function)
 
 ✅ Count how many high-value purchases were made (COUNTIF)
 
 ✅ Calculate the total revenue from high-value customers (SUMIF)
 
 ✅ Find the average amount spent by high-value customers (AVERAGEIF)
 
 ✅ Apply multiple conditions, like filtering purchases by category (SUMIFS, COUNTIFS, AVERAGEIFS, MAXIFS, MINIFS)

 ![image](https://github.com/user-attachments/assets/4f6c7647-1ea8-4724-a555-565ea81a0fbc)

![image](https://github.com/user-attachments/assets/1d02a1c4-43b9-4fa5-a000-a798d270af41)

![image](https://github.com/user-attachments/assets/c7d349ad-bb48-4219-8f91-b54b218780ea)
