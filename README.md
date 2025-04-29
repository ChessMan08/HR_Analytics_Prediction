# HR Analytics Prediction

This project analyzes employee attrition using HR data and explores the key factors behind why individuals leave their organizations. The goal is to uncover insights and build a predictive model to understand attrition trends better.

## 🔍 Project Overview

I examined employee data to understand patterns in attrition. Key observations include:

- **Early-career switches**: Employees tend to switch jobs more often at the beginning of their careers.
- **Impact of compensation**: Higher salaries and stock options significantly reduce attrition rates.
- **Work-life balance paradox**: While good work-life balance is valued, it can encourage switching for even better opportunities.
- **Department-wise trends**: Departments like Sales, where performance is target-driven, see higher attrition than administrative roles.
- **Job and environment satisfaction**: Dissatisfaction with job roles or work environment is a strong predictor of resignation.

## 📊 Data Analysis

I performed visual analysis using:

- Age vs Attrition
- Income vs Attrition
- Department-wise attrition
- Job & Environment Satisfaction impacts
- Stock options and retention
- Work-life balance and its dual nature
- Role of experience, promotions, and managers

## 🧠 Model Building

A **Logistic Regression** model was trained to predict employee attrition using various features from the dataset, including:

- Demographic data
- Compensation metrics
- Work experience and satisfaction levels
- Department and role-specific encodings

### Model Accuracy:

- **Training Accuracy**: ~0.895
- **Test Accuracy**: ~0.899

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Seaborn, Matplotlib, Plotly
- Scikit-learn

## 📁 Dataset

We used the publicly available dataset: `WA_Fn-UseC_-HR-Employee-Attrition.csv`

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/your-username/hr-analytics-prediction.git
cd hr-analytics-prediction
```

## Install dependencies

```bash
pip install -r requirements.txt
```

## 📈 Visual Examples

Plots generated include:

- Attrition trends by Age
- Impact of Income and Work-life Balance
- Role of Manager, Promotions, and Stock Options

## 📜 License

This project is licensed under the MIT License.
