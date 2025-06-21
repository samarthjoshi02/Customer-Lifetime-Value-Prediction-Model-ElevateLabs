# 🧠 Customer Lifetime Value (LTV) Prediction

This project aims to predict the **Customer Lifetime Value (LTV)** using historical transaction data. By leveraging machine learning, businesses can better understand customer behavior, prioritize retention efforts, and tailor marketing strategies.

---

## 📌 Project Objective

Predict the total future monetary value a customer will bring to a business using features like:

- **Recency** (days since last purchase)
- **Frequency** (number of purchases)
- **Average Order Value (AOV)**

---

## 🛠️ Tools & Libraries

- Python (Pandas, NumPy)
- Scikit-learn (Random Forest Regressor)
- Matplotlib & Seaborn (Visualizations)
- Jupyter Notebook
- Excel (for result export)

---

## ⚙️ Project Structure

ltv-prediction-project/
├── LTV_Prediction_RandomForest.ipynb # Main notebook
├── final_ltv_predictions.xlsx # Final LTV output (not pushed to GitHub)
├── synthetic_customer_transactions.csv # Sample data (optional)
├── .gitignore
└── README.md

---

## 🧪 Steps Involved

1. **Data Preprocessing**: Cleaned and formatted transaction data.
2. **Feature Engineering**: Created RFM features.
3. **Model Building**: Trained a Random Forest Regressor to predict LTV.
4. **Evaluation**: Validated with MAE and RMSE metrics.
5. **Segmentation**: Classified customers into High, Mid, and Low LTV groups.
6. **Export**: Saved predictions and segments to Excel.

---

## 📈 Sample Output

Customer segmentation into:
- 🔴 **High Value**
- 🟡 **Mid Value**
- 🟢 **Low Value**

Final results exported as `final_ltv_predictions.xlsx`.

---

## 🚀 How to Run

1. Clone the repo  
2. Install dependencies  
3. Open `LTV_Prediction_RandomForest.ipynb`  
4. Run all cells

---

## 📂 License

This project is licensed under the **Mozilla Public License 2.0 (MPL-2.0)**.  
You can read the full license [here](https://www.mozilla.org/en-US/MPL/2.0/).
