# Calculating the shipping price
Final project for the Building AI course

## Summary

Help calculate the shipping price that will be added to the bill, considering the distance, cost per kilometer, estimated trip duration, any hills above sea level. 


## Background

This AI will help reduce the time and process of setting a price for the freight needed by customers, the displeasure in waiting or in the price charged.

This is how you make a list, if you need one:
* When the seller is invoicing the materials he must add by pressing several buttons, the freight cost.
* The transportation coordinator does not have a freight price table, which considers different factors of the shipment, sometimes does not even know the destination, and sets prices verbally through a phone call or message
* Sometimes prices can be very low or very high, and there is no valid reason to explain to the customer the reason for the price set.


## How is it used?

1. The seller fixes the destination of the purchase on a map.  1 minute
2. The AI debe considerar
  a. distance(60%), type of road(20%), meters above sea level, from the starting point to the destination(20%) and the ratio units/weight in pounds.
  b. Each parameter must be multiplied with a previously established cost to give a result
  c. The IA must be able to use the information generated to estimate other freight prices by proximity, and thus be able to reduce calculations at the discretion of a human 
