# MSCS 634 — Lab 4
## Regression Analysis with Regularization Techniques

**Student:** Abhilash Reddy Marthala

## Purpose
Compare simple linear, multiple, polynomial, Ridge, and Lasso regression
for predicting disease progression using the scikit-learn Diabetes dataset.

## Dataset
- 442 observations
- 10 input features
- Continuous disease-progression target
- Loaded directly with sklearn.datasets.load_diabetes

## Methods
- 80/20 train/test split with random_state=42
- BMI-only simple and polynomial regression
- All ten features for multiple, Ridge, and Lasso regression
- Five-fold training-set cross-validation for polynomial degree and alpha
- Preprocessing performed inside model pipelines

## Evaluation
Models were evaluated using MAE, MSE, RMSE, and R².

## Key Insights
- Lowest test RMSE: [model and value]
- Selected polynomial degree: [value]
- Selected Ridge alpha: [value]
- Selected Lasso alpha: [value]
- Effect of polynomial degree: [your observation]
- Effect of regularization: [your observation]

## Decisions and Challenges
Describe your actual experience. Possible topics include:
- Using the same split for consistent comparisons
- Standardizing features before regularization
- Selecting hyperparameters without using test-set results
- Interpreting training versus validation error
- Any installation or convergence issues you encountered

## Files
- Lab_4_Regression_Analysis.ipynb: Executed notebook with analysis and plots
- README.md: Project overview and findings

## How to Run
1. Install numpy, pandas, matplotlib, seaborn, scikit-learn, and notebook.
2. Open Lab_4_Regression_Analysis.ipynb in Jupyter.
3. Run all cells from top to bottom.