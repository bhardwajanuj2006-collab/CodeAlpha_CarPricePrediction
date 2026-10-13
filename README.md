🚗 Car Price Prediction Using Machine Learning
📌 Project Overview

This project was developed as Task 3 of my Machine Learning Internship at CodeAlpha. The objective is to build a machine learning model that predicts car prices based on various vehicle features.

The project uses Python and popular data science libraries to perform data preprocessing, exploratory data analysis, feature engineering, model training, and evaluation.

🎯 Objectives
Analyze a car price dataset using Pandas and NumPy.
Clean and preprocess the dataset.
Extract brand information from car names.
Train regression models to predict car prices.
Compare Linear Regression and Random Forest Regression.
Evaluate model performance using MAE, RMSE, and R² score.
Visualize actual versus predicted prices and analyze feature importance.
🛠️ Technologies Used
Python – Programming language
Pandas – Data manipulation and analysis
NumPy – Numerical computations
Matplotlib – Data visualization
Scikit-learn – Machine learning and model evaluation
Jupyter Notebook – Development environment
Joblib – Saving the trained model
📂 Dataset

The project uses the carprice_assignment.csv dataset, containing vehicle specifications such as:

Car brand
Fuel type
Car body
Engine size
Horsepower
Curb weight
City and highway mileage
Other vehicle specifications
Price (target variable)
⚙️ Project Workflow
Import libraries and load the dataset.
Explore the data and identify missing values and duplicate records.
Clean the dataset and prepare the features.
Extract brand information from car names.
Separate input features and target prices.
Split the data into training and testing sets.
Train Linear Regression and Random Forest Regression models.
Evaluate model performance using MAE, RMSE, and R².
Visualize predictions and feature importance.
Save the trained model for future use.
📊 Model Evaluation

The models are evaluated using:

Mean Absolute Error (MAE): Measures the average absolute prediction error.
Root Mean Squared Error (RMSE): Penalizes larger prediction errors more heavily.
R² Score: Measures how well the model explains variation in car prices.

The best-performing model is selected based on the evaluation results.

▶️ How to Run the Project
Clone or download this repository.
Install the required libraries:
   pip install pandas numpy matplotlib scikit-learn joblib jupyter

Place carprice_assignment.csv in the project directory.
Open the Jupyter Notebook.
Run the notebook cells in order to train and evaluate the models.
🌟 Applications
Used-car price estimation
Vehicle valuation
Supporting data-driven pricing decisions
Understanding the relationship between car specifications and market prices
🎓 Learning Outcomes

Through this project, I gained practical experience in data preprocessing, feature engineering, regression modeling, model evaluation, and data visualization.

👩‍💻 Internship

Organization: CodeAlpha
Task: Task 3 – Car Price Prediction
Domain: Machine Learning

⚠️ Disclaimer

The predicted prices are estimates based on patterns learned from the available dataset. Actual market prices may vary depending on vehicle condition, location, demand, and other factors.
