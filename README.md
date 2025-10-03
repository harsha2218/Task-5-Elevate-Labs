#  Task 5: Exploratory Data Analysis (EDA)

##  Objective
Extract insights from the **Bank Customer Churn Dataset** using statistical and visual exploration techniques.

## 🛠️ Tools & Libraries
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook


## 📂 Project Files
- `Bank Customer Churn Prediction.csv` → Dataset  
- `EDA.ipynb` → Jupyter Notebook with EDA code  
- `EDA Report.pdf` → PDF report of findings  

## 🔑 Steps Followed
1. **Basic Exploration**  
   - Used `.info()`, `.describe()`, `.value_counts()`  
   - Checked dataset size, columns, and target distribution  

2. **Visualizations**  
   - **Heatmap** → Correlation among numerical features  
   - **Pairplot** → Relationships between age, credit score, balance, salary  
   - **Histograms & Boxplots** → Distribution and churn trends  
   - **Scatterplots** → Balance vs Age (colored by churn)  
   - **Countplots** → Churn trends by country, gender, products, activity  

3. **Observations**  
   - ~20% of customers churned (imbalanced dataset)  
   - **Age:** Older customers (40+) churn more  
   - **Country:** Germany has the highest churn rate  
   - **Balance:** Customers with high balances churn more often  
   - **Membership:** Active members and credit card holders churn less  
   - Weak linear correlations → possible non-linear effects  

4. **Summary of Findings**
   - Customer churn is strongly linked with **age, balance, and geography**  
   - Active engagement (credit cards, activity status) reduces churn  
   - Dataset is imbalanced → useful insight for predictive modeling  



---
