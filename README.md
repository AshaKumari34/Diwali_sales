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
  `User_ID, Cust_name, Gender, Age Group, State, Occupation, Marital_Status, Product_Category, Orders, Amount`

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
  - Remove columns(status,unnamed1)
**2.Checked missing values**
  - Found missing value in amount and handel them using fillna method with median imputation.
**3.Add new columns**
  - Add new columns (Total_spending,High_Spender,Spender_Category)
**4.Use level segmentation** 
  - Amount divied into level segmentation using conditional statement 
**5.Remove Whitespaces**  
  - Remove whitespaces using strip methods for spaces in columns and cell values.
**6.Rename columns**
  - Rename the cust_name using rename method.  

# EDA(Exploratory Data Analysis)  

**1.which group of customers should we target more in Diwali sales?** 
![Customer Segmentation](images/Customer_segmentation.png)











```bash
git clone https://github.com/<your-username>/diwali-sales-analysis.git
cd diwali-sales-analysis
pip install -r requirements.txt