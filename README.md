# BlackFriday
This project predicts the purchase amount of customers during the Black Friday sale event using machine learning models. The goal is to understand customer purchasing behavior based on features such as age, gender, product categories, and city category. Various machine learning techniques, including LightGBM, have been applied to predict the target variable, Purchase.

Data Preprocessing-
Handling Missing Values: Missing values in product categories (Product_Category_2 and Product_Category_3) were filled with 0, assuming that missing values represent a lack of category.
Label Encoding: Categorical variables such as Age, Gender, Stay_In_Current_City_Years, and City_Category were label encoded to convert them into numerical values for model compatibility.
Feature Scaling: Scaling was not required as most features are already in a suitable numerical format for LightGBM.


Feature Engineering
Interaction Terms: New interaction features were created between product categories to capture relationships between them.
Age_Gender: Product of Age and Gender.
Product_Category_1_2: Interaction between Product_Category_1 and Product_Category_2.
Product_Category_2_3: Interaction between Product_Category_2 and Product_Category_3.


Modeling
LightGBM Model: We utilized LightGBM, a powerful gradient boosting algorithm, to predict the Purchase amount.
Model Evaluation: The model was evaluated using cross-validation, and performance was measured using metrics like Mean Squared Error (MSE).


Evaluation
The model's performance is evaluated using metrics such as Mean Squared Error (MSE) to assess how well it predicts the purchase amount. Cross-validation techniques were employed to ensure robustness and generalizability of the model.
