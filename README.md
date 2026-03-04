# 💰 Predicting Restaurant Tips with Linear Regression
This project demonstrates how to build and evaluate a __Linear Regression__ model to predict restaurant tips based on customer and billing features.  
The analysis is implemented in a Jupyter Notebook and walks through data exploration, preprocessing, model training, and evaluation.



## 📌 Project Overview
The goal of this project is to:
* Explore relationships between features such as total bill, party size, gender, smoker status, and time.
* Build a __Linear Regression__ model to predict the tip amount.
* Evaluate model performance using regression metrics.
* Interpret feature importance and coefficients.  

This notebook is designed as a hands-on introduction to regression modeling and exploratory data analysis using Python.


## Project Structure
```
.
│
├── src/
│   └── PredictingTips_LinearRegression.ipynb   # Main Jupyter Notebook
├── requirements.txt
└── README.md                               # Project documentation

```


## 🛠️ Technologies Used
* Python 3.x
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib / Seaborn
* Scikit-learn


## 📊 Workflow
The notebook follows a structured machine learning pipeline:  

1️⃣ __Data Exploration__
* Load dataset
* Inspect data types and missing values
* Generate summary statistics
* Visualize relationships between variables  

2️⃣ __Data Preprocessing__
* Encode categorical variables
* Feature selection
* Train-test split  

3️⃣ __Model Building__
* Train a Linear Regression model
* Fit the model on training data  

4️⃣ __Model Evaluation__
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score
* Residual analysis  

5️⃣ __Interpretation__
* Analyze regression coefficients
* Understand which factors most influence tipping behavior


## 🚀 How to Run the Project
1. __Clone this repository__:  
```
git clone https://github.com/Sahar-Salmanz/tip_prediction.git
```

2. __Navigate to the project directory__:
```
cd tip_prediction
```

3. __Launch Jupyter Notebook__:  
```
jupyter notebook
```

4. __Open__:
```
PredictingTips_LinearRegression.ipynb
```


## 📈 Example Insights
The model helps answer questions such as:
* Does a higher total bill lead to higher tips?
* Does party size influence tipping behavior?
* Are there noticeable differences based on time or smoker status?