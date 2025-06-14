# 🚢 Titanic Survival Analysis using Exploratory Data Analysis (EDA)

This project analyzes passenger data from the Titanic disaster using **exploratory data analysis (EDA)** techniques. The goal is to uncover insights and patterns that influenced survival, based on various features such as age, gender, class, and more.

> 🔍 Inspired by the Kaggle notebook [Titanic Dataset Exploratory Data Analysis (EDA)](https://www.kaggle.com/code/junaiddata35/titanic-dataset-exploratory-data-analysis-eda) by [@junaiddata35](https://www.kaggle.com/junaiddata35), this project adds custom visualizations and group analysis to deepen understanding.

---

## 📁 Project Structure

```
├── titanic_eda.ipynb          # Jupyter Notebook with EDA code and plots
├── README.md                  # Project documentation (this file)
└── dataset/                   # (Optional) Directory to store Titanic dataset
```

---

## 📊 Dataset Overview

* **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)
* **Records**: 891 passengers
* **Target**: `Survived` (0 = No, 1 = Yes)
* **Key Features**:
  - `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`, `Fare`, `Embarked`

---

## 🎯 Project Objectives

* Perform detailed **data profiling and visualization**
* Identify the most influential features affecting survival
* Group passengers by categories such as age, gender, and class
* Visualize insights using countplots, heatmaps, and histograms

---

## 🔧 Key Techniques Used

1. **Data Cleaning**:
   - Handling missing values (`Age`, `Embarked`)
   - Creating derived features (`Age Group`)

2. **EDA Visualizations**:
   - Survival rate by `Sex`, `Pclass`, `Embarked`
   - Age group-based analysis using `pd.cut()`
   - Countplots and heatmaps for correlation and comparison

3. **Categorical Grouping**:
   - Bin `Age` into groups like `Child`, `Teenager`, `Adult`, etc.
   - Analyze survival trends across age groups

---

## 📈 Sample Insights

* **Women had significantly higher survival rates** than men.
* **First-class passengers** were more likely to survive.
* **Children** were prioritized during evacuation.
* Survival rate decreased with increasing age.

---

## 📷 Visuals Included

* Countplot of survival based on:
  - Gender
  - Passenger class
  - Age groups
* Correlation heatmap
* Age distribution histograms
* Survival breakdown by Embarkation port

---

## ⚙️ Technologies Used

* **Python 3**
* **Pandas**, **NumPy**
* **Matplotlib**, **Seaborn**
* **Jupyter Notebook**

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/titanic-eda-analysis.git
cd titanic-eda-analysis
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:

```bash
jupyter notebook titanic_eda.ipynb
```

---

## ✅ Future Improvements

* Build predictive model (Logistic Regression, Decision Trees)
* Add dashboard using Streamlit or Plotly Dash
* Explore deeper correlations with feature engineering

---

## 🙌 Acknowledgments
* Titanic dataset from [Kaggle Competition](https://www.kaggle.com/competitions/titanic)
