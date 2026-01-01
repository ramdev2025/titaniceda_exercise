# Titanic Exploratory Data Analysis (EDA)

This project performs a detailed exploratory data analysis on the classic Titanic dataset to uncover trends, patterns, and insights regarding passenger survival.

## Author
**Ramdev Calope**

## Project Overview
The goal of this analysis is to determine which factors most influenced the survival of passengers aboard the Titanic. By leveraging Python's data science stack, we explore relationships between demographics, socio-economic status, and survival rates.

## Dataset
The project uses the standard Titanic disaster dataset, containing information such as:
- **Survived**: Survival (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Sex**: Passenger gender
- **Age**: Age in years
- **SibSp**: # of siblings / spouses aboard the Titanic
- **Parch**: # of parents / children aboard the Titanic
- **Fare**: Passenger fare
- **Embarked**: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Key Findings & Insights
- **Gender Bias**: Females had a significantly higher survival probability compared to males, suggesting a "women and children first" rescue policy.
- **Socio-Economic Status**: There is a clear correlation between `Pclass` and survival. First-class passengers had the highest survival rates, while third-class passengers (the majority) had the lowest.
- **Family Dynamics**: Passengers traveling alone or with small families generally fared better than those in very large families (>4 members), especially in lower passenger classes.
- **Data Gaps**: Identified significant missing values in the `Age` and `Cabin` columns, which are critical for future predictive modeling.

## Technologies Used
- **Python**: Core programming language.
- **Pandas/Numpy**: Data manipulation and numerical computation.
- **Matplotlib/Seaborn**: Data visualization and plotting.
- **Jupyter Notebook**: Interactive analysis environment.

## Getting Started
1. Clone this repository.
2. Ensure you have the required libraries installed: `pip install pandas matplotlib seaborn`.
3. Open `eda-titanic-ramdevcalope.ipynb` in Jupyter Notebook or VS Code to view the analysis.
