# Price Predictions of Second-Hand Cars (ongoing)

## Introduction
The goal is to optimize my search for second-hand cars using data science.

Below are the three car models that interest me:

- Kia Sorento
- Mazda CX-5
- Toyota Rav4

I will use the inventory of these three cars to train a model to estimate the price of a given car based on its characteristics (e.g., year, mileage, trim).

Hopefully, the model will help me identify good deals: if the predicted price is higher than the proposed price, it might be a good deal!

## Data Collection
There are several options:
- Web scraping of Carmax.com
- Web scraping or API of Cars.com
- Web scraping or API of Edmunds.com

Some characteristics (e.g., color and drivetrain) are directly available on the first page of results of Cars.com and Edmunds.com but not Carmax.com. The former also have larger car inventories and APIs to collect data. However, they also tend to have more missing data.

Depending on the number of results, I will limit the search results to a certain radius around my zip code (e.g., 500 miles) because it is unlikely that I will buy a car from across the country and prices do vary. Used cars tend to be cheaper in the northeast and in Florida compared to California for example ([reference](https://www.cnbc.com/2016/08/30/where-to-get-the-best-used-car-prices.html)).

A search on Carmax.com on August 9, 2017 returned 500 Kia Sorento. The majority (over 85%) are Sorento LX. A quick search on other used cars websites shows that this is common: Edmunds.com (more than 75% of the inventory of Kia Sorento is of trim LX) and Cars.com (more than 65%). On the three websites, the most common used Kia Sorento after the LX trim, are EX and SX. There are only a handful of L, SXL and Limited.
- The L and LX trims are the base models and correspond to 185 HP.
- The EX trim corresponds to 240 HP.
- The SX and SXL models correspond to 290 HP.

## Data Analysis

Plotting price vs. mileage with different colors for years clearly show that price decreases with mileage, and that for a given mileage, newer cars tend to be more expensive.

## Predictions (linear regression model)

## Conclusion
