# 🚢 Titanic Survival Prediction using Machine Learning

This project predicts whether a passenger survived the Titanic disaster using Machine Learning techniques. It demonstrates the complete data science workflow including data preprocessing, visualization, feature engineering, model building, and evaluation.

---

## 📌 Project Overview

The goal of this project is to analyze the Titanic dataset and build a predictive model that can determine passenger survival based on features like age, gender, class, fare, etc.

---

## 📊 Dataset

* File: `Titanic-Dataset.csv`
* Source: Kaggle Titanic Dataset
* Features include:

  * Age
  * Sex
  * Pclass
  * Fare
  * SibSp
  * Parch
  * Embarked
* Target variable:

  * `Survived` (0 = No, 1 = Yes)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## ⚙️ Methodology

### 🔹 Data Preprocessing

* Handled missing values
* Removed unnecessary columns

### 🔹 Feature Engineering

* Created new feature: `FamilySize`

### 🔹 Data Visualization

* Survival count plot
* Gender vs survival plot
* Correlation heatmap

### 🔹 Model Building

* Logistic Regression model used

### 🔹 Evaluation

* Accuracy score
* Confusion Matrix

---

## 📈 Results

* ✅ Accuracy Achieved: **81.01%**
* 📌 Observations:

  * Female passengers had a higher survival rate
  * Passenger class significantly influenced survival

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/SANDEEP112005titanic-classification-ml.git
```

2. Navigate to the project folder:

```bash
cd titanic-classification-ml
```

3. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Run the notebook:

* Open `Titanic_survival.ipynb`
* Run all cells

---

## 📁 Project Structure

* `README.md` → Project documentation
* `Titanic-Dataset.csv` → Dataset
* `Titanic_survival.ipynb` → Model & code
* `Titanic_Project_Report_sandeep.pdf` → Project report

---

## 🔗 References

* Titanic Dataset (Kaggle)
* Scikit-learn Documentation

---

## 👤 Author

**Sandeep**
B-Tech CSE (Data Science)

---

## 📌 Conclusion

This project demonstrates how machine learning can be used to analyze real-world data and make predictions. It covers all key steps from preprocessing to model evaluation.

---
