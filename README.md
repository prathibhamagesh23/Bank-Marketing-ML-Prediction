# Bank Marketing ML Prediction

Predicting customer subscription to term deposits using machine learning. A two-phase course project exploring data analysis and predictive modeling on real-world bank marketing data.

## 📋 Project Overview

This project analyzes customer behavior from a Portuguese bank's marketing campaign and builds machine learning models to predict whether customers will subscribe to a term deposit. The analysis spans two phases:

- **Phase 1:** Exploratory Data Analysis (EDA) and data understanding
- **Phase 2:** Predictive modeling with multiple ML algorithms and performance evaluation

## 🎯 Problem Statement

Given customer demographics, account information, and previous campaign history, predict whether a customer will subscribe to a term deposit (binary classification).

**Dataset:** Bank Marketing (UCI ML Repository)
- **Samples:** 4,119 customer records
- **Features:** 20 (age, job, education, account details, campaign info, economic indicators)
- **Target:** Subscription status (yes/no) — ~11% positive class

## 📁 Project Structure

```
phase_1/              # Exploratory Data Analysis
├── Phase1_Group_52__1_.ipynb    # Main EDA notebook
├── Phase1_Group_52__2_.csv      # Dataset
└── Phase1_Group_52__2_.html     # HTML report

phase_2/              # Predictive Modeling
├── Phase2_Group52___1_.ipynb    # Modeling notebook
├── Phase2_Group52__1_.csv       # Dataset
└── Phase2_Group52___1_.html     # HTML report
```

## 🔍 Phase 1: Exploratory Data Analysis

**Key Activities:**
- Data loading and initial exploration (shape, dtypes, missing values)
- Univariate analysis (distributions, outliers)
- Bivariate analysis (feature correlations with target)
- Class imbalance assessment
- Feature importance insights

**Outputs:**
- Statistical summaries and visualizations
- Data quality assessment
- Recommendations for Phase 2 modeling

## 🤖 Phase 2: Predictive Modeling

**Modeling Pipeline:**
1. Data preparation (outlier handling, encoding, scaling)
2. Train/test split
3. Model training (multiple algorithms)
4. Hyperparameter tuning
5. Performance evaluation and comparison
6. Recommendation of best model

**Models Evaluated:**
- Logistic Regression
- Random Forest
- Gradient Boosting
- Neural Networks (if included)
- *Additional algorithms as per notebook*

**Evaluation Metrics:**
- Accuracy, Precision, Recall, F1-Score
- ROC-AUC, Confusion Matrix
- Cross-validation scores

## 🛠️ Technologies & Libraries

- **Python 3.x**
- **Pandas** – Data manipulation
- **NumPy** – Numerical computing
- **Matplotlib & Seaborn** – Visualization
- **Scikit-learn** – Machine learning models & preprocessing
- **Jupyter Notebook** – Analysis environment

## 📊 Key Findings (Summary)

*(Update with your Phase 2 results:)*

- Best performing model: [Model name] with [metric] score
- Important features: [Top 3-5 features]
- Key insights: [Main takeaways from analysis]

## 💾 Dataset

**Source:** [UCI Machine Learning Repository - Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)

**Features Include:**
- Demographic: age, job, marital status, education
- Account: credit default, housing loan, personal loan
- Campaign: contact type, duration, campaign count, previous outcomes
- Economic: employment rate, consumer price index, EUR interest rate

**Citation:** Moro et al., 2014

## 🚀 Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/prathibhamagesh23/bank-marketing-ml-prediction.git
   cd bank-marketing-ml-prediction
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```

3. Run notebooks:
   ```bash
   jupyter notebook phase_1/Phase1_Group_52__1_.ipynb
   jupyter notebook phase_2/Phase2_Group52___1_.ipynb
   ```

4. View HTML reports for summary visualizations

## 📝 Course Context

- **Course:** MATH2319 Machine Learning
- **Institution:** RMIT University
- **Assessment:** 2-phase project
- **Group:** 52

## 📈 Next Steps / Future Work

- Cross-validation with different random seeds for robustness
- Handling class imbalance with SMOTE or stratified sampling
- Feature engineering (interaction terms, polynomial features)
- Deployment-ready model serialization (pickle/joblib)
- API wrapper for predictions
- Real-time campaign strategy recommendations

## 👥 Authors

Group 52 – RMIT Data Science
Prathibha Magesh

