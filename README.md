# diabetes-prediction-ML
Diabetes Prediction using Machine Learning Algorithms A comparative machine learning study on the Pima Indians Diabetes dataset. Five classification algorithms and an Artificial Neural Network (ANN) are implemented, evaluated, and compared to predict the onset of diabetes based on diagnostic measurements.
# Diabetes Prediction using Machine Learning Algorithms

A comparative machine learning study on the **Pima Indians Diabetes dataset**. Five classification algorithms and an Artificial Neural Network (ANN) are implemented, evaluated, and compared to predict the onset of diabetes based on diagnostic measurements.

---

## Dataset

- **Source:** Pima Indians Diabetes Dataset
- **Records:** 768 patients
- **Features:** Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age
- **Target:** Outcome (1 = Diabetic, 0 = Non-Diabetic)

---

## Project Workflow

1. **Data Loading & Exploration** — shape, data types, class distribution
2. **Data Preprocessing** — replaced invalid zeros with column means, scaled features using `StandardScaler`
3. **Exploratory Data Analysis** — correlation heatmap, class distribution plot
4. **Model Training & Evaluation** — 5 classifiers + ANN, 80/20 train-test split
5. **Model Comparison** — ROC curves, AUC scores, confusion matrix

---

## Models & Results

| Model               | Accuracy | AUC  |
|---------------------|----------|------|
| Logistic Regression | 75%      | 0.82 |
| KNN                 | 74%      | 0.78 |
| Decision Tree       | 72%      | 0.70 |
| Random Forest       | 75%      | 0.83 |
| SVM                 | 75%      | 0.81 |
| ANN (TensorFlow)    | 75%      | —    |

> **Best performer:** Random Forest with AUC = 0.83

---

## Tech Stack

- **Language:** Python
- **Libraries:** scikit-learn, TensorFlow / Keras, pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Google Colab

---

## How to Run

1. Open the `.ipynb` file in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook
2. Upload `pima_diabetes_data.csv` when prompted
3. Run all cells in order

---

## Author

**Hafiz Muhammad Anas Majid**  
BS Computer Science — University of Management and Technology (UMT), Lahore  
[LinkedIn](https://www.linkedin.com/in/) · [Portfolio](https://your-portfolio-link.com)
