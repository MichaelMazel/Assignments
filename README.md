<a name="BackToTop"></a>

# Assignments

>This repository stores select assignments from my Master’s in Data Science program. These are generally smaller scale pieces of work, and therefore, do not exist as stand-alone projects on my repo page. A description for each assignment can be found below, along with some findings. 


---


## Table of Contents
- [SQL-Queries](#SQL-Queries)
- [Beer-EDA-and-Classification](#Beer-EDA-and-Classification)


---


<a name="SQL-Queries"></a>

## SQL Queries
This python script connected to the MYSQL databases on my local machine. Before I performed these SQL queries, I created a third normal form schema from a collection of data about a fictional basketball tournament. Afterwards I performed queries for a fictional bike shop.

![Bball_Schema](https://github.com/MichaelMazel/Assignments/blob/main/SQL_Queries_Schemas/BBall_Schema.PNG)

Some example questions include:
-List the player names whose highest score in a game is more than 10 points higher than their personal average
-Find orders from 4th quarter 2012 that took 4 or more days to ship
-List the CUSTOMERS who have purchased a bike but not a helmet


### How to Use
The mysql.connector library was used to link Python to MYSQL
The data sets were provided from database class

#### Technologies
Jupyter Notebooks  
Python version 3.8.5

[Back to Top](#BackToTop)


---


<a name="Beer-EDA-and-Classification"></a>

## Beer EDA and Classification
In this group project, my partner and I used two data sets involving United States craft breweries and craft beers. Our exploratory data analysis spanned from examining the number of breweries in each state to the relationship between beer variables, such as ABV, ounces, and length of beer name. We then used KNN and Naive Bayes to classify a beer as either an IPA or Ale

Below are several of our findings via graphs
![Breweries by State](https://github.com/MichaelMazel/Beer-EDA-and-Prediction/blob/main/EDA-and-Prediction_files/figure-gfm/unnamed-chunk-6-1.png?raw=true)

![ABV vs IBU scatterplot](https://github.com/MichaelMazel/Beer-EDA-and-Prediction/blob/main/EDA-and-Prediction_files/figure-gfm/unnamed-chunk-26-1.png?raw=true)


We also identified tours offered by the top beer producers. We matched this with a heat map of breweries per state.
![Brewery Tours US Heat Map](https://github.com/MichaelMazel/Beer-EDA-and-Prediction/blob/main/EDA-and-Prediction_files/figure-gfm/unnamed-chunk-38-1.png?raw=true)



Finally, we accurately predicted if a beer was an IPA or Ale 86.3% of the time using KNN. This slightly outperformed Naive Bayes' accuracy of 83.8%.

### How to Use
The data sets used in this analysis were provided by my data science class. They can be found under Beer-EDA-and-Prediction-Data-Sets

#### Technologies
R Studio  
R version 4.0.3

### Authors
Michael Mazel and Alexandre Jasserme


[Back to Top](#BackToTop)