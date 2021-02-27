# AirBnB-Seattle-Data-Analysis-Price-Prediction-



We will try to Answer some common Customer based question and finally try to create a good model to predict price for a future listing.


## Context

Since 2008, guests and hosts have used Airbnb to travel in a more unique, personalized way. As part of the Airbnb Inside initiative, this dataset describes the listing activity of homestays in Seattle, WA.


## Content

### The following Airbnb activity is included in this Seattle dataset:

Listings, including full descriptions and average review score
Reviews, including unique id for each reviewer and detailed comments
Calendar, including listing id and the price and availability for that day

   
   
 ## Installation
 
This project requires Python 3.x and the following Python libraries installed:

SciPy
NumPy
Pandas
matplotlib
seaborn
scikit-learn
warning
calendar
xgboost

Python Jupyter notebook has been used and is recommended for coding.


## Project Motivation

This dataset is really good to test variaty of skills in datascience and CRISP-DM process and has a variaty of dataset and a lot to analyse. Using the dataset, 3 questions i aspire to answer from the data.

I chose Airbnb data in Seattle, and have the following three questions:

Business Question we wil try to Answer-

Lets make this Customer Centric and try to There are 3 questions we would like to answer from our data.
    
   > When are listings typically available? 

                     Weekends only or all through the week?
                     Is there a seasonality pattern?
                     Are the neighbourhood variations?
                     We need to analyze the calendar dataset for this question.

   > Secondly we would try to look at the main factors that Drive the price for a property.


   > Using the above factors only we will try to create a prediction model to predict the price of a new listing.
   
   

## File Descriptions:

Jupyter Notebook (Analysis of Seattle AirBnB Dataset.ipynb)-  works related to the above questions.
seattle_calendar.zip - contains the Listing price , date and availability on the date
seattle_listings.csv - contains all data about the listings


## Result

For overall if we observe, then we see that availability do not have much variation on any day of the week for all neighborhood.
for seasonal it is quite interesting as we see availability is very low with a big dip in January and it peaks towards the end of the year. People tent to go on vacation towards the end of the year, hence the peak. Also availability is high in February and March and again it dips during July-August. If we try to find the reason for the dip in mid year,then we come to know that this is the time when the city is dry and inflow of people might be low and locals would be moving out of the city.

What we observe is the Most significant of the features in listings to give us price are bedrooms, bathrooms, property type, and accommodates. Which is very correct because when these features are better and in abundance then the price will definitely go up or down.

After running a few algorithms on the dataset, we see that Random Forest and Xgboost give us the best results with low Mean Square Error and better Coefficient of Determination.



## Acknowledgement

I would like to thank Kaggle for creating a learning model that is very efficient.