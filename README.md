FIFA Player Dataset – Exploratory Data Analysis (EDA)

This project explores a dataset of professional football players from the FIFA game series. The goal is to understand the structure of the data. clean inconsistent fields. and examine relationships between player attributes. performance ratings. and market values using Python.

Project Overview

The dataset includes information about over eighteen thousand players. covering age. nationality. skill ratings. physical traits. wages. market values. release clauses. and more. The notebook walks through importing the dataset. cleaning it. visualising it. and interpreting patterns across attributes.

Steps Performed

Data Importing
The dataset was loaded from an Excel file using pandas.

Data Cleaning
Several fields required cleaning or conversion. including
. fixing monetary fields into numeric values
. handling missing values in physical and skill attributes
. standardising dates into year format
. ensuring correct data types for analysis

Exploratory Data Analysis
The analysis covered
. histograms of Age. Overall rating. and Potential
. correlation ranking of all numeric attributes relative to Overall rating
. heatmap visualising relationships between technical attributes
. scatter plots for Value vs Overall and other pairs
. count summaries of Nationality. Club. and Preferred Foot

Insights

Players peak in their mid twenties. and high rated players show strong alignment with mental and technical attributes such as Reactions and Composure. Market value increases sharply with Overall rating. Right foot is dominant across players. Goalkeeper attributes show weak or negative correlation with Overall because the dataset features many more outfield players.

Tools Used

Python
Pandas
Matplotlib
Seaborn
Jupyter Notebook

How to Use

Clone the repository. open the notebook. and run cells from top to bottom. The dataset file should be placed in the correct directory for loading.

Future Improvements

The analysis can be extended by exploring positional breakdowns. club level summaries. clustering of player styles. or simple predictive models for value or rating.
