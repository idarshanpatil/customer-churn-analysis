# 📊 Customer Churn Analysis

## 📌 Project Overview  
Customer churn occurs when customers stop doing business with a company. Analyzing churn patterns helps organizations **understand customer behavior, identify risk factors, and design retention strategies**.  

This project performs **Exploratory Data Analysis (EDA)** on a churn dataset to uncover hidden patterns and business insights.  

The notebook includes:  
- Data cleaning & preprocessing  
- Outlier detection and treatment  
- Univariate & bivariate analysis  
- Correlation study  
- Business insights and conclusions  

---

## 📂 Dataset  
The dataset contains customer information such as:  
- **Demographics**: Age, Gender, Geography  
- **Account details**: Tenure, Balance, Number of products  
- **Banking behavior**: Credit score, Active member status, Exited (churn label)  

Target variable:  
- `Exited` → 1 if customer churned, 0 otherwise  

---

## ⚙️ Tech Stack  
- **Python 3.x**  
- **Libraries used**:  
  - `numpy`, `pandas` → Data wrangling  
  - `matplotlib`, `seaborn` → Data visualization  

---

## 🚀 Workflow  
1. **Data Preprocessing**  
   - Handled missing values  
   - Treated outliers  
   - Encoded categorical variables (if needed)  

2. **Exploratory Data Analysis**  
   - **Univariate Analysis** → Distribution of individual features  
   - **Bivariate Analysis** → Relationship of features with churn  
   - **Correlation Heatmap** → Understanding dependencies  

3. **Insights & Conclusions**  
   - Identified patterns affecting churn  
   - Suggested business recommendations  

---

## 📈 Key Insights  
- Customers with **low credit score** are more likely to churn.  
- **Older customers** show higher churn tendency.  
- Customers with **low tenure** leave faster.  
- **Inactive members** churn more compared to active members.  
- Geography plays an important role in churn differences.  

---

## 🔮 Next Steps  
- Extend project with **predictive modeling** (Logistic Regression, Random Forest, etc.)  
- Build a **dashboard (Power BI / Streamlit)** for churn visualization  
- Include **customer segmentation analysis**  

---

## 👨‍💻 Author  
**Darshan Patil**  
- Data Analyst | ML Enthusiast  
- 📧 Email: *patildarshan2702@gmail.com*   
