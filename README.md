# 📊 Customer Insights Statistical Analysis Project

## 🔍 Overview
This project focuses on exploring, analyzing, and understanding customer behavior using **statistics and hypothesis testing**.  
The goal was to extract meaningful insights that can support business decision-making using a dataset containing customer demographics and spending patterns.

---

## 🛠 Tools & Technologies Used
- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn

---

## 📂 Project Workflow

### 1️⃣ Data Understanding
- Loaded and explored dataset structure
- Identified categorical vs numerical features
- Checked missing values and data types

### 2️⃣ Descriptive Statistics
- Mean, median, mode, standard deviation
- Summary statistics for spending, age, and engagement

### 3️⃣ Data Visualization
- Histograms & boxplots for distribution analysis  
- Bar charts for categorical insights  
- Scatter plot to identify relationships  
- KDE plots to understand spending patterns  

### 4️⃣ Hypothesis Testing
| Test Performed | Method | Result |
|---------------|--------|--------|
| Gender vs Spending | T-test | No significant difference |
| Education vs Spending | ANOVA | No significant difference |
| State vs Spending | ANOVA | No significant difference |
| Marital Status vs Pets | Chi-Square | Significant relationship |
| Age vs Engagement | Correlation | Near zero → no relationship |

---

## 🚧 Challenges Faced
- Selecting correct statistical tests  
- Handling different data types (categorical vs numerical)  
- Interpreting statistical results into meaningful business insights  

---

## 🧠 Key Insights
- Spending did **not significantly** change across gender, education, or state.
- **Marital status strongly correlates** with number of pets owned.
- Most customers are **middle-aged with moderate spending distribution**.
- No strong relationship between customer age and recent activity.

---

## 📌 Business Recommendations
- Create engagement campaigns for inactive customers
- Target marketing around pet-related and family products
- Avoid segmentation based on gender or education as they showed no difference

---

## 📎 Files Included
| File | Description |
|------|------------|
| `Statistics_mini_project.ipynb` | Full code and analysis |
| `US_Customer_Insights_Dataset.csv` | Dataset Used |
| `README.md` | Project documentation |

---

## 🚀 Future Improvements
- Apply clustering to segment customers
- Use predictive modeling (Regression/Classification)
- Deploy results using dashboards (PowerBI/Streamlit)
