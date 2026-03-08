# 📊 Telecom Customer Churn Prediction

## 📌 What is Customer Churn?
Customer churn happens when customers stop using a company’s service.  
In telecom, churn rates are usually **15–25% annually**.  
Predicting churn helps companies focus retention efforts on **high‑risk customers**, which is cheaper than acquiring new ones.

---

## 🎯 Objectives
- Find % of churn vs active customers  
- Analyze features responsible for churn  
- Identify the best ML model for churn classification  

---

## 📂 Dataset
**Telco Customer Churn** dataset includes:  
- **Churn column** → whether customer left in last month  
- **Services** → phone, internet, security, backup, streaming, etc.  
- **Account info** → tenure, contract, payment method, charges  
- **Demographics** → gender, senior citizen, dependents, partners  

---

## 🔎 Key EDA Insights
- **Churn Rate:** ~26.6% customers switched  
- **Contract:** 75% churn with Month‑to‑Month vs 13% (1‑year) vs 3% (2‑year)  
- **Payment Method:** Electronic Check users churn more  
- **Internet Service:** Fiber optic users churn more than DSL  
- **Dependents:** Customers without dependents churn more  
- **Online Security & Tech Support:** Lack of these increases churn  
- **Paperless Billing:** Higher churn rate  
- **Charges & Tenure:** High monthly charges + new customers churn more  

---

## 🤖 Machine Learning Models
Evaluated with **10‑fold cross validation**:  
- Logistic Regression  
- KNN  
- Naive Bayes  
- Decision Tree  
- Random Forest  
- AdaBoost  
- Gradient Boosting  
- Voting Classifier  

---

## 📊 Results
| Model                     | Accuracy (Mean) |
|----------------------------|-----------------|
| Logistic Regression        | ~84% |
| KNN                        | ~79% |
| Naive Bayes                | ~82% |
| Decision Tree              | ~65% |
| Random Forest              | ~82% |
| AdaBoost                   | ~84% |
| Gradient Boosting          | ~84% |
| **Voting Classifier (Final)** | **~85%** |

- **Final Model:** Voting Classifier (Gradient Boosting + Logistic Regression + AdaBoost)  
- **Confusion Matrix:**  
  - Correctly predicted most non‑churn customers  
  - Balanced performance on churn detection  

---

## 📜 Conclusion
- **High churn drivers:** Month‑to‑Month contracts, electronic check payments, fiber optic internet, lack of support/security.  
- **Best model:** Voting Classifier with ~85% accuracy.  
- **Business impact:** Early churn prediction enables targeted retention strategies, reducing losses and improving customer loyalty.  

---

## 👩‍💻 Author
**Sabna Asmi S**  
Final-year IT Student | Data Science Enthusiast  
