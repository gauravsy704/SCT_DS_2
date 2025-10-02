# SCT_DS_2
SCT_DATASCIENCE_Task2, data source and outputs.

# Task Overview
Performed data cleaning and exploratory data analysis (EDA) on the Titanic dataset from Kaggle. Investigated the relationships between variables and identified key patterns and trends in the data using Python, with a focus on survival rates, passenger demographics, and embarkation details.

## Tools Used
- Python (Jupyter Notebook)
- Pandas
- Seaborn, Matplotlib
- Scikit-learn (for imputation)
- GitHub for version control

## Key Findings
- Significant missing data was present in 'Age', 'Cabin', and 'Embarked' columns; handled with mean and mode imputation.
- The dataset included 891 passengers, though historical records show more, indicating partial data coverage.
- Survival patterns:
  - Females had a much higher survival rate than males.
  - First class had the highest survival rate; third class had the lowest.
  - Passengers who embarked from Port C had a higher survival rate compared to other ports.
- Data visualization revealed clear class and port influences on survival outcomes.

## Files
- train.csv: Titanic dataset from Kaggle
- SCT_DS_2.ipynb: Jupyter notebook with EDA, visualizations, and imputation steps
- SCT_DS_2.pdf: Graphs and screenshorts

## Methodology
1. Loaded and inspected the Titanic dataset from Kaggle.
2. Checked for missing values and imputed 'Age' (mean), 'Cabin' and 'Embarked' (mode).
3. Explored distributions of passenger class, embarkation port, and survival rate.
4. Created visualizations to analyze survival by gender, class, and port.
5. Investigated variable relationships and identified data trends.

## Author
[GAURAV SINGH YADAV] - Data Science Intern, SkillCraft Technology
