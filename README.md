# PyBer Analysis

## Overview
Analyzing and visualizing rideshare data from January to May 2019 to help improve access to ride-sharing services and determine affordability for underserved neighborhoods.

## Results
<font size="2">*Note: Figure numbers do not correspond to file names in the Analysis directory.*</font>

![summary](/Analysis/pyber_summary_df.png)<font size="2">*(Figure 1)*</font>

    Figure 1 offers a general summary of the data. From it, we can gather that as one 
    moves further from heavily populated areas, fares increase while riders and drivers 
    become more sparse.
<br>

### Rides and Drivers
#### Total Rides
![boxplot](/Analysis/Fig2.png)<font size="2">*(Figure 2)*</font>

First examining the total number of rides for each city type, it is apparent that the average number of rides declines as one moves from urban to rural areas. This is not surprising, suburban areas are less populous than urban areas, and rural areas are less populous than suburban. What is notable is the lack of rides in rural areas, whose deficit is most easily understood by examining suburban cities.

While suburban ride counts tend toward the middle of the data, the great heights these cities *can* reach are worth noting. The highest ride counts in suburban areas would place near the top 25% in urban areas (around 24-27 rides), and well within the average. The same cannot be said for rural cities, whose busiest areas still sit below the lowest 25% of the suburban data. There is discrepancy between the urban and suburban plots (which we'll get to later), but at least the latter shows potential. The approach for rural areas may need a drastic overhaul.

<br>

#### Total Drivers
![boxplot](/Analysis/Fig4.png)<font size="2">*(Figure 3)*</font>

Antithetically, urban areas have become over-served. The number of drivers in urban areas considerably outnumbers the number of drivers in both suburban and rural areas combined. And while there may be greater demand - bustling cities have attractions, tourists, etc. - the market has become over-saturated. The average number of drivers in these cities is around 37, while the average number of rides is about 25, for a ratio of ~1.5 drivers per ride. No other city type has a ratio greater than or equal to one.

The problem here is that with so many drivers and so few rides, there's not enough work to go around. Supply has so greatly exceeded demand that some drivers will inevitably be left without any rides. What good does that do anyone? It's not that these drivers should be fired or relocated, but a new marketing strategy may be in order.

<br>

### Fares

To further illustrate the need for restructure let's take a look at the fare data for each city type.

#### Average Fare per Ride & Driver
![avg fare](/Analysis/avg_fare.png)<font size="2">*(from Figure 1; top to bottom: Rural, Suburban, Urban)*</font>

It is immediately clear that more populated areas offer cheaper rides, presumably because of the number of drivers and distance to be traveled. The numbers here are promising, in order to promote growth in less profitable cities (i.e., rural cities) it is important that drivers are making enough to incentivize driving while rides are still affordable enough to generate rides.

Let's take a look at total fares for each city type.

<br>

#### Total Fare by City Type
![fare by city type](/Analysis/PyBer_fare_summary.png)
![fare pie chart](/Analysis/Fig5.png)

Even with cheaper rides, urban cities still bring in more revenue than any other city type. It is a testament to the fact that urban cities are resilient, and will generate profit under any circumstance, while other city types may need more care and attention.

It is important to note that urban cities still have room to improve - having a lot of drivers is only good if there are a lot of rides - but do not need as much work as the other two types. Suburban cities generate about as much revenue as one would expect, but rural cities struggle mightily, and will require more creative solutions to prove viable. 

<br>

## Summary

The important takeaways here are how over- and under-served urban and rural cities are, respectively. Suburban areas perform as expected, with some quite busy (typically those close to bigger cities), and others not so much. The problem is generating more business in urban and rural areas. As far as urban cities, there a great number of drivers, which is not a problem, but hardly enough rides. It's not a matter of failed business, but untapped potential. Rural cities, on the other hand, need a kickstart.

Below are a few possible solutions:
1. Better marketing in urban cities to increase rides.
2. Incentives for drivers in rural areas.
3. Incentives for drivers to complete longer trips.
4. Discounts on trips over 50 miles.

The simple solution for urban cities is better marketing. Investing in advertising in big cities will help generate more business. Rural cities need a little more than that, perhaps offering incentives for drivers in these cities (i.e., every X trips completed in the area), or offering incentives for drivers from outside the area to travel there by incentivizing longer trips. On the flip side, offering customers slight discounts on trips over 50 miles could encourage those in rural areas to save money and gas and use PyBer, creating more rides.

In short, business is bustling, but we've only scratched the surface in so many cities. There's plenty of work that can be done.