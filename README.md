# 🚢 Titanic – Machine Learning From Disaster

> Predicting passenger survival on the Titanic using machine learning

[![Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange)](https://github.com/p-gagan/Titanic---Machine-Learning-From-Disaster/blob/main/Titanic%20-%20Machine%20Learning%20From%20Disaster.ipynb)
![Kaggle Score](https://img.shields.io/badge/Kaggle%20Score-0.77990-brightgreen)

---

## 📖 Project Overview

This is a Kaggle competition project where the goal is to predict whether a passenger on the Titanic survived based on features such as age, sex, class, and more.  
The project covers:
- Data cleaning & preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature engineering (titles, family size, etc.)  
- Training multiple machine learning models  
- Submitting predictions to Kaggle  

---

## 🧰 Dataset

- **train.csv** – training data with survival labels  
- **test.csv** – test data without labels (for submission)  
- **gender_submission.csv** – sample submission  

Dataset source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)  

---

## 🔍 Exploratory Data Analysis & Feature Engineering

Some highlights from EDA:
- Women had a significantly higher survival rate than men.  
- 1st class passengers had a better chance of survival compared to 2nd and 3rd.  
- Larger families had mixed outcomes; small family groups survived better.  
- Missing values in **Age** were imputed, and new features such as `FamilySize` and passenger `Title` were created.  

*(Plots and visualizations can be added here as images.)*

---

## 🤖 Models & Results

The following models were trained and compared:

| Model | Validation Accuracy | Notes |
|---|---|---|
| Logistic Regression | ~77% | Simple, interpretable baseline |
| Random Forest | ~78% | Strong performance with feature importance |
| XGBoost | ~78% | Tuned for better generalization |
| Support Vector Machine | ~76% | Decent but slower |

✅ **Best Kaggle submission achieved a public score of 0.77990**  

---

## 📈 Kaggle Leaderboard

Your first Kaggle submission scored:

- **Score:** `0.77990`  
- **Ranking:** #2896 (at time of submission)  

![Kaggle Leaderboard Screenshot](Screenshot.png)  

---

## 🔧 Installation & Usage

To run this project locally:

```bash
# Clone the repo
git clone https://github.com/p-gagan/Titanic---Machine-Learning-From-Disaster.git
cd Titanic---Machine-Learning-From-Disaster

# Install requirements
pip install -r requirements.txt

---
### Then open the notebook:
jupyter notebook "Titanic - Machine Learning From Disaster.ipynb"

---

## 📂 Project Structure
.
├── Titanic - Machine Learning From Disaster.ipynb   # Main notebook
├── train.csv                                        # Training dataset
├── test.csv                                         # Test dataset
├── gender_submission.csv                            # Sample submission
├── submission.csv                                   # Final Kaggle submission
├── requirements.txt                                 # Dependencies
└── README.md                                        # Project documentation

## 🧮 Tools & Libraries
- Python (Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, XGBoost)
- Jupyter Notebook
- Kaggle platform

## 🙏 Acknowledgements
- Kaggle Titanic Competition
