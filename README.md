# EDA 
Titanic Dataset Exploratory Data Analysis
This notebook performs an exploratory data analysis (EDA) on the Titanic dataset.

Data Loading and Overview
The dataset is loaded into a pandas DataFrame and the first few rows are displayed to get an initial look at the data.

Univariate Analysis - Categorical Data
Univariate analysis is performed on the categorical features of the dataset: Survived, Pclass, Sex, and Embarked.

Survived: The distribution of passengers who survived versus those who did not is visualized using a bar plot.
Pclass: The distribution of passengers across different passenger classes is visualized using a bar plot. The mean fare price for each passenger class is also calculated and displayed.
Sex: The distribution of male and female passengers is visualized using a bar plot.
Embarked: The distribution of ports of embarkation is visualized using a pie chart.
Frequency Tables and Mode: Frequency tables and the mode for each categorical column are calculated and displayed to show the exact counts and most frequent categories.
Univariate Analysis - Numerical Data
Univariate analysis is performed on the numerical features of the dataset: Age and Fare.

Age: A histogram and a distribution plot are used to visualize the distribution of passenger ages. A box plot is also used to identify potential outliers and visualize the five-number summary. The maximum, minimum, and mean age are calculated and displayed. The standard deviation of the age is calculated to understand the spread of the data.
Fare: A box plot is used to visualize the distribution of fare prices and identify potential outliers. The maximum, minimum, and mean fare are calculated and displayed. The standard deviation of the fare is calculated to understand the spread of the data.
Further Analysis
Future steps could include:

Bivariate analysis to explore relationships between variables (e.g., Survival rate by Sex or Pclass).
Handling missing values in columns like Age and Embarked.
Feature engineering to create new features from existing ones.
Building a predictive model to predict passenger survival.
