## 📘 Customer Lifetime Value Prediction Model

This project predicts customer Lifetime Value (LTV) using transaction data from a digital wallet application. The output helps businesses identify high-value customers and optimize marketing strategies.

---

### 📁 Files Included

| File Name                            | Description                                                                                                         |
| ------------------------------------ | ------------------------------------------------------------------------------------------------------------------- |
| `Customer_LTV_Prediction_(1).ipynb`  | Jupyter Notebook containing data loading, preprocessing, feature engineering, model training, and prediction steps. |
| `digital_wallet_ltv_dataset.csv`     | Source dataset containing transaction-level data of digital wallet users.                                           |
| `ltv_predictions.csv`                | Output file containing predicted LTV values and customer segment labels.                                            |
| `Customer_LTV_Prediction_Report.pdf` | Final project report summarizing the objective, process, and outcomes.                                              |

---

### 🧠 Project Steps

1. **Load and clean data**
2. **Engineer features**: Recency, Frequency, AOV
3. **Build LTV regression model** (XGBoost)
4. **Predict LTV for each customer**
5. **Segment customers** into Low, Medium, and High LTV
6. **Export predictions** and save results

---

### 🔧 Tools & Libraries Used

* Python, Jupyter Notebook
* `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`
* `Scikit-learn`, `XGBoost`

---

### 📌 Use Case

This model helps identify which customers are most likely to bring long-term value, enabling:

* Targeted marketing
* Personalized retention strategies
* Efficient resource allocation

