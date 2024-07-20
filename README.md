#  Analysis and Predict The flight ticket price

> ### Introduction
* The flight booking dataset obtained from the 'Ease My Trip' website represents an internet platform used by potential passengers to purchase flight tickets. A thorough study of this data will help uncover valuable insights that can greatly benefit passengers.
* ### Problem statement
* The objective of this project is to analyze how flight ticket prices vary across different columns and identify which columns are most responsible for that. Additionally, we have to build a machine learning model that can predict the ticket price for new passengers based on input parameters like airline, source city, destination city, class, and other relevant features.
> ### Source of dataset
 * We collected the dataset from [kaggle.com](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction)
 
 > ### Size of dataset
 * Size of airline_dataset is 24.68 MB

 > ### About the dataset
* Dataset contains information about flight booking from the website Easemytrip for flight travel between India's top 6 metro cities. 
* Dataset contains 11 columns namely - 'Unnamed: 0', 'airline', 'flight', 'source_city', 'departure_time', 'stops', 'arrival_time','destination_city', 'class', 'duration', 'days_left', 'price'.

> ### Libraries
* Numpy
* Pandas
* Matplotlib
* Seaborn
* Sklearn
> ### EDA Section
 
* Does price vary with Airlines?

![barplot](price_airline.png)

Vistara airline average ticket price is very high(around 30000 rs) and AirAsia average ticket price is much less(around 5000 rs)compare to other airlines.

* How does stops column affect ticket price?
  
![sr](stops.png)

The flights that take one stop between the source and destination cities have ticket prices higher, over 20,000 rupees. The flights that have zero stops between the source and destination cities have the lowest ticket prices, around 10,000 rupees

* Do flight durations play a significant role in ticket pricing?
![scatter](scatter.png)
 
 Here flight duration do not play a significant role in ticket pricing and we can't see any significant relationship between price and duration.

 

 
