# 🏛️ Analyzing U.S. Public Pension Plans (2001–2023) Using Python and Power BI

### 📊 Overview
This project analyzes the **Public Plans Database (PPD)** to explore trends in funded ratios, contributions, assets, and liabilities of major U.S. state and local government pension plans.  
It integrates **Python for data preprocessing and analytics** and **Power BI for interactive dashboards**, aiming to uncover actionable insights into pension fund performance.

---

### 🧠 Objectives
1. Clean and preprocess pension data using Python.  
2. Perform exploratory data analysis (EDA) and visualize key trends.  
3. Build predictive models to estimate funded ratios.  
4. Develop a Power BI dashboard for interactive insights.

---

### 🐍 Python Analysis
- Conducted using **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**.  
- Linear Regression model used to predict funded ratio trends.  
- Data cleaning and merging operations saved into `cleaned_data.csv`.

**Key Visualizations:**
- Funded Ratio Trend (2001–2023)
- Total Contributions Over Time
- Top 10 Pension Plans by Assets
- Correlation Analysis of Key Metrics

Refer to `PythonAnalysis.pdf` for the full code and outputs.

---

### 📈 Power BI Dashboard
The Power BI report (`Pension_plan_Dasboard.pbix`) provides:
- Overview of total assets, liabilities, and contributions.
- Interactive charts by year and state.
- Forecasts of funded ratios (2023–2028).

#### 📊 Power BI Dashboard Pages

The dashboard is divided into **three interactive pages**:

---

#### 🧭 1. Overview
- Summarizes total assets, liabilities, contributions, and funded ratios.  
- Displays key performance indicators (KPIs) and overall funding trends.  

📸 *Dashboard Preview:*  
![Overview Dashboard](overview.png)

---

#### 💰 2. Contributions & Liabilities (Details)
- Shows detailed breakdowns of **employer vs. employee contributions**.  
- Tracks **asset and liability growth** and compares them across states.  
- Enables state-level filtering for granular insights.  

📸 *Dashboard Preview:*  
![Contributions and Liabilities Dashboard](contributions_liabilities.png)

---

#### 📈 3. Prediction & Trend Analysis (2023–2028)
- Uses historical data up to 2022 to forecast funded ratios through 2028.  
- Includes **confidence intervals** and **trend lines** for predictive insight.  
- Supports interaction by year and plan for better exploration.  

📸 *Dashboard Preview:*  
![Prediction and Trend Analysis Dashboard](prediction_trends.png)

---

### 🧠 Key Insights from Public Pension Plans Analysis (2001–2023)

After analyzing the Public Plans Database using **Python** and visualizing results in **Power BI**, the following insights highlight major trends and challenges in U.S. public pension systems:

#### 🧩 1. Funded Ratios Declined After 2008 but Are Recovering
- Funded ratios fell sharply post-2008 due to market losses.  
- Recovery began around 2013, driven by stronger employer funding and investment returns.  
- Many plans still remain below the 80% sustainability threshold.  
**📊 Insight:** Recovery is ongoing, but financial resilience remains uneven across states.

#### 💰 2. Employer Contributions Drive Stability
- A strong positive correlation exists between employer contributions and funded ratios.  
- Employee contributions remain stable but have limited impact on plan solvency.  
**📊 Insight:** Consistent employer funding is the key determinant of long-term pension health.

#### 📈 3. Liabilities Outpace Asset Growth
- Assets and liabilities both increased since 2001, but liabilities grew slightly faster.  
- Expanding benefit obligations and modest returns slow overall funded ratio improvement.  
**📊 Insight:** Without policy reform or higher funding, liability growth may threaten sustainability.

#### 🌍 4. Geographic Disparities in Pension Health
- States like **Wisconsin, South Dakota, and New York** maintain funded ratios above 90%.  
- States such as **Illinois, Kentucky, and New Jersey** remain underfunded (<60%).  
**📊 Insight:** Governance quality and funding discipline explain large inter-state differences.

---

### 🗃 Files Included
| File Name | Description |
|------------|-------------|
| `pension_data.csv` | Raw dataset from the Public Plans Database |
| `cleaned_data.csv` | Cleaned dataset generated using Python |
| `Pensionplan.ipynb` | Python notebook for data analysis and visualization |
| `Pension_plan_Dasboard.pbix` | Power BI dashboard file |
| `PythonAnalysis.pdf` | PDF version of Python analysis results |

---

### ⚙️ Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)  
- **Power BI**  
- **Jupyter Notebook**

---

### 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/US_Pension_Plan_Analysis.git
```

2. Open `Pensionplan.ipynb` in Jupyter Notebook to run the analysis.
3. Open `Pension_plan_Dasboard.pbix` in Power BI Desktop to explore the dashboard.


```
---

### 👩‍💻 Author

**Megha Rajeev**
*Data Analyst | B.Tech in Information Technology*
📫 [Your Email or LinkedIn link here]

---

