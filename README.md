# 🚗 Car Price Prediction

This project applies Data Science and Machine Learning techniques to predict the selling price of cars based on key features such as year of manufacture, kilometers driven, fuel type, transmission, and ownership history. It covers the complete workflow — from data exploration and preprocessing to model training and evaluation — using Python, pandas, and scikit-learn.

## 📊 Project Overview

The notebook includes:

* Data preprocessing and feature encoding
* Exploratory data analysis (EDA)
* Model building using Linear Regression 
* Performance evaluation using R² Score and Mean Absolute Error

## 🧠 Models Used

* **Linear Regression**
* **Lasso Regression**
* **Ridge Regression**
  

## 🔍 Dataset

The dataset includes features such as:

* Name
* Year
* Selling Price
* Present Price
* Kms Driven
* Fuel Type
* Seller Type
* Transmission
* Owner
   
## 📈 Evaluation Metrics

The models are evaluated using:

* R² Score
* Mean Absolute Error (MAE)

## 🏃‍♂️ How to Run the Project

### Running the Jupyter Notebook

This is for training the model, performing EDA, and saving the model.

#### Prerequisites:

* Python 3.9+
* Jupyter Notebook

#### Steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/nayana1507/car_price_prediction.git
   cd car_price_prediction
   ```

2. **Install the dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

4. **Open `car_price_prediction.ipynb`** in your browser.

5. **Run the notebook cells one by one** to:

   * Load and explore the dataset
   * Preprocess and encode the features
   * Train machine learning models
   * Evaluate performance
   * Save the best model 

The model is trained and evaluated within the notebook. No model persistence is used

## 📦 Requirements

* Python 3.x
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn

## 📁 Files

* `car_price_prediction.ipynb` – Main notebook with code and visualizations.
* `car data.csv` – The dataset file. 
* `requirements.txt` – Python dependencies.

## 🧠 Future Improvements

* Add more regression models 
* Hyperparameter tuning for better accuracy
* Deploy model using Flask or Streamlit


