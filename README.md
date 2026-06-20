# 📊 Startup Profit Analysis

**Tools Used:** MySQL · Python (Scikit-learn, Pandas) · Power BI  
**Project ID:** PRDA-01 | **Role:** Data Analyst Intern

---

## 📌 Objective

To analyze startup company data and identify which spending factors — R&D, Administration, and Marketing — most significantly impact profit, and to build regression models to predict profit based on these variables.

---

## 📁 Dataset Description

The dataset contains financial information across startup companies with the following features:

| Column | Description |
|--------|-------------|
| `RD_Spend` | Research & Development investment |
| `Administration` | Administrative expenses |
| `Marketing_Spend` | Marketing investment |
| `State` | Startup location |
| `Profit` | Company profit (target variable) |

> **Source:** Initially analyzed using a MySQL database, then exported as CSV for Python and Power BI analysis.

---

## 🛠️ Tools & Technologies

- **MySQL** — Data storage, querying, and exploratory SQL analysis
- **Python** — Linear & Multiple Regression modeling using Scikit-learn and Pandas
- **Power BI** — Interactive dashboard for business insight visualization

---

## 🔍 Workflow

### 1. SQL Data Analysis (MySQL)
- Imported dataset into MySQL database
- Ran queries to explore relationships between spending variables and profit
- Checked for missing values and data quality issues

**Key SQL Findings:**
- R&D Spend shows a strong positive relationship with profit
- Marketing Spend also contributes positively to profit
- Administration has a weaker impact on profit
- No missing values found in the dataset

### 2. Regression Analysis (Python)
- Built a **Linear Regression** model using `RD_Spend`, `Administration`, and `Marketing_Spend` as features
- Target variable: `Profit`
- Generated **2 profit predictions** based on different spending scenarios

**Sample Predictions:**

| Prediction | RD Spend | Administration | Marketing Spend | Predicted Profit |
|------------|----------|----------------|-----------------|-----------------|
| 1 | 21,892.92 | 81,910.77 | 1,64,270.70 | **71,236.89** |
| 2 | 23,940.93 | 96,489.63 | 1,37,001.10 | **71,040.76** |

> 💡 Higher R&D and Marketing investments generally lead to higher predicted profits.

### 3. Power BI Dashboard
- Built an interactive dashboard to visualize KPIs, spending trends, and profit distribution
- Enabled business stakeholders to explore insights across states and spending categories

---

## 📈 Key Insights & Conclusions

- **R&D Spend** is the most influential factor affecting startup profit
- **Marketing investment** contributes positively to profit
- **Administration expenses** show limited impact on profit
- Linear Regression successfully predicted startup profit across scenarios
- Power BI dashboard effectively communicated business insights visually

---

## 💡 Recommendations

- Startups should **prioritize R&D investment** to maximize profit potential
- **Marketing spend** should be maintained as a secondary growth driver
- Administrative costs should be monitored and optimized, as they contribute minimally to profit growth

---

## 📂 Project Structure

```
📦 Startup-Profit-Analysis
 ┣ 📄 startup_data.csv          # Dataset
 ┣ 📄 sql_analysis.sql          # SQL queries for EDA
 ┣ 📄 profit_analysis.ipynb     # Python regression models
 ┣ 📄 dashboard.pbix            # Power BI dashboard file
 ┗ 📄 README.md
```

---

## 👩‍💻 Author

**Muskan Chib**  
Data Analyst Intern | Punjab, India  
📧 Muskanchibt08@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/)  
🔗 [GitHub](https://github.com/muskanthakur08)
