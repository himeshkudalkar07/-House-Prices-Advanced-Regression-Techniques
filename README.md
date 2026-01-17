House Prices Prediction using Machine Learning
This project solves the Kaggle competition “House Prices: Advanced Regression Techniques” by building an end-to-end machine learning pipeline to predict house sale prices using structured real-estate data.

📌 Project Objective
To predict the final SalePrice of houses based on various numerical and categorical features such as location, size, quality, and construction details.

The evaluation metric used is Root Mean Squared Error (RMSE) on log-transformed prices.

📊 Kaggle Result
Public Score: 0.12644

Competition: House Prices – Advanced Regression Techniques

Ranking: Top ~30% globally

⚙️ Tech Stack
Python

Pandas, NumPy

Scikit-learn

LightGBM

Google Colab / Jupyter Notebook

🔍 Workflow
Data loading and inspection

Missing value handling using domain logic

Feature engineering:

Total square footage

House age

Total bathrooms

Categorical encoding using One-Hot Encoding

Log transformation of target variable

Cross-validation using K-Fold

Model training using LightGBM

Prediction and Kaggle submission

🧠 Machine Learning Model
The primary model used is:

LightGBM Regressor

Chosen for its performance on structured tabular datasets and ability to handle complex feature interactions efficiently.

📈 Performance Evaluation
Cross-validation RMSE used for validation

Kaggle public leaderboard score used for final evaluation

📁 Repository Structure
powershell
Copy code
House-Prices-Kaggle-Regression/
│
├── house_prices_model.ipynb
├── submission.csv
├── README.md
🚀 How to Run
Download the Kaggle dataset from the competition page

Upload train.csv and test.csv into the notebook environment

Run all cells in house_prices_model.ipynb

Generate submission.csv

Upload submission to Kaggle

🏆 Learning Outcomes
This project helped me understand:

Real-world data preprocessing challenges

Feature engineering importance

Handling categorical variables effectively

Cross-validation strategies

Model tuning and evaluation

End-to-end ML pipeline development

📌 Kaggle Link
House Prices Competition:
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

🙌 Author
Himesh Kudalkar
BTech – Artificial Intelligence & Data Science
