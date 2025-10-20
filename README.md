

AI & ML Internship Task 1: Data Cleaning & Preprocessing
🎯 Objective
Solve Task 1: Data Cleaning & Preprocessing using the Titanic Dataset to prepare it for a machine learning model.

🛠 Tools
Language: Python 3.x

Libraries: pandas, numpy, scikit-learn, matplotlib/seaborn

Dataset: Titanic-Dataset.csv

✅ Key Preprocessing Steps
Step	Column(s)	Strategy
Missing Values	Cabin	Dropped (Excessive nulls)
Age	Imputed with Median
Embarked	Imputed with Mode
Outlier Handling	Fare	Detected via Boxplot and removed using the IQR method.
Encoding	Sex, Embarked	One-Hot Encoding (pd.get_dummies) was applied.
Scaling	Age, SibSp, Parch, Fare	Standardization (StandardScaler) was applied to normalize feature ranges.
Dropped Columns	PassengerId, Name, Ticket	Removed as they are not useful for model training.

Export to Sheets

🚀 How to Run
Clone this repository.

Install dependencies: pip install pandas numpy scikit-learn matplotlib seaborn.

Execute the Python script/Jupyter Notebook ([YourFileName.py/ipynb]).
