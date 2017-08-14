# Price Predictions of Second-Hand Cars (Ongoing)

I want to optimize my search for second-hand cars using data science. 

I have pre-selected a couple of models that interest me:
- Kia Sorento 
- Mazda CX-5 
- Toyota Rav4
- Subaru Forester

I will collect data from Carmax.com, Cars.com and/or Edmunds.com:
- Brand 
- Model
- Trim 
- Price 
- Year 
- Mileage 
- Color (only with Cars.com or Edmunds.com)
- Drivetrain (FWD / AWD) (only with Cars.com or Edmunds.com)

Some characteristics (e.g., color and drivetrain) are directly available on the first page of results of Cars.com and Edmunds.com but not Carmax.com. The former also have larger car inventories and APIs to collect data. However, they also tend to have more missing data.

Depending on the number of results, I will limit the search results to a certain radius around my zip code (e.g., 500 miles) because it is unlikely that I will buy a car from across the country and prices do vary. Used cars tend to be cheaper in the northeast and in Florida compared to California for example ([reference](https://www.cnbc.com/2016/08/30/where-to-get-the-best-used-car-prices.html)).

I will use the data to train a model estimating the price of a car based on its characteristics. 

Finally I will try to identify good deals using the algorithm: if the algorithm predicts a higher price than the proposed price, it might be a good deal! 
