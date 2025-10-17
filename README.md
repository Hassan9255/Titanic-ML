# 🚢 Titanic - Machine Learning from Disaster

A beginner-friendly **Machine Learning project** based on the famous **Titanic Kaggle Competition**.  
The goal is to **predict which passengers survived** the Titanic disaster using demographic and socio-economic data such as age, gender, ticket class, and family relationships.

---

## 📊 Dataset
📦 Dataset Source (Kaggle):  
👉 [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)

The dataset includes details of over 800 passengers such as:
- Name, Age, Gender, and Ticket Class (Pclass)  
- Fare, Embarkation Port, and Family Size  
- Survival status (`0 = Did not survive`, `1 = Survived`)

---

## 🧰 Tools & Technologies Used
| Category | Tools |
|-----------|--------|
| **Programming Language** | Python |
| **Environment** | Jupyter Notebook |
| **Libraries** | pandas, numpy, scikit-learn, matplotlib, seaborn |
| **Machine Learning Models** | Logistic Regression, Decision Tree, Random Forest |

---

## 🧠 Project Workflow
1. **Data Cleaning**  
   - Handle missing values (Age, Embarked)  
   - Drop irrelevant columns (e.g., Ticket, Cabin)  
   - Encode categorical variables  

2. **Exploratory Data Analysis (EDA)**  
   - Visualize survival rates by gender, age, and passenger class  
   - Analyze correlations between features  

3. **Model Training**  
   - Train multiple ML models: Logistic Regression, Decision Tree, and Random Forest  
   - Compare model accuracy using cross-validation  

4. **Model Evaluation & Submission**  
   - Achieved ~**76% accuracy** on Kaggle test data  
   - Generated a valid `submission.csv` file for Kaggle upload  

---

## 📁 Project Structure

- main_jupyter.ipynb # 📘 Main notebook with data cleaning, EDA, and model training
- train.csv # 🚂 Training dataset from Kaggle
- test.csv # 🧪 Test dataset from Kaggle
- submission.csv # 📄 Final predictions ready for Kaggle submission
- README.md # 📝 Project documentation (this file)
