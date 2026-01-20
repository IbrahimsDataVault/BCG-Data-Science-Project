# BCG Data Science Project - PowerCo Customer Churn Analysis

## Project Overview

This repository contains a comprehensive data science project analyzing customer churn for PowerCo, a major gas and electricity utility company. The project was developed as part of a BCG consulting engagement to identify key drivers of customer churn and build predictive models to help reduce customer attrition.

## Business Context

PowerCo is experiencing significant customer churn in their SME (Small & Medium Enterprise) segment. The hypothesis is that price sensitivity is a major factor driving churn. This project aims to:

- Analyze customer behavior and identify churn patterns
- Engineer relevant features from historical data
- Build predictive models to forecast customer churn
- Provide actionable insights for customer retention strategies

## Project Structure

### Task 2 - PowerCo EDA (Exploratory Data Analysis)
Exploratory analysis of customer and pricing data to understand churn patterns and relationships.

**Key Files:**
- `Task 2 - PowerCo_EDA.ipynb` - Comprehensive exploratory data analysis notebook
- `client_data.csv` - Customer demographic and usage data
- `price_data.csv` - Historical pricing information
- `data_description` - Data dictionary describing all fields

### Task 3 - Feature Engineering
Development of predictive features from raw data to improve model performance.

**Key Files:**
- `Task 3 - feature_engineering.ipynb` - Feature engineering notebook
- `clean_data_after_eda.csv` - Cleaned dataset after EDA
- `enhanced_data_after_feature_engineering.csv` - Dataset with engineered features
- `final_engineered_features.csv` - Final feature set for modeling

### Task 4 - Random Forest Modeling
Predictive modeling using Random Forest classifier to predict customer churn.

**Key Files:**
- `Task 4 - Random_Forest_Model.ipynb` - Model development and evaluation
- `enhanced_features_for_model.csv` - Features used for training
- `data_for_predictions.csv` - Dataset for making predictions
- `churn_predictions_for_business.csv` - Final churn predictions

## Key Deliverables

- **BCG - Executive Summary.pdf** - High-level summary and recommendations for stakeholders
- **Predictive Models** - Random Forest classifier for churn prediction
- **Feature Importance Analysis** - Identification of key drivers of churn
- **Business Recommendations** - Data-driven strategies for customer retention

## Technologies Used

- **Python** - Primary programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib & Seaborn** - Data visualization
- **Scikit-learn** - Machine learning modeling
- **Jupyter Notebook** - Interactive development environment

## Key Findings

The analysis revealed:

1. Price sensitivity is a significant factor in customer churn
2. Consumption patterns correlate with churn behavior
3. Contract renewal dates present critical intervention points
4. Customer tenure and engagement metrics are strong predictors

## Model Performance

The Random Forest model achieved:
- High accuracy in predicting customer churn
- Identification of at-risk customers for targeted retention campaigns
- Feature importance rankings to guide business strategy

## Installation & Usage

```bash
# Clone the repository
git clone https://github.com/IbrahimsDataVault/BCG-Data-Science-Project.git

# Install required packages
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Launch Jupyter Notebook
jupyter notebook
```

## Project Workflow

1. **Data Exploration** - Analyze customer and pricing data to understand patterns
2. **Data Cleaning** - Handle missing values, outliers, and data quality issues
3. **Feature Engineering** - Create predictive features from raw data
4. **Model Development** - Train and evaluate Random Forest classifier
5. **Business Insights** - Translate model results into actionable recommendations

## Author

**Ibrahim Ibrahim**
- Data Scientist & Analytics Professional
- GitHub: [@IbrahimsDataVault](https://github.com/IbrahimsDataVault)

## Acknowledgments

- BCG for the project framework and business context
- PowerCo for providing the data and business problem

## License

This project is for educational and portfolio purposes.

---

*Last Updated: January 2026*
