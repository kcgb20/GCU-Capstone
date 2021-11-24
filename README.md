# Predicting Eurovision Finalists
## GCU Data Science MS Capstone Project


**Introduction**  
This project involves predictive modeling for the Eurovision Song Contest. 
During the contest, the contestants are placed into two different semi-finals, and ten acts from each semi-final will advance to the grand final. 
The models I am building will predict which countries pass on to the grand final.
Feel free to download the data set and Python code to run it yourself.
  
**Data Set**  
The data set that is being used in the modeling is Eurovision Data.csv
Years 2012 thru 2021 are represented in this data.
The values in this data set are as follows:
  
| Variable | Source |
|----------|--------|
| Country | Wikipedia |
| Artist | Wikipedia |
| Song | Wikipedia |
| Year | Wikipedia |
| Semi | Wikipedia |
| Qualified | Wikipedia |
| Place | Wikipedia |
| Running Order | Wikipedia |
| Returning Artist | Wikipedia |
| YouTube Views | YouTube |
| YouTube Upvotes Ratio| YouTube |
| Spotify Listens | Spotify |
| Sung in English | Wikipedia |
| Pop | Personal Determination |
| Wiwi Jury | WiwiBloggs |
| OGAE Rating | OGAE |
| Dance | Chosic |
| Energy | Chosic |
| Acoustic | Chosic |
| Happy | Chosic |
| Speech | Chosic |
| Live | Chosic |
| Loud | Chosic |
| Tempo | Chosic|
| Odds | Eurovision World |
  
The variables YouTube Views, YouTube Upvotes Ratio, and Spotify Listens are ranked within
their year and semi-final, with 1 being the act with the highest value.
  
Feel free to add additional years to the data set or add additional variables to try in the model.
  
  
**Code**  
The modeling code is under Capstone Code.ipynb
This code will create the following types of models:  
-- Linear Regression  
-- Linear Regression, reduced variable model  
-- Logistic Regression  
-- Logistic Regression reduced variable model  
-- Decision Tree  
-- Random Forest  
-- Naive Bayes  
-- Ensemble  
  
The reduced variable models are based on including only variables that are significant from
the full-variable models.
The decision tree model is limited to 5 levels.
The random forest model uses 1000 trees.
  
If you run this model you will need to change the path to your data.
  
You may feel free to add or remove variables in the model as you see fit.
  
If you add years to the data, make sure to add running the predictions at the end of the code.
  
  
**Exported Data**  
The Python code will export data intended to be used for Tableau.
You may view the Tableau Workbook at the below link.
You should also be able to download the Tableau workbook if you would like to modify it.
https://public.tableau.com/app/profile/kc.grace/viz/Baker-DataScienceCapstone/LandingPage