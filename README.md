# Titanic Dataset - Exploratory Data Analysis (EDA) & Modeling

This project conducts an **Exploratory Data Analysis (EDA)** on the famous Titanic dataset, aiming to understand various factors influencing survival rates. After the EDA, a **Random Forest classification model** is built to predict the survival of passengers.

## 🧑‍💻 Project Overview

The Titanic dataset provides information about passengers aboard the ill-fated RMS Titanic. The project includes:
- Data cleaning and handling missing values
- Visualizing data to gain insights into passenger survival
- Feature engineering and statistical testing
- Model building and evaluation

## 📊 Conclusions from Titanic EDA

1. **Overall Survival Count**
   - The majority of passengers **did not survive** the Titanic disaster.
   - This emphasizes the importance of passenger class, gender, and age in survival chances.

2. **Survival by Gender**
   - **Females** had a **much higher survival rate** than males, confirming the "women and children first" evacuation policy.

3. **Survival by Passenger Class**
   - Passengers in **1st class** had the highest survival rates, followed by **2nd class**, and then **3rd class**.
   - **Socio-economic status** played a major role in survival.

4. **Age vs Survival**
   - **Younger passengers** had higher survival rates on average.
   - The boxplot indicates that survivors had a lower average age than non-survivors.

5. **Family Size vs Survival**
   - Passengers with a **Family Size of 2–4** had higher survival rates.
   - Passengers traveling alone or with large families had **lower survival chances**.

6. **Embarkation Port**
   - Passengers who boarded from **Cherbourg (C)** had a higher survival rate, possibly due to wealthier passengers or better access to lifeboats.

7. **Fare vs Survival (via Correlation Heatmap)**
   - A positive correlation between **Fare** and **survival** suggests that wealthier passengers had higher chances of survival.

8. **Statistical Tests (Chi-Square and t-test)**
   - **Chi-Square tests** revealed significant associations between survival and features like **Sex**, **Pclass**, and **FamilySize**.
   - A **t-test** showed significant differences in **Age** between survivors and non-survivors.

9. **Model Evaluation (Confusion Matrix & ROC Curve)**
   - The **Random Forest model** demonstrated a reasonable **ROC AUC score**, suggesting good predictive ability.

## 🛠️ Technologies Used

- **Python** (Jupyter Notebook)
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn** for visualizations
- **Scikit-learn** for machine learning models and evaluation
