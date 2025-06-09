# Titanic Dataset Exploratory Data Analysis (EDA)

This project explores the famous [Titanic dataset from Kaggle](https://www.kaggle.com/c/titanic/data) using Python and key data science libraries. The goal is to extract insights about passenger survival using visual and statistical analysis.

---

## 📁 Files Included

- `Titanic_EDA.ipynb` — Jupyter Notebook with complete EDA code and visuals
- `Titanic_EDA_Report.pdf` — Polished PDF report of findings
- `train.csv` — Input dataset (downloaded from Kaggle)

---

## 🧪 Tools & Libraries Used

- **Python 3.x**
- **Pandas** — Data manipulation
- **Matplotlib / Seaborn** — Data visualization
- **NumPy** — Numerical operations
- **FPDF** — PDF generation (for exporting report)

---

## 📊 Key EDA Steps

1. **Dataset Overview**
   - Checked data types and missing values
   - Used `.info()`, `.describe()`, `.value_counts()`

2. **Cleaning**
   - Handled missing `Age` values with median
   - Dropped rows with missing `Embarked`
   - Dropped `Cabin` due to high missingness

3. **Univariate Analysis**
   - Analyzed distribution of `Survived`, `Pclass`, `Sex`, `Age`, `Fare`
   - Visualized with histograms, boxplots, countplots

4. **Feature Engineering**
   - Created `Family_Size` and `Is_Alone` features

5. **Multivariate Analysis**
   - Plotted correlations using heatmaps and pairplots
   - Found strong relationships between `Sex`, `Pclass`, `Fare`, and survival

---

## 📌 Summary of Findings

- Women had significantly higher survival rates.
- First-class passengers were more likely to survive.
- Passengers traveling with small families had better chances.
- Higher ticket fare correlated with survival.

---

## 📈 Next Steps

- Build predictive models (e.g., logistic regression, random forest)
- Incorporate external Titanic data for enriched features

---

## 📎 How to Run

1. Clone this repository or download files.
2. Ensure you have Python and required libraries installed.
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Titanic_EDA.ipynb
