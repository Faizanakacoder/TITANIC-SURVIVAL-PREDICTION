# 🚢 Titanic Survival Prediction | CodSoft Task 1

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Library](https://img.shields.io/badge/Library-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Internship](https://img.shields.io/badge/CodSoft-Data%20Science-red)

> **"The Titanic is one of the most infamous shipwrecks in history. But was survival just luck? Or was there a pattern?"**

---

## 📄 Project Overview
This project goes beyond simple binary classification. As **Task 1** for the **CodSoft Data Science Internship**, I analyzed the Titanic dataset to understand the *human* factors behind survival. By leveraging **Exploratory Data Analysis (EDA)** and **Feature Engineering**, this model predicts survival with high accuracy based on socio-economic status, age, and gender.

### 🎯 Objective
To build a Machine Learning model that answers the question: **"What sort of people were more likely to survive?"**

---

## 📊 Visual Insights (EDA)
*Data isn't just numbers; it's a story.* Here are the key insights that drove my model's logic:

### 1. The "Women and Children First" Protocol
The age distribution clearly shows a massive spike in survival for infants (0-5 years), while men faced the lowest survival probability.
![Age Distribution](<img width="863" height="549" alt="age distribution" src="https://github.com/user-attachments/assets/65f688d9-41be-4d42-9e55-051f2d14950d" />
)
*(Replace 'images/age_distribution.png' with your actual file path)*

### 2. The Socio-Economic Divide
Survival wasn't random—it was purchased. 1st Class passengers (especially women) had a near-guaranteed survival rate, while 3rd Class men were left behind.
![Class and Gender](<img width="691" height="549" alt="class and gender" src="https://github.com/user-attachments/assets/00549808-0f11-4870-98cc-8f29f1ccaed7" />
)
*(Replace 'images/by_class_and_gender.png' with your actual file path)*

### 3. Feature Correlations
My analysis revealed that **Fare** (Wealth) was actually a stronger predictor of survival than **Age** (excluding infants).
![Heatmap](<img width="645" height="530" alt="coffeletion" src="https://github.com/user-attachments/assets/c4095351-c9dc-4806-87ac-d459b10155e2" />
)
*(Replace 'images/feature_survivour.png' with your actual file path)*

---

## 🛠️ Technologies & Tools

| Category | Tools Used |
| :--- | :--- |
| **Language** | Python 🐍 |
| **Data Manipulation** | Pandas, NumPy |
| **Visualization** | Seaborn, Matplotlib |
| **Machine Learning** | Scikit-Learn (Logistic Regression, Decision Trees) |
| **Environment** | Jupyter Notebook / Google Colab |

---

## 🚀 Key Workflow Steps

1.  **Data Loading & Cleaning:**
    * Imported data via Seaborn.
    * Handled missing values in `Age` (imputed based on Pclass) and `Embarked`.
2.  **Feature Engineering:**
    * Extracted **Titles** (Mr, Mrs, Miss, Master) from passenger names to categorize social status more accurately.
    * Converted categorical variables (`Sex`, `Embarked`) into numeric dummies.
3.  **Exploratory Data Analysis (EDA):**
    * Uncovered the correlation between **Fare Price** and **Survival Rate**.
    * Visualized the impact of **Family Size** (SibSp + Parch).
4.  **Model Training:**
    * Split data into 80% Training and 20% Testing sets.
    * Trained a **Logistic Regression** model for binary classification.
5.  **Evaluation:**
    * Evaluated performance using Accuracy Score and Confusion Matrix.

---

## 📂 Repository Structure

```markdown
```text
├── images/               # Screenshots of plots and graphs
├── Titanic_Survival.ipynb # Main Jupyter Notebook
├── README.md             # Project Documentation
└── requirements.txt      # List of dependencies

```

---

## 🔗 Connect with Me

If you found this analysis interesting or have any questions, feel free to connect!

* **Author:** Faizan Firoz Shah
* **Role:** Data Science Intern @ CodSoft
* **Batch:** January 2026
* **Internship ID:** CS11NY482650
* **GitHub:** [https://github.com/Faizanakacoder](https://www.google.com/search?q=https://github.com/Faizanakacoder)
* **LinkedIn:** [www.linkedin.com/in/0faizanshah0]

---

<div align="center">
<p>⭐ <b>If you found this project helpful, please give it a Star!</b> ⭐</p>
<p><i>Happy Coding! 🚀</i></p>
</div>

```

```
