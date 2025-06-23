# Dataset-CleaningTitanic Dataset - Data Cleaning & Preprocessing 🚢

Objective The objective was to explore the research areas in each segment and synthesize blend of scientific knowledge with the current situation of the artificially aged customers.
It is a part of my AI/ML internship in which I aimed to clean and preprocess Titanic dataset to use it in the machine learning process. The idea is to transform the raw data into a properly organized form to be modeled.


## Tools
- Python
- Pandas
- NumPy
Seaborn /Matplotlib
- scikit-learn


Actions That Were Undertaken

1. **Data Loading and Exploration**
Application of the `pandas` library to read the Titanic-Dataset.csv
Looked into missing values, shape, and datatypes

2. **Missing Value Treatment**
Age: filled with median
- Embarked: inlaid with mode
- Cabin: discarded because of a significant number of missing data

3. **Coding of Categorical Variables**
One-hot encoded Sex, Embarked
`Name` had extracted and encoded `Title`

4. **Feature Engineering**
Added the new feature that is `FamilySize = SibSp + Parch + 1`

5. **Feature Scaling**
Normalized the `Age` and `Fare` by `StandardScaler`


## Final Feature Columns
`Survived` (Target)
`Pclass`, `Age`, `Fare`, `FamilySize`
- `Sex_male`
Embarked Q, embarked S
Title_Mr, Title_Mrs, Title_Miss, Title_Rare


What is Unique about This?
Retrieved feature of Name Title
Produced a significant aspect of **FamilySize**
Dataset is cleaned and engineered and ready to become ML!

Author
Mallikarjun SY- AI/ML Intern
