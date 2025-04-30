Titanic Dataset - Exploratory Data Analysis (EDA)

This project performs a comprehensive EDA (Exploratory Data Analysis) on the Titanic dataset to uncover insights about passenger survival during the infamous disaster. The analysis involves data cleaning, visualization, feature engineering, and statistical testing.

📁 Dataset

Source: sns.load_dataset('titanic')

The dataset contains demographic and travel information for passengers aboard the Titanic.

🧹 Steps Performed

Data Cleaning

Dropped columns with excessive missing values (e.g., deck).

Imputed missing values for age, embarked, and embark_town.

Visualization and EDA

Plotted various relationships using Seaborn and Matplotlib.

Feature Engineering

Created a new feature FamilySize = sibsp + parch + 1.

Statistical Testing

Applied Chi-Square tests for categorical variables.

Used t-tests for numerical feature comparison (e.g., age).

Correlation and Encoding

One-hot encoded categorical features.

Visualized the correlation heatmap.

Model Evaluation

Trained a Random Forest Classifier and evaluated it using ROC and Confusion Matrix.

📊 Key Conclusions

Overall Survival

Most passengers did not survive.

Gender vs Survival

Females had a much higher survival rate than males.

Class vs Survival

First class passengers were most likely to survive.

Age vs Survival

Younger passengers had a higher chance of survival.

Family Size

Medium-sized families (2–4 people) had better survival rates.

Embarkation Port

Passengers from Cherbourg showed higher survival rates.

Fare vs Survival

Higher fare correlated positively with survival.

Statistical Significance

Features like sex, pclass, and FamilySize showed significant associations with survival.

Model Metrics

ROC curve and confusion matrix validated the predictive quality of selected features.

📌 Tools & Libraries

Python

Pandas

Seaborn

Matplotlib

Scikit-learn

SciPy
