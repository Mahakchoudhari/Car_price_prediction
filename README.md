# Car Price Prediction

##  Project Overview

This project predicts the selling price of used cars using Machine Learning techniques.
The model is trained on car dataset features such as year, fuel type, kilometers driven, and transmission type.

The objective of this project is to build a regression model that can accurately estimate car prices based on given input features.

---

 ## Dataset

This project uses a **Car Price Dataset**.

🔗 Dataset Link:
https://www.kaggle.com/datasets/jacksondivakarr/sample34

The dataset contains information about used cars and their selling prices.

### Features
* name                   
* year                   
* km_driven             
* fuel                    
* seller_type             
* transmission            
* owner                   
* seats                   
* max_power (in bph)     
* Mileage Unit           
* Mileage                
* Engine (CC)  

**Target Variable**

* Selling Price
---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* XgBoost
* Jupyter Notebook

---

## Machine Learning Model

* XgBoost Regression Model

### Steps Involved

1. Train-Test Split
2. Data Preprocessing
3. Handling Categorical Data using One-Hot Encoding
4. Model Training
5. Model Prediction

---
  
 ## How to Run the Project

1️⃣ Clone the repository
```
git clone https://github.com/Mahakchoudhari/Car_price_prediction.git
```
2️⃣ Install dependencies
```
pip install -r requirements.txt
```
3️⃣ Run the notebook or Python script

---

## Example Prediction

Example Input:

Year: 2015
Present Price: 6.5
Kms Driven: 35000
Fuel Type: Petrol
Transmission: Manual

Output:

** Predicted Car Price: ~₹X Lakhs

---

## Project Structure

```
Car_price_prediction
│
├── car data.csv
├── Car_price_prediction.ipynb
├── requirements.txt
└── README.md
```

## Author

**Mahak Choudhari**
Machine Learning Student
