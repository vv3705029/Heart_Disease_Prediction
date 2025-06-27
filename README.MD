-------------------------------------------------------------     Heart Disease Prediction Using Machine Learning  --------------------------------------------

This project predicts the likelihood of heart disease based on clinical parameters. Multiple supervised machine learning models were trained and compared using a medical dataset (`heart.csv`).

---

-------------------------------------------------------------     Features (from `heart.csv`)  -----------------------------------------------------------------

- `age`: Age of the patient
- `sex`: Gender (1 = male, 0 = female)
- `cp`: Chest pain type
- `trestbps`: Resting blood pressure
- `chol`: Serum cholesterol (mg/dl)
- `fbs`: Fasting blood sugar > 120 mg/dl
- `restecg`: Resting electrocardiographic results
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina (1 = yes, 0 = no)
- `oldpeak`: ST depression induced by exercise
- `slope`: Slope of the peak exercise ST segment
- `ca`: Number of major vessels colored by fluoroscopy
- `thal`: Thalassemia status
- `target`: Heart disease presence (1 = disease, 0 = no disease)

---

---------------------------------------------------------      Machine Learning Models Used   ----------------------------------------------------------------

- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **Support Vector Machine (SVM)**
- **K-Nearest Neighbors (KNN)**
- **Naive Bayes Classifier**

---

-------------------------------------------------------------         Evaluation Metrics     ------------------------------------------------------------------

Each model was evaluated using:

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Confusion Matrix**

-------------------------------------------------------          Sample Output (Accuracy %)    ----------------------------------------------------------------
        Model	                          Accuracy
1. Logistic Regression	             86.38%
2. Decision Tree	                   100%
3. Random Forest	                   100%
4. KNN	                             87.93%
5. Naive Bayes	                     85.21%
6. SVM	                             86%

-------------------------------------------------------                   Dataset              -----------------------------------------------------------------

- `heart.csv`  
  Contains 14 attributes and a binary target variable indicating presence or absence of heart disease.

---

--------------------------------------------------------                How to Run            -----------------------------------------------------------------

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/heart-disease-prediction.git
   cd heart-disease-prediction
