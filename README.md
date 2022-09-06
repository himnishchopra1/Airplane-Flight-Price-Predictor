# Airplane-Flight-Price-Predictor
A analysis of dataset and built a model to predict the price of an airplane flight.

link to dataset:
https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh

#### Skills Demonstrated:
•	Pandas
•	Numpy
•	Matplotlib
•	Seaborn
•	Random Forest Regression
•	Extra-Trees Regression
•	Cat Boost Regression

#### Methods Used:
•	Exploratory Data Analysis
•	Data Visualization
•	Data Cleaning, Feature Engineering
•	Model Building

#### Problem:

The aim of this project was to explore the different features of the dataset in order to determine different trends and explore the characteristics that determine the price of a flight from the various sources and destinations in the dataset. This information would then be used to produce a machine learning model that can predict the price of a airplane flight when certain information of the flight is entered such as the airline, destination, and number of stops.

#### Results:
These are some interesting insights found from exploring this data that travellers can consider when booking a flight to the destinations in the dataset in order minimize the price of the flight.

![aiplane graph1](https://user-images.githubusercontent.com/91419941/188706220-07629359-b98c-4796-8ae6-ab0b82b2c935.JPG)

Travellers can consider this graph when deciding their destination as different destinations have different airplane ticket prices.

![aiplane graph2](https://user-images.githubusercontent.com/91419941/188706400-00e25e95-966e-423b-b4d2-b68e95fd5c92.JPG)

Travellers can consider this graph when deciding which airline they want to fly in as different airlines have different travel prices.

#### Model Evaluation:

The Coefficient of Determination-R2 score was used to evaluate the models built in this project. This was the preferred method of evalution because it is the amount of the variation in the output dependent attribute which is predictable from the input independent variables. This is better as it can be observed what flight characteristics (destination, airline, source,etc) have the biggest impact on flight price and what specific flight options travellers should look for to get the cheapest flight possible for themselves.

The Cat Boost Regressor resulted in a 83 % R2 score meaning 83 % of the variability of the target can be explained by the model. This was the best performing model out of all the models.

Based on the analysis and model it was determined that the most important features that determine the price of a airplane flight is the Airline, Source, and Destination. 

