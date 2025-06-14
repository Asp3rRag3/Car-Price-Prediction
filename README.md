# 🚗 Car Price Prediction using Machine Learning

Hey there! 👋  
This is a machine learning project where I built a model to predict car prices based on features like the brand, year, fuel type, transmission, and more.

The idea was simple — feed the model a bunch of car data, train it to learn patterns, and get it to predict car prices as accurately as possible. I wanted to see how good ML can be at understanding market value, and honestly, it performed way better than I expected!

## 🔧 What I did

- Started with a **clean dataset** — no missing values or duplicates to deal with 🙌
- Detected and handled a few **outliers in the Price column** (just 6 of them!)
- Did feature engineering to get the data into the right shape
- Trained a **Gradient Boosting Regressor** with hyperparameter tuning
- Evaluated the model using RMSE and R² Score — and the results were 🔥

## 📊 Tech Stack

- Python  
- Pandas & NumPy  
- Scikit-learn  
- Matplotlib & Seaborn  
- Google Colab (because why not?)

## 📈 Model Performance

- **RMSE:** ~200.75  
- **R² Score:** 0.996  
- Used 5-fold cross-validation to make sure the model wasn’t just memorizing stuff

## 📁 Files

- `car_price_model.ipynb` — My full Colab notebook with step-by-step code and comments
- (Planning to add more like a `.py` version or web app soon)

## 🚀 What’s next?

- Might deploy this as a Streamlit or Flask web app just for fun
- Try out other boosting models like XGBoost or LightGBM for comparison
- Maybe even build an API for real-time predictions

---

Thanks for stopping by! Feel free to check it out, fork it, or drop a star ⭐ if you liked it.  
– *Meet Lohia*
