# House-sales-in-king-county-USA
Project is suggested by coursera as a final assignment on Data Analysis course for IBM Data Science professional certificate 
The goal of this project is to analyze and predict the price of housing in king County for 2016
## About the Work:
- In this project we will do:
#### Data Wrangling
#### Exploratory Data Analysis
#### Exploring Data through Visualizations Seaborn and MatPlotLib
#### Model Development
#### Model Evaluation and Refinement

I used various regression methods for prediction (Ridge Regression ,XGBregressor,Simple & Multiple Linear Regression,Polynomial Regression..) and some metrics like R-squared values and mean of R^2 obtained from K-fold cross validation to compare different models.
###### Having R-squared value closer to 1 means a better fit

## Dataset : https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/DA0101EN/coursera/project/kc_house_data_NaN.csv
Our dataset contains house sales prices for King County which includes Seattle.
It includes homes solded between May 2014 and May 2015,dataset columns are as follows:

* id :a notation for a house
* date: Date house was sold
* price: Price is prediction target
* bedrooms: Number of Bedrooms/House
* bathrooms: Number of bathrooms/bedrooms
* sqft_living: square footage of the home
* sqft_lot: square footage of the lot
* floors :Total floors (levels) in house
* waterfront :House which has a view to a waterfront
* view: Has been viewed
* condition :How good the condition is Overall
* grade: overall grade given to the housing unit, based on King County grading system
* sqft_above :square footage of house apart from basement
* sqft_basement: square footage of the basement
* yr_built :Built Year
* yr_renovated :Year when house was renovated
* zipcode:zip code
* lat: Latitude coordinate
* long: Longitude coordinate
* sqft_living15 :Living room area in 2015(implies-- some renovations) This might or might not have affected the lotsize area
* sqft_lot15 :lotSize area in 2015(implies-- some renovations)



