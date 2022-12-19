# motorcycle-fatalities
Analysis of behavioral risk factors that impact a person's likelihood of being involved in a fatal motorcycle accident.

This project's scope was to create a clean dataset that was analyzed using
descriptive statistical methods to ascertain what behavioral risk factors contribute
to motorcycle fatalities. The analysis included a Jupyter Notebook which contains
a logistic regression analysis of the dataset and determined which behaviors are
major risk factors.

To achieve the goal of this analysis, Excel was used to clean, filter, and
aggregate the datasets downloaded from the U.S. Department of
Transportation’s National Highway Transport Safety Administration website.
From there, the data was put into SQL Server, where queries and joins were
performed on the data to make it ready to bring into Jupyter Notebook. Finally, in
Jupyter, the dataset was transformed to run a logistic regression on it and
determine if behavioral risk factors increase a person’s chances of dying in a
motorcycle accident, and those individual risk factors were identified.

The files included here are the SQL statments used to create the dataset in 
SQL Server (sql-motorcycle-fatalities), the cleaned dataset (crss_1619_csv.csv),
and the Jupyter file.

