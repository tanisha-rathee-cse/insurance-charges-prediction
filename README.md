# Insurance Charges Prediction

A machine learning regression project that predicts medical insurance charges based on personal and health-related factors.

## Dataset
Insurance dataset with the following features: age, sex, BMI, number of children, smoker status, and region. Target variable: `charges`.

## Project Workflow
1. Data cleaning and exploratory data analysis (EDA)
2. Feature engineering (BMI categories) and encoding of categorical variables
3. Correlation analysis between features and charges
4. Train-test split (80-20, `random_state=42`)
5. Model training using Linear Regression
6. Evaluation using R² score

## Key Findings
- Smoker status has the strongest correlation with charges (0.79)
- Age and BMI (obesity) also influence charges
- Region has a very weak effect on charges

## Results
- **R² Score:** 0.80

## Tools & Libraries
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Future Improvements
- Add interaction features (e.g., smoker × BMI)
- Try Random Forest and Gradient Boosting models
- Hyperparameter tuning

## How to Run
1. Clone the repository
2. Install the required libraries: `pip install pandas numpy matplotlib seaborn scikit-learn`
3. Open `insurance_charges_prediction.ipynb` in Jupyter Notebook and run all cells
