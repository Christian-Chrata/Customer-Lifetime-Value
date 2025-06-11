# 🧠 Customer Lifetime Value Prediction

![presentation](./media/Customer%20Lifetime%20Value%20Prediction.gif)

This project aims to build a regression model to predict Customer Lifetime Value (CLV) using machine learning techniques. The best-performing model helps businesses identify high-value customers for better targeting and retention strategies.


---

## 📊 Dataset

- Located at: `input/dataset.csv`
- Includes features related to customer behavior, insurance policies, and claim history

---

## 🚀 Objective

To build a regression model that accurately predicts a customer's **lifetime value**, enabling:

- Customer segmentation
- Strategic retention efforts
- Personalized marketing

---

## 🛠️ Machine Learning Models Tested

- Linear Regression
- K-Nearest Neighbors
- Decision Tree
- Random Forest ✅ *(Best model)*
- XGBoost

---

## 📈 Evaluation Metrics

- MAE (Mean Absolute Error)  
- MAPE (Mean Absolute Percentage Error)  
- RMSE (Root Mean Squared Error)  
- R² Score

---

## 🧪 Best Model Summary: Random Forest (Untuned)

- **MAE**: ~1396.73  
- **MAPE**: ~10.94%  
- **R²**: ~0.66  
- Outperformed even the tuned versions

---

## 📌 Recommendations

- Use the untuned Random Forest as baseline
- Retrain the model periodically
- Enhance dataset with behavioral or transactional features
- Explore model ensembles if further accuracy is needed

---

## 📄 Author

- [Christian](https://github.com/Christian-Chrata) 