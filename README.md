# 🚢 Titanic Survival Prediction

This project uses a Machine Learning model to predict whether a passenger on the Titanic would survive based on features like age, sex, class, etc. The dataset is taken from the famous Titanic challenge on [Kaggle].
## 🧠 Objective
To build a predictive model that answers the question:
> *"Would a given passenger have survived the Titanic disaster?"*

## 📦 Dataset
The dataset typically contains the following features:
- `Pclass`: Ticket class (1st, 2nd, 3rd)
- `Sex`: Gender
- `Age`: Age of the passenger
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Fare`: Ticket fare
- `Embarked`: Port of Embarkation
- `Survived`: Target variable (0 = No, 1 = Yes)

## 🛠️ Technologies Used
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Seaborn & Matplotlib (for visualization)
- Scikit-learn (for ML model)

## ⚙️ How the Model Works
1. **Data Cleaning**: Handles missing values and categorical encoding.
2. **Exploratory Data Analysis (EDA)**: Uses seaborn and matplotlib for visualizing survival rates across features.
3. **Model Training**: Trains a machine learning model (e.g., Logistic Regression, SVM, etc.).
4. **Prediction**: Predicts survival on test data.
5. **Evaluation**: Uses accuracy score to compare predictions (`y_pred`) with actual outcomes (`Y_test`).
