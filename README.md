# Price Predictions of Second-Hand Cars (Ongoing)

I want to optimize my search for second-hand cars using data science. 

I have pre-selected a couple of models that interest me:
- Kia Sorento, 
- Mazda CX-5, and 
- Toyota Rav4. 

I will collect data from carmax.com or cars.com:
- Brand, 
- Model,
- Price, 
- Year, 
- Mileage, 
- Color, 
- Transmission (Automatic or Manual), 
- Trim, 
- HP (based on the year and trim).

Some characteristics (e.g., color and transmission) are directly available on the first page of results of cars.com but not carmax.com.

I will limit the search results to a certain radius around my zip code (e.g., 100 miles) because it is unlikely I will buy a car from across the country and prices do vary. Used cars tend to be cheaper in the northeast and in Florida compared to California for example ([reference](https://www.cnbc.com/2016/08/30/where-to-get-the-best-used-car-prices.html))

I will use the data to train an algorithm estimating the price of a car based on its characteristics. 

Finally I will try to identify good deals using the algorithm: if the algorithm predicts a higher price than the proposed price, it might be a good deal! 
