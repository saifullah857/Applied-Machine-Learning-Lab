
# 🚀 Machine Learning Algorithms & Implementations

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

## 📌 Overview
This repository contains a collection of fundamental Machine Learning algorithms applied to real-world datasets. It serves as a practical exploration of both **Classification** and **Regression** problems. 

The project highlights technical proficiency in data preprocessing, model building, hyperparameter tuning, and performance evaluation using industry-standard libraries, alongside a custom mathematical implementation of Linear Regression built entirely from scratch.

---

## 📂 Project Structure

### 📊 Datasets
The models in this repository are trained and evaluated on the following datasets:
* **`heart.csv`**: Clinical data used for binary classification tasks to predict the likelihood of heart disease.
* **`house.csv`**: Real estate data featuring property specifics (Location, Area, Bedrooms) used to predict housing prices (Regression).
* **`insurance.csv`**: Demographic and health metrics (Age, BMI, Smoker status) used to forecast medical insurance charges (Regression).

### 📓 Jupyter Notebooks
* **`Linear-Reggression.ipynb`**: Implementation of simple/multiple linear regression for continuous value prediction (e.g., housing prices), complete with Seaborn visualizations for actual vs. predicted values.
* **`logistic_regression.ipynb`**: Binary classification modeling featuring standard scaling and rigorous evaluation metrics (Accuracy, Precision, Recall).
* **`lasso_regression.ipynb`**: Advanced regression techniques utilizing `RidgeCV` and `Lasso` for regularization, hyperparameter tuning (Alpha), and mitigating overfitting.
* **`knn.ipynb`**: K-Nearest Neighbors classifier implementing `StandardScaler`, `Pipeline`, and `GridSearchCV` to find the optimal number of neighbors ($k$).
* **`naive_bays.ipynb`**: Probabilistic classification utilizing the Gaussian Naive Bayes theorem.
* **`scratch_implementaion.ipynb`**: A core AI/ML engineering exercise—implementing Gradient Descent and Linear Regression purely using `NumPy` mathematics without relying on external ML libraries.

---

## 🛠️ Key Technologies & Concepts
* **Supervised Learning:** Classification & Regression.
* **Evaluation Metrics:** Mean Squared Error (MSE), $R^2$ Score, Accuracy, Precision, Recall.
* **Data Optimization:** One-Hot Encoding (`pd.get_dummies`), Feature Scaling (`StandardScaler`).
* **Model Selection:** Cross-Validation (`cv=5`), Hyperparameter Tuning (`GridSearchCV`).

---

## 🚀 Getting Started

### Prerequisites
To run these notebooks locally in VS Code or Jupyter, ensure you have Python installed along with the required scientific libraries:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
```

### Installation & Execution
1. Clone the repository:
   ```bash
   git clone [https://github.com/saifullah857/Applied-Machine-Learning-Lab.git]
   ```
2. Navigate to the project directory:
   ```bash
   cd Applied-Machine-Learning-Lab
   ```
3. Launch Jupyter Notebook or open the files directly in VS Code:
   ```bash
   jupyter notebook
   ```

---

## 👨‍💻 Author
**Saif Ullah** 
