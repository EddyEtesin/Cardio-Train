#  Cardiovascular Disease Prediction

This project uses machine learning to predict the likelihood of cardiovascular disease based on patient data. The goal is to build and evaluate a classification model that helps identify high-risk patients.

---

##  Dataset

The dataset `cardio_train.csv` contains information on various medical indicators such as:

* Age
* Gender
* Height & Weight
* Blood pressure (systolic & diastolic)
* Cholesterol & glucose levels
* Lifestyle indicators (smoking, alcohol intake, physical activity)

The target variable is `cardio`:

* `0`: No cardiovascular disease
* `1`: Cardiovascular disease present

---

##  Features

The following steps are included in the notebook:

* **Data Cleaning:** Handling missing values and preparing features
* **Feature Scaling:** Standardizing numerical variables
* **Encoding:** Converting categorical variables using one-hot encoding
* **Model Training:** Logistic Regression using Scikit-learn
* **Evaluation:** Accuracy score, confusion matrix, and classification report

---

## Technologies

* Python 3
* Pandas, NumPy for data processing
* Scikit-learn for machine learning
* Matplotlib, Seaborn for data visualization

---

##  How to Run

1. Clone this repository.
2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open the notebook `Cardio Train.ipynb` in Jupyter Notebook or VSCode.
4. Run the cells sequentially.

---

## Results

The logistic regression model achieved good performance in classifying patients based on their medical data. Evaluation metrics (accuracy, precision, recall) are included in the notebook.

---


