# sales_prediction

This project focuses on predicting sales for retail items using the **XGBoostRegression algorithm**.
The goal is to develop a model that can accurately estimate the sales of various items based on different features.

## DataSet

* The dataset used for this project is obtained from the file `/content/Train.csv`.
* The dataset contains information about retail items and their corresponding sales.
* Features include item weight, item visibility, item maximum retail price (MRP), outlet establishment year, item fat content, item type, outlet identifier, outlet size, 
  outlet location type, and outlet type.
* The target variable is the item outlet sales.

## Prerequisites

 Make sure you have the following libraries installed:

* numpy
* pandas
* matplotlib
* seaborn
* sklearn
* xgboost

You can install these libraries using the following command: pip install numpy pandas matplotlib seaborn sklearn xgboost

## Data Preprocessing

* Loading the dataset using **Pandas** and examining its structure.
* Handling missing values in 'Item_Weight' and 'Outlet_Size' columns.
* Performing data visualization using **Matplotlib** and **Seaborn** to gain insights into the dataset.

## Data Encoding

* Applying one-hot encoding to categorical columns using the **OneHotEncoder** from _scikit-learn_.
* Separating numerical columns from the dataset.

## Model Training and Evaluation

* Training an **XGBoost regression** model on the training data.
* Evaluating the model's performance using **R-squared score** on both the training and testing sets.

### Future Improvements

* Trying other regression algorithms and comparing their results.
* Incorporating additional features or engineering new features to capture more information about the sales data.





