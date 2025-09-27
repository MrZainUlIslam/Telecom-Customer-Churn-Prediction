This project aims to predict customer churn for a telecom company using machine learning techniques. Customer churn prediction is crucial for businesses to retain customers and reduce revenue loss.

**Key Objectives:**
- Identify factors that contribute to customer churn
- Build predictive models to flag at-risk customers
- Provide actionable insights for customer retention strategies

## 📊 Dataset

The project uses the **Telco Customer Churn** dataset from Kaggle, containing information about:
- 7,043 customers
- 21 features including demographic info, services subscribed, account information
- Target variable: Churn (Yes/No)

**Dataset Features:**
- **Demographic info**: gender, age, partner, dependents
- **Services subscribed**: phone, multiple lines, internet service, online security, etc.
- **Account information**: tenure, contract type, payment method, monthly charges, total charges

## 🔧 Features

### Data Preprocessing
- Missing value handling
- Data type conversion
- Outlier detection
- Data validation

### Feature Engineering
- Created tenure groups (0-1 Year, 1-2 Years, etc.)
- Monthly charge categorization (Low, Medium, High, Very High)
- Total services count
- Internet service flags
- Customer value calculation

### Exploratory Data Analysis
- Univariate and bivariate analysis
- Correlation heatmaps
- Distribution plots
- Churn rate analysis across different segments

### Machine Learning Models
- Logistic Regression
- Random Forest
- Gradient Boosting
- Support Vector Machines
- Neural Networks

## 🚀 Installation

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Required Python packages

### Installation Steps

1. **Clone the repository**
```bash
git clone https://github.com/MrZainUlIslam/Telecom-Customer-Churn-Prediction.git
cd Telecom-Customer-Churn-Prediction
