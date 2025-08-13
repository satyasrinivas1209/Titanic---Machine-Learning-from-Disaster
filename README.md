# Titanic Data Analysis
##  Overview
This Jupyter Notebook performs **Exploratory Data Analysis (EDA)** on the Titanic dataset.  
It uses Python data science libraries to load, explore, visualize, and gain insights from the dataset.

##  Dataset
The notebook uses the **Titanic training dataset** from Kaggle:  
`train.csv` — containing passenger details like age, class, fare, survival status, and more.

**Key Columns:**
- `Survived` – Survival indicator (0 = No, 1 = Yes)
- `Pclass` – Passenger class
- `Age` – Age of passenger
- `Fare` – Ticket fare
- `Sex` – Gender of passenger
- `Embarked` – Port of embarkation

##  Requirements
Install the following Python libraries before running the notebook:

## Features of the Notebook
- Loads Titanic dataset into a Pandas DataFrame
- Performs **data cleaning** (handling missing values, type conversions, etc.)
- Generates **statistical summaries**
- Visualizes data using Matplotlib and Seaborn:
  - Distribution of Age
  - Boxplots comparing Age across Passenger Classes
  - Fare distribution by survival status
  - Correlation heatmaps for numeric features

## How to Run
1. Clone or download this repository.
2. Place `train.csv` in the same folder as the notebook (or update the file path inside the code).
3. Open the notebook:
4. Run cells sequentially to reproduce the analysis.

## Example Visualizations
- Age Distribution Histogram
- Boxplot: Age vs Passenger Class
- Boxplot: Fare vs Survival Status
- Heatmap of Feature Correlations

