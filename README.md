# CSI_Week04
Exploratory Data Analysis on the Titanic dataset using advanced imputation and Seaborn visualizations. Week 4 internship assignment @ Celebal Technologies.

This assignment explores the Titanic dataset to understand the survival patterns of passengers based on multiple factors like gender, age, class, fare, family size, and embarkation port. The focus is on exploratory data analysis (EDA) and handling missing values effectively.

The analysis involves:
: Data Cleaning and Advanced Missing Value Imputation
: Univariate and Bivariate Data Visualization
: Visual Analysis using Seaborn & Matplotlib

This assignment was part of my internship at Celebal Technologies, Week 4 – with the goal of practicing EDA and preprocessing techniques.

Dataset Info
Source: Titanic Dataset via Seaborn
Rows: 891
Columns: 15
Target Variable: survived (0 = No, 1 = Yes)

Key Features Used:
pclass – Passenger Class (1st, 2nd, 3rd)
sex – Gender
age – Age
sibsp – Siblings/Spouse aboard
parch – Parents/Children aboard
fare – Ticket Fare
embarked – Port of Embarkation
who, deck, alone – Additional categorical indicators

Visualizations Included
Count Plots (Class, Gender, Embarked, Alone, Who)
Histograms (Age, Fare)
Boxplots (Detecting outliers in Age and Fare)
Violin Plots (Survival vs Age/Fare)
Bar Plots (Survival rate by Categorical Variables)
Correlation Heatmap (Numeric Feature Correlations)

Key Insights
Females had a much higher survival rate than males.
1st class passengers were more likely to survive than those in 2nd or 3rd.
Younger passengers, especially children, had better survival chances.
Passengers with higher fare values tended to survive more.
Embarkation from Cherbourg was associated with higher survival.

Tools & Libraries
Python 3.x
Pandas 
NumPy
Matplotlib 
Seaborn 
Scikit-learn – Missing value imputation using IterativeImputer

