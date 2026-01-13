🚢 Titanic Dataset - Exploratory Data Analysis (EDA)


🧭 Overview

The Titanic dataset contains details of passengers aboard the RMS Titanic, which tragically sank in 1912.
The goal of this analysis is to explore the data, identify patterns, and understand which factors influenced passenger survival.

🔹 1. Dataset Overview

Total rows: 891

Total columns: 12

Target variable: Survived (0 = Did not survive, 1 = Survived)

Features include:

Demographics: Age, Sex, Pclass

Travel info: Embarked, Ticket, Fare

Family info: SibSp, Parch

🔹 2. Data Cleaning

Missing values found in: Age, Cabin, and Embarked
Age → Filled with median
Embarked → Filled with most frequent value (mode)
Cabin → Using feature engineering created a new column as has cabin
Removed duplicate rows (if any)
Checked and corrected data types

🔹 3. Univariate Analysis

Survival Count: ~38% passengers survived
Gender: More males than females on board
Pclass: Most passengers were from 3rd class
Age: Majority between 20–40 years

🔹 4. Bivariate Analysis

Gender vs Survival:
🧍‍♀️ Females had a much higher survival rate than males

Class vs Survival:
🏆 1st class passengers had the highest survival rate

Age vs Survival:
👶 Younger passengers (especially children) were more likely to survive

Embarked vs Survival:
🚢 Passengers from Cherbourg (C) had higher survival chances

🔹 7. Key Insights

✅ Women and children had higher survival rates
✅ 1st class passengers were more likely to survive
✅ Higher fare = better chance of survival
✅ Most passengers embarked from Southampton (S)

🔹 8. Conclusion

The Titanic dataset highlights that social and economic factors (like gender, class, and fare) played a major role in survival.
This dataset is ideal for practicing data visualization, feature engineering, and classification models in data science.
