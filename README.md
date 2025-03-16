# Predicting Churn with KNN

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)  
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-0.24%2B-orange)  
![Data Science](https://img.shields.io/badge/Data%20Science-KNN-green)

## Overview
This project applies the **K-Nearest Neighbors (KNN)** algorithm to predict customer churn based on demographic and service usage data. By analyzing patterns, we can classify customers into different service groups and identify those at risk of churning.

## Dataset
The dataset consists of customer information, including:
- **Demographics**: Age, Region, Marital Status
- **Service Usage**: Tenure, Income, Employment Status
- **Target Variable**: `custcat` (Customer Category with four groups)

## Steps
1. **Data Preprocessing**: Handling missing values, standardizing features
2. **Exploratory Data Analysis (EDA)**: Visualizing data distributions
3. **Feature Selection**: Identifying important attributes for classification
4. **Model Training**: Applying KNN with different `k` values
5. **Evaluation**: Finding the best `k` value based on accuracy

## Results
- The best accuracy was observed with **k=9**, as determined through model evaluation.
- Standardization improved classification performance.

## Tech Stack
- **Python** (NumPy, Pandas, Matplotlib, Scikit-learn)
- **Jupyter Notebook**

## Running the Project
```bash
# Clone the repository
git clone https://github.com/RNNivash/Predicting-Churn-with-KNN.git  
cd Predicting-Churn-with-KNN  

# Install dependencies  
pip install -r requirements.txt  

# Run the Jupyter Notebook  
jupyter notebook  
```

## Contributing
Feel free to fork this repo, create a new branch, and submit a pull request with improvements!

---

💡 **Author**: [Nivash R N](https://www.linkedin.com/in/nivash-r-n/)  
🔗 **Portfolio**: [rnnivash.github.io/My_Port/](https://rnnivash.github.io/My_Port/)  
