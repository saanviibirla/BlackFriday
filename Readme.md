# Black Friday Sales Analysis

## Project Overview
This project analyzes Black Friday sales data to identify trends,
patterns, and insights that can help drive business decisions. Using
Python and various data science techniques, the project focuses
on exploring customer demographics, purchase behaviors, and other key
factors that influence sales during Black Friday.

# Key Features :
- Data Cleaning and Preprocessing: Handle missing values, data type conversions, and other preprocessing steps to prepare data for analysis.
- Exploratory Data Analysis (EDA): Visualize data distributions and relationships, including customer demographics, purchase patterns, and product categories.
- Machine Learning Model: Build and evaluate a predictive model (likely with XGBBoost) to forecast sales or identify high-value customers.
- Feature Engineering: Enhance the dataset with new features that improve model performance and insights.


# Technologies and Tools :

- Python: Programming language for data manipulation and model building.
- Pandas & NumPy: Libraries for data manipulation and numerical operations.
- Matplotlib & Seaborn: For data visualization during EDA.
- Scikit-learn: For data preprocessing and model evaluation.
- XGBBOOST: A gradient boosting framework for building predictive models.

# File Structure
- main.ipynb: Main Jupyter notebook that contains the entire workflow, from data cleaning to model evaluation.

```bash
pip install -r requirements.txt
```
Note: Ensure requirements.txt lists all required packages (e.g., pandas, numpy, matplotlib, seaborn, scikit-learn, lightgbm).


View Results: At the end of the notebook, you'll find key insights, visualizations, and model evaluation metrics.

## Analysis Steps
- Data Cleaning and Preprocessing
- Remove or impute missing values.
- Convert data types as needed.
- Normalize or scale features if required.
- Exploratory Data Analysis (EDA)
- Visualize age and gender distributions, product categories, and purchase amounts.
- Identify trends in customer segments and purchasing habits.
- Feature Engineering

Create new features that add predictive power (e.g., aggregating purchase history or grouping product categories).
Modeling with XGBBOOST

## Model selection
Train a model to predict key targets, such as purchase amounts or high-value customer likelihood.
Fine-tune the model to achieve optimal accuracy.
Evaluation

Measure model performance using metrics such as accuracy, precision, recall, and F1 score.

## Results
We were able to get an RMSE of 2535 & Analystics Vidhya ranking of 636 in the leaderboard
the rmse can surely be lowered by tuning the hyperparameters of the model and boosting techniques can 
be applied as per the user's choice. 

## Output screenshots are present

Hope you like the project :)

