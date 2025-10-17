# 🚢 Titanic - Machine Learning from Disaster

A beginner-friendly **Machine Learning project** based on the **Kaggle Titanic Competition**.  
The goal is to **predict which passengers survived** the Titanic disaster using **Logistic Regression** and proper data preprocessing.

---

## 📊 Dataset
📦 Dataset Source (Kaggle):  
👉 [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)

The dataset contains:
- Passenger demographics: Age, Sex
- Ticket class (Pclass)
- Family size: SibSp, Parch
- Fare and Embarked port
- Survival status (`Survived`: 0 = Did not survive, 1 = Survived)

---

## 🧰 Tools & Technologies Used

| Category | Tools |
|-----------|--------|
| **Programming Language** | Python |
| **Environment** | Jupyter Notebook |
| **Libraries** | pandas, numpy, scikit-learn |
| **Model Used** | Logistic Regression |
| **Version Control** | Git & GitHub |
| **Data Source** | Kaggle Titanic Dataset |

---

## 🧠 Project Workflow

1. **Data Loading**: Load training and test datasets into Pandas DataFrames.
2. **Data Cleaning & Preprocessing**: Drop unused columns, fill missing values, handle categorical variables.
3. **Feature Encoding**: Encode categorical columns (Sex, Embarked) into numerical form.
4. **Model Training**: Split dataset into training and validation sets and train a Logistic Regression model.
5. **Evaluation**: Evaluate model accuracy on validation data (~76% accuracy).
6. **Prediction & Submission**: Predict survival on the test dataset and save results as `submission.csv` for Kaggle submission.

---

## 📁 Project Structure

- main_jupyter.ipynb # 📘 Main notebook with data cleaning, EDA, and model training
- train.csv # 🚂 Training dataset from Kaggle
- test.csv # 🧪 Test dataset from Kaggle
- submission.csv # 📄 Final predictions ready for Kaggle submission
- README.md # 📝 Project documentation (this file)
