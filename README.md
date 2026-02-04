# Heart Disease Prediction using Machine Learning

This project aims to predict the presence of heart disease in patients using supervised machine learning techniques. Multiple classification models were trained and evaluated to identify the most suitable approach for this medical dataset.

---

## 📌 Problem Statement
Heart disease is one of the leading causes of death worldwide. Early detection can significantly improve treatment outcomes. This project uses patient medical data to predict whether a person is likely to have heart disease.

---

## 📂 Dataset
- **Source:** Kaggle Heart Disease Dataset  
- **Records:** 1026 
- **Features:** 13 medical attributes (age, cholesterol, blood pressure, etc.)  
- **Target:**  
  - `0` → No Heart Disease  
  - `1` → Heart Disease  

---

## 🔍 Exploratory Data Analysis (EDA)
The following analyses were performed:
- Distribution analysis of target classes
- Feature-wise visualizations
- Correlation heatmap to understand relationships between features
- Identification of features strongly correlated with heart disease

EDA helped in understanding data patterns and selecting appropriate models.

---

## 🧠 Machine Learning Models Used
The following classification models were implemented and evaluated:

1. **Logistic Regression** (Baseline Model)
2. **K-Nearest Neighbors (KNN)**
3. **Support Vector Machine (SVM)**

Feature scaling was applied where required (Logistic Regression, KNN, SVM).

---

## 📊 Model Evaluation Metrics
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Special emphasis was given to **Recall for heart disease cases**, as missing a positive patient is critical in medical applications.

---

## 📈 Model Performance Summary

| Model | Accuracy |
|-----|---------|
| Logistic Regression | 81% |
| KNN | 73% |
| SVM | 70% |

---

## 🏆 Final Model Selection
**Logistic Regression** was selected as the final model because:
- It achieved the highest accuracy
- It showed stable and reliable performance
- It provides better interpretability for medical decision-making
- It has lower risk of overfitting compared to complex models

---

### Dashboard Preview
![Dashboard Preview](dashboard_heart.pdf)

--

## 📉 Error Analysis
- **False Positives:** May cause unnecessary medical concern
- **False Negatives:** More critical, as they represent missed heart disease cases  

The selected model minimized false negatives, making it suitable for healthcare prediction tasks.

---

## ⚠️ Limitations
- Dataset size is limited to 1025 records
- No external validation dataset was used
- The model was tested only on structured numerical data

---

## 🛠️ Tech Stack
- Python  
- Google Colab  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## ▶️ How to Run the Project
1. Clone the repository
2. Open the notebook in **Google Colab**
3. Upload the dataset (`heart.csv`)
4. Run all cells sequentially

---

## 📌 Conclusion
Multiple machine learning models were evaluated for heart disease prediction. Logistic Regression emerged as the most reliable model with an accuracy of 81% and strong recall for disease detection. This project demonstrates the effectiveness of classical machine learning techniques in healthcare prediction tasks.

---

## 👤 Author
**Manish N**  
BTech CSE (Data Science)

