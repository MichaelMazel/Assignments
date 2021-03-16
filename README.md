<a name="BackToTop"></a>

# Assignments

>This repository stores select assignments from my Master’s in Data Science program. These are generally smaller scale pieces of work, and therefore, do not exist as stand-alone projects on my repo page. A summary for each assignment can be found below. 


---


## Table of Contents
- [SQL-Queries](#SQL-Queries)
- [Beer-EDA-and-Prediction](#Beer-EDA-and-Prediction)


---


<a name="SQL-Queries"></a>

## SQL Queries
This python script connects to the MySQL databases on my local machine. Before I performed these SQL queries, I created a third normal form schema from a collection of data about a fictional basketball tournament. Afterwards, I performed queries for a fictional bike shop.

![Bball_Schema](https://github.com/MichaelMazel/Assignments/blob/main/SQL_Queries_Schemas/BBall_Schema.PNG)

Some example questions include:


1. List the player names whose highest score in a game is more than 10 points higher than their personal average.
2. Find orders from 4th quarter 2012 that took 4 or more days to ship.
3. List the customers who have purchased a bike but not a helmet.


#### How to Use
The mysql.connector library was used to link Python to MySQL.  
The data sets were provided from my database class.

##### Technologies
Jupyter Notebooks  
Python version 3.8.5

[Back to Top](#BackToTop)


---


<a name="Beer-EDA-and-Prediction"></a>

## Beer EDA and Prediction
In this group project, my partner and I used two data sets involving United States craft breweries and craft beers. Our exploratory data analysis spanned from examining the number of breweries in each state to the relationship between beer variables, such as ABV, ounces, and length of beer names. We then used KNN and Naive Bayes to classify a beer as either an IPA or Ale.

Below are several of our findings via graphs
![Breweries by State](https://github.com/MichaelMazel/Assignments/blob/main/Beer-EDA-and-Prediction_files/figure-gfm/unnamed-chunk-6-1.png)

![ABV vs IBU scatterplot](https://github.com/MichaelMazel/Assignments/blob/main/Beer-EDA-and-Prediction_files/figure-gfm/unnamed-chunk-26-1.png)


We also identified tours offered by the top beer producers. We matched this with a heat map of breweries per state.
![Brewery Tours US Heat Map](https://github.com/MichaelMazel/Assignments/blob/main/Beer-EDA-and-Prediction_files/figure-gfm/unnamed-chunk-39-1.png)



Finally, we accurately predicted if a beer was an IPA or Ale 87% of the time using KNN. This slightly outperformed Naive Bayes' accuracy of 84.5%.

#### How to Use
The data sets used in this analysis were provided by my data science class. They can be found under Beer-EDA-and-Prediction-Data-Sets.

##### Technologies
R Studio  
R version 4.0.3

#### Authors
Michael Mazel and Alexandre Jasserme


[Back to Top](#BackToTop)