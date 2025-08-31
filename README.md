# 🎆Diwali Sales Data Analysis(EDA Project)

This project performs **Exploratory Data Analysis (EDA)** on Diwali Sales Data using Python.  
The goal is to analyze customer purchasing behavior, product performance, and sales trends.  

It is part of my **portfolio** and can also be used as an **interview showcase project**.

---

## 📌 Project Overview
- Loaded & cleaned sales dataset
- Performed data preprocessing using **Pandas** & **NumPy**
- Conducted **Exploratory Data Analysis (EDA)**
- Created **visualizations** with **Matplotlib** & **Seaborn**
- Generated **key business insights** to improve sales strategy
- Generated  **Business Recommendations**

---

## 📂 Dataset
- Dataset: `Diwali Sales Data.csv`  
- Contains sales records with customer demographics & purchase details.  
- Columns include:  
  `'User_ID', 'Customer_name', 'Product_ID', 'Gender', 'Age Group', 'Age',
       'Marital_Status', 'State', 'Zone', 'Occupation', 'Product_Category',
       'Orders', 'Amount', 'Total_spending', 'High_Spender',
       'Spender_Category'`

---
# Usage 
Run the jupyter notebook to explore the analysis

---
# Technologis used
- Jupyter Notebook:-For analysis & run
- Python
- Pandas:-For data cleaning,manipulation or analysis
- Numpy:-For numerical operation
- Matplotlib & Seaborn:-For Data Visualization

---

## Data Cleaning Performed

**Removed unnecessary columns**
  - Remove columns(status,unnamed1)<br>
**2.Checked missing values**
  - Found missing value in amount and handel them using fillna method with median imputation.<br>
**3.Add new columns**
  - Add new columns (Total_spending,High_Spender,Spender_Category)<br>
**4.Use level segmentation** 
  - Amount divied into level segmentation using conditional statement <br>
**5.Remove Whitespaces**  
  - Remove whitespaces using strip methods for spaces in columns and cell values.<br>
**6.Rename columns**
  - Rename the cust_name using rename method.<br>  

# EDA(Exploratory Data Analysis)  

## 1.which group of customers should we target more in Diwali sales?
used:-<br>
*Pie chart*:-For  Distribution of Spender category<br>
*Bar Chart*:- For Customer count in each category.<br>

Shows the percentage distribution<br>
![Customer Segmentation](images/Customer_segmentation.png)<br>
Shows the actual customer count<br>
![Customer Count](images/CustomerCount.png)
## Observation<br>
**Medium Spender** 58.9%:-majority of customers belong to Medium Spender segment, providing a stable revenue base.<br>
**High Spender** 21.6%:-smaller number of customers, but contributing significantly to revenue.<br>
**Low Spender** 19.5%:-opportunity for targeted marketing and upselling to increase revenue.
## Overall Insights
- Most revenue comes from Medium and High Spenders<br>
- There is a significant opportunity to increase revenue by converting Low Spenders into Medium/High Spenders<br>
- Medium Spenders form the backbone of stable sales during Diwali.
## Tips
- Design festive offers and loyalty programs to encourage Medium and Low Spenders to spend more
- Target Low Spenders with promotions to convert them into higher spending segments.(ex:-offers/discounts/coupons)
- Focus marketing campaigns on High-value customers for maximizing revenue.(ex:-special ads, festive coupons, premium offers)

##Which gender contributes more to overall revenue?
used:-<br>
bar chart:-shows absolute comparsion between male and female<br>
![Revenue_Contributes](images/RevenueContribution.png)




















```bash
git clone https://github.com/<your-username>/diwali-sales-analysis.git
cd diwali-sales-analysis
pip install -r requirements.txt