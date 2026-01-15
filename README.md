## Adult Census Income Analysis

This project analyses the Adult Census dataset to explore patterns associated with income levels.
The analysis focuses on data cleaning, feature engineering, exploratory data analysis, and a
logistic regression model to examine factors linked to earning more than $50K.

### Dataset
The project uses the Adult Census dataset, which contains demographic and employment-related
information such as age, education, occupation, working hours, and income category.

An additional dataset is used to map countries of origin to broader geographic regions.

Datasets are located in the `data` folder:
- `adult.csv`
- `countries_regions.csv`

### Analysis Notebook
The full analysis is contained in the Jupyter notebook:
- `notebooks/adult_census_income_analysis.ipynb`

### Methods
• Data cleaning and preparation  
• Handling missing and duplicated values  
• Feature engineering of demographic and work-related indicators  
• Exploratory data analysis with visualisations  
• Correlation analysis of numeric features  
• Logistic regression modelling for income prediction  
• Interpretation of results with ethical considerations  

### Key Insights
• Higher education levels are strongly associated with higher income  
• Individuals working longer hours tend to earn more on average  
• Certain occupations and marital status categories show strong relationships with income  
• Regional differences in income can be partly explained by education levels  

### Tools
Python, pandas, numpy, matplotlib, seaborn, scikit-learn

### Notes
This project focuses on analytical reasoning and interpretation rather than optimising predictive
performance. The model outputs reflect patterns in historical data and should not be interpreted
as causal relationships.
