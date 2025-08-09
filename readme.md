# Medical Insurance Cost Prediction

This project predicts medical insurance charges based on demographic and health-related features using machine learning models. The goal is to help insurance companies set fair pricing policies.

## Dataset

- Source: [Kaggle - Health Insurance Cost Prediction](https://www.kaggle.com/code/priyang/health-insurance-cost-prediction-using-ml?scriptVersionId=78467794&select=insurance.csv)
- File: `insurance.csv`

## Features

- Age
- Sex
- BMI
- Number of Children
- Smoker Status
- Region

## Workflow

1. **Data Collection**: Load and inspect the dataset.
2. **Data Exploration**: Analyze missing values, data types, and summary statistics.
3. **Data Preprocessing**: Encode categorical features and scale numerical features.
4. **Feature Engineering**: Split features and apply transformations.
5. **Model Training**: Train Linear Regression, SVR, and Random Forest models.
6. **Evaluation**: Compare models using R², MAE, and RMSE metrics.
7. **Hyperparameter Tuning**: Optimize Random Forest using GridSearchCV.
8. **Visualization**: Feature importance, actual vs. predicted values, residuals, and correlation heatmap.

## Results

- Random Forest achieved the best performance with the highest R² and lowest MAE/RMSE.
- Feature importance and correlation visualizations provide insights for business decisions.

## Usage

1. Clone the repository and place `insurance.csv` in the project directory.
2. Open and run `ML_project_enhanced.ipynb` in Jupyter or VS Code.
3. Follow the notebook cells for step-by-step analysis and results.

## Requirements

- Python 3.8+
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

Install dependencies with:

```sh
pip install pandas numpy seaborn matplotlib scikit-learn
```

## License

This project is for educational purposes.
