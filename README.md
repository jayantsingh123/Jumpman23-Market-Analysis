## Introduction

The food delivery apps grow and make it more attractive for time-starved consumers and generations millennial and Z. According to the food delivery market research of Allied Market Research, the market for delivery mobile apps to hit $16.6B in 2023. The food delivery market analysis shows us that it was valued at about $3.7B in 2017. The segment is predicted to grow the fastest at 28% by 2023. 

https://user-images.githubusercontent.com/27310613/89149303-faac2480-d510-11ea-8949-255ec0090293.png




In this project, we look at the various KPI's and their trend during October 2014 for the food delivery app, Jumpman23 in New York City.

## Dataset

The dataset contains delivery information for the orders delivered during October 2014. Its columns include;

* delivery_id: Every delivery has aunique identifier.
* customer_id: Customer identification number.
* jumpman_id: Carrier identification number.
* vehicle_type: Type of carrier vehicle. 
* pickup_place: Place from where food/item is picked.
* place_category: Category of the pick-up place.
* item_name: Name of the item object.
* item_quantity: Order quantity.
* item_category_name: Category of the order.
* how_long_it_took_to_order: Order time(in minutes)
* pickup_lat: Pick-up lattitude.
* pickup_lon: Pick-up longitude.
* dropoff_lat: Drop-off lattitude.
* dropoff_lon: Drop-off longitude.
* when_the_delivery_started: Time when the delivery started.
* when_the_Jumpman_arrived_at_pickup: Time when item was picked up.
* when_the_Jumpman_left_pickup: Time when the carrier left the pick-up spot.
* when_the_Jumpman_arrived_at_dropoff: Time when carrier delivered the item/food to the customer.

## Analysis Steps

We have followed top-down approach to analyze this dataset; get an overall idea regarding the performance of service in New York city, then dig deeper and look at the metrics at different granular levels.

**Question**: How is the business looking in New York City?

To answer the above question, a reasonable approach is to look at the trend of various KPI's which are relevant to the success of a food delivery platform. Some of the KPI's studied here include; 

* Weekly comparison of Average Daily Performance
* Average Item count per Delivery
* Average number of deliveries made per hour on a given day
* Average Order Duration
* Food Preparation time, and 
* Delivery time

Above terms are quite self explanatory and by no means is the comprehensive list of KPI's. But these are one of the most relevant ones to the best of our knowledge. Once we have an overall idea of the metrics in the city, it makes sense to look at these metrics in a bit more detailed fashion. Since success of food delivery platforms depends a lot on the availability of partner restaurants, it makes sense to look at above metrics from a geographical point of view.

## Do Some Boroughs Need More Attention?

In this section, we look at the health of the business across different boroughs of New York City, namely Queens, Manhattan, Brooklyn, Bronx and Statten Island. This datasets only has information regarding Brooklyn, Queens and Manhattan, therefore we will concentrate on them. Couple of outstanding highlights in this section include; Morning times are really busy for the carriers in Manhattan(probably due to the commuters to work), and  Overall Delivery time in Brooklyn is considerably higher. The second observation necessiates partnering with more restaurants in Brooklyn. 
