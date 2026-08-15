🚗 Used Car Price Prediction

📌 Overview

A machine learning regression project that predicts the selling price of a used car based on vehicle specifications, ownership details, usage, and seller information.

The project follows an end-to-end machine learning workflow, including data preprocessing, exploratory data analysis, categorical encoding, feature selection, model training, evaluation, and price prediction.

⸻

🎯 Objective

The objective of this project is to develop a machine learning model that can estimate the selling price of a used car from historical vehicle data.

This project demonstrates how machine learning can be applied to a real-world regression problem involving both numerical and categorical features.

⸻

📊 Dataset

The project uses a used-car dataset containing information about vehicles, their original prices, usage, fuel type, transmission, seller type, and ownership history.

Features Used

Feature	Description	Type
Year	Manufacturing year of the car	Numerical
Present_Price	Current/ex-showroom price of the car	Numerical
Kms_Driven	Total kilometers driven	Numerical
Fuel_Type	Fuel used by the vehicle — Petrol, Diesel, CNG	Categorical
Seller_Type	Type of seller — Dealer or Individual	Categorical
Transmission	Transmission type — Manual or Automatic	Categorical
Owner	Number of previous owners	Numerical

Target Variable

Selling_Price — The price at which the used car is expected to be sold.

Excluded Feature

Car_Name is not used as a model feature because the project focuses on vehicle characteristics rather than the individual car name.

⸻

🛠️ Tech Stack

Programming Language

* Python

Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

Development Environment

* Jupyter Notebook

Machine Learning

* Linear Regression
* Lasso Regression

⸻

🔄 Project Workflow

Data Collection
      ↓
Data Loading
      ↓
Data Understanding
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Categorical Feature Encoding
      ↓
Feature Selection
      ↓
Train-Test Split
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Selling Price Prediction

⸻

🔍 Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the relationships between vehicle attributes and selling price.

The analysis includes:

* Distribution of selling prices
* Relationship between Present_Price and Selling_Price
* Impact of Kms_Driven
* Effect of vehicle Year
* Comparison of selling prices across fuel types
* Comparison between manual and automatic vehicles
* Effect of seller type
* Analysis of previous ownership
* Correlation analysis between numerical variables

Visualizations were created using Matplotlib and Seaborn.

⸻

⚙️ Data Preprocessing

The following preprocessing steps were performed:

* Loading the dataset using Pandas
* Checking dataset dimensions and data types
* Identifying missing values
* Removing unnecessary features
* Encoding categorical variables
* Preparing independent and dependent variables
* Splitting the dataset into training and testing sets

Categorical variables such as:

Fuel_Type
Seller_Type
Transmission

are converted into numerical representations so they can be used by machine learning algorithms.

⸻

🤖 Machine Learning Models

1. Linear Regression

Linear Regression is used to establish a baseline relationship between the input features and the target variable.

The model learns how factors such as present price, kilometers driven, vehicle age, fuel type, transmission, seller type, and ownership affect the selling price.

2. Lasso Regression

Lasso Regression is a regularized linear regression algorithm that applies L1 regularization.

It helps control model complexity and reduces the influence of less important features.

⸻

📈 Model Evaluation

The trained models are evaluated on unseen test data to determine their prediction performance.

Evaluation can include regression metrics such as:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

The model performance can then be compared to determine which approach provides better predictions.

⸻

📁 Project Structure

Car-Price-Prediction/
│
├── data/
│   └── car_data.csv
│
├── notebooks/
│   └── Car_Price_Prediction.ipynb
│
├── README.md
│
└── requirements.txt

Update the folder structure if your actual repository uses different file or folder names.

⸻

⚡ Installation

Clone the repository:

git clone https://github.com/YOUR-USERNAME/Car-Price-Prediction.git

Navigate to the project directory:

cd Car-Price-Prediction

Install the dependencies:

pip install -r requirements.txt

⸻

▶️ Running the Project

Start Jupyter Notebook:

jupyter notebook

Open:

Car_Price_Prediction.ipynb

Run the notebook cells sequentially to:

1. Load the dataset
2. Explore the data
3. Preprocess the features
4. Train the regression models
5. Evaluate model performance
6. Generate car price predictions

⸻

📦 Requirements

numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter

⸻

💡 Key Skills Demonstrated

* Python Programming
* Data Cleaning & Preprocessing
* Exploratory Data Analysis
* Feature Engineering
* Categorical Encoding
* Data Visualization
* Regression
* Linear Regression
* Lasso Regression
* Model Evaluation
* Machine Learning Workflow
* Git & GitHub

⸻

🚀 Future Improvements

* Implement additional regression algorithms such as Random Forest, XGBoost, and Gradient Boosting
* Perform hyperparameter tuning
* Implement cross-validation
* Improve feature engineering
* Build an interactive Streamlit interface
* Deploy the trained model as a web application
* Add model performance comparison and visualization

⸻

👨‍💻 Author

Shreyas Kocheri

B.E. — Robotics & Artificial Intelligence

⸻

⭐ If you found this project useful, consider giving the repository a star.