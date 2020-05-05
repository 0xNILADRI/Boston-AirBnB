# Boston-AirBnB

## Introduction

Airbnb, Inc. is an online marketplace for arranging or offering lodging, primarily homestays, or tourism experiences. The company does not own any of the real estate listings, nor does it host events; it acts as a broker, receiving commissions from each booking.[6] The company is based in San Francisco, California, United States.

The company was conceived after its founders put an air mattress in their living room, effectively turning their apartment into a bed and breakfast, in order to offset the high cost of rent in San Francisco; Airbnb is a shortened version of its original name, AirBedandBreakfast.com.

![alt text](https://raw.githubusercontent.com/niladrihere/Boston-AirBnB/master/airbnb_logo.png)

Source : Wikipedia

#### Context
Since 2008, guests and hosts have used Airbnb to travel in a more unique, personalized way. As part of the Airbnb Inside initiative, this dataset describes the listing activity of homestays in Boston, MA.

#### Content
The following Airbnb activity is included in this Boston dataset:

Listings, including full descriptions and average review score
Reviews, including unique id for each reviewer and detailed comments
Calendar, including listing id and the price and availability for that day

#### Acknowledgement
This dataset is part of Airbnb Inside, and the original source can be found here.

#### Python libraries used:

      1. datetime
      2. numpy
      3. pandas
      4. matplotlib
      5. seaborn
      6. sklearn
      7. vaderSentiment

## Aim

Data analysis has been performed on the data set to drive out the important outcomes from the data.
The data set contains the listing details of Airbnb properties in Boston region which provides
necessary details for the property like listing id, property description, neighborhood overview, house rules, day first listed, pincode, etc . This data set can have much more categorical columns
than it currently has therefor new columns have to be made for proper analysis, but first of all data needs to be cleaned and outliers must be removed. The reviews data set consists of the reviews provided by the customer to their respective properties and calendar data set contains the details of price and availability of the properties. Hence from these details we can fetch out the different variables which correlates to the pricing of the properties.

### Questions that could be raised after analyzing and manipulating the data :

  1. Which neighborhoods in Boston are the most costliest and cheapest ?
  2. Does the total number of bookings depends on the price of the properties in the neighborhood ?
  3. What are the different property types and room types which people prefer to book ?
  4. Which neighborhoods in Boston are the highest and lowest rated by people along with average price and booking count ?
  5. What are the different factors that relates to price of the property ?


  This question can be sub divided into three sub categories - `amenities`,`ratings and reviews` and `property characteristics`.
  6. Which months have the highest prices of bookings ?
  7. Which factors have dependency to the price of the property ?


## Conclusion

A detailed conclusion has been provided in the Communication_airbnb_boston.ipynb.

### Sources :
      1. Boston-AirBnB Data Set (Kaggle)
      2. Stackoverflow
