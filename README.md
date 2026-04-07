# HexSoftwares_Titanic_EDA
EDA on Titanic Dataset using Python

# Titanic Exploratory Data Analysis (EDA)

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the famous Titanic dataset to understand the factors that influenced passenger survival.
The analysis includes data cleaning, statistical exploration, and visualization to uncover meaningful insights.

## Objectives

* Understand the structure of the dataset
* Handle missing values effectively
* Analyze relationships between different features
* Visualize patterns affecting survival
* Extract actionable insights



## Dataset Information

* Dataset: Titanic Dataset
* Total Records: 891 passengers
* Features: 12 columns


### Key Columns:

* `Survived` → Survival (0 = No, 1 = Yes)
* `Pclass` → Passenger class (1st, 2nd, 3rd)
* `Sex` → Gender
* `Age` → Age of passenger
* `Fare` → Ticket fare
* `Embarked` → Port of embarkation


## Technologies Used

* Python 
* Pandas (Data Handling)
* Matplotlib (Visualization)
* Seaborn (Advanced Visualization)
* Jupyter Notebook



## Data Cleaning Steps

* Filled missing values in `Age` using mean
* Filled missing values in `Embarked` using mode
* Dropped `Cabin` column due to excessive missing values
* Verified dataset for null values



## Exploratory Data Analysis

### 1. Survival Analysis

* Count of passengers who survived vs not survived

### 2. Gender-based Analysis

* Compared survival rate between males and females

### 3. Class-based Analysis

* Analyzed survival across passenger classes

### 4. Age Distribution

* Studied age patterns using histogram

### 5. Correlation Analysis

* Used heatmap to identify relationships between numerical features



## Visualizations

* Count plots
* Histograms
* Box plots
* Heatmaps



## Key Insights

* Female passengers had a significantly higher survival rate than males
* Passengers in 1st class had better survival chances
* Higher fare passengers were more likely to survive
* Younger passengers showed slightly better survival rates
* Socio-economic status played a major role in survival


## Conclusion

The analysis highlights that **gender and passenger class were the most influential factors** affecting survival on the Titanic.
EDA techniques helped uncover patterns and provided valuable insights from the dataset.


## Project Structure


Titanic-EDA/
│── Titanic_EDA.ipynb
│── titanic.csv
│── README.md



## Future Improvements

* Apply machine learning models for prediction
* Perform feature engineering
* Build interactive dashboards



## GitHub Repository

https://github.com/nickxjarvis1810/HexSoftwares_Titanic_EDA



## Acknowledgment

This project was completed as part of an internship assignment with HexSoftwares.
