# credit-card-fraud-detection
A machine learning project to detect fraudulent credit card transactions using supervised classification techniques. The dataset is highly imbalanced, and this project addresses that challenge with appropriate techniques.


---

## 🧠 Problem Type

**Supervised Learning** → **Binary Classification**  
- **0** → Genuine Transaction  
- **1** → Fraudulent Transaction

---

## 📊 Dataset

- **Name**: [Credit Card Fraud Detection Dataset (Kaggle)](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Features**: 30 (anonymized due to confidentiality)
- **Rows**: 284,807 transactions
- **Fraudulent transactions**: 492 (approx. 0.17%)

---

## 🔍 Project Structure

| Stage                     | Description |
|--------------------------|-------------|
| `EDA`                    | Distribution analysis, class imbalance, outlier detection |
| `Preprocessing`          | Scaling, undersampling/oversampling (SMOTE), train/test split |
| `Model Training`         | Logistic Regression, Random Forest, XGBoost |
| `Evaluation`             | Confusion matrix, Precision, Recall, F1-score, ROC-AUC |
| `Deployment Ready`       | Trained model saved with `joblib` for future use |

---

## ⚙️ Dependencies

```bash
pip install -r requirements.txt
