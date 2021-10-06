# Data Cleaning Practice Exercise - Assignment 1

**Goal:** Implement steps required to perform data cleaning and preprocessing and visualization of the given noisy dataset 

**Data Cleaning:** process of fixing or removing incorrect, corrupted, incorrectly formatted, duplicate, or incomplete data within a dataset. If data is incorrect, outcomes and algorithms are unreliable.

**Data Preprocessing:** manipulation or dropping of data before it is used in order to ensure or enhance performance

Step 1: Import all the required libraries and read csv input file

Step 2:  Dropping the rows where the name of the AirBnb property is less than 5 characters, 
#on closer inspection found that these values were invalid. Hence getting rid of those records.

Step 3: Dropping the rows where the host name of the person listing the AirBnb property is less than 3 characters, 
#on closer inspection found that these values were invalid. Hence getting rid of those records.

Step 4:  Get unique count for each column and Calculating statistical data

Step 5: Dropping columns that do not contribute in training the model

Step 6: Renaming the columns to have more apt and meaningful names

Step 7: Dropping the rows where the availablity for that property is 0.

Step 8: Removing propeties where the price of a "Private room" room type is less than 30, as it inaccurate value for an avg price in NYC listing

Step 9: Removing propeties where the price of a "Entire home/apt" room type is less than 50, as it inaccurate value for an avg price in NYC listing

Step 10: Data Exploration and visualization 

Step 11: Plot locations with heatmap intensity as per the Price of the properties

Step 12: Plotting a chart to show the price distribution based on the NYC boroughs

step 13: Applying model training with scikit learn - Linear Regression

Step 14: Training the model with number of reviews and price to predict price of properties on AirBnb listings - popularity
