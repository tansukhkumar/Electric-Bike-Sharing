### Electric-Bike-Sharing

**Business Case**
Electric-Bike-Sharing is India’s leading micro-mobility service provider, which offers unique vehicles for the daily commute. Starting off as a mission to eliminate traffic congestion in India, Electric-Bike-Sharing provides the safest commute solution through a user-friendly mobile app to enable shared, solo and sustainable commuting.

Electric-Bike-Sharing zones are located at all the appropriate locations (including metro stations, bus stands, office spaces, residential areas, corporate offices, etc) to make those first and last miles smooth, affordable, and convenient!

Electric-Bike-Sharing has recently suffered considerable dips in its revenues. They have contracted a consulting company to understand the factors on which the demand for these shared electric cycles depends. Specifically, they want to understand the factors affecting the demand for these shared electric cycles in the Indian market.

**Univariate Analysis insights based on EDA**
  1. There is no missing value present in the dataset.
  2. More than 80% of time, temperature is less than 30 degree celcius.
  3. More than 80% of time, feels like temperature is greater than 30 degree celcius.
  4. Around 80% of time humidity is more than 40.
  5. 50% of time windspeed value is less than 15. Around 85% time windspeed value is less than 20.
  6. 50% of time Casual users count is around 30. and 80% of time its less than 60.
  7.0For Registerd users 80% of time count is less than 300. and 50% of time its less than 200.
  8. Season columns contains alomost smiliar values for all seasons.
  9. Weather columns have very few values for category 3 (Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds) and 4 (Heavy Rain + Ice Pallets + Thunderstorm + Mist,       Snow + Fog).


**Outliers Detection insights based on EDA**
  1. There is no outlier in the temp column.
  2. There are few outliers present in humidity column.
  3. There are many outliers present in each of the columns : windspeed, casual, registered, count.


**Bivariate Analysis insights based on EDA**
  1. The count of total rental bikes is higher in the fall season, followed by the summer and winter seasons. It is generally low in the spring season.
  2. The count of total rental bikes is higher in the clear and cloudy weather, followed by the misty weather and rainy weather. There are very few records for extreme weather conditions.


**Time Analysis insights based on EDA**
  1. We Have around 719 days of data.
  2. There is overall up going trand in rentals from 2011 to 2012
  3. January to March there is increasing.
  4. From July to September, there is a slight decrease in the count of rental bikes, with negative growth rates.
  5. the count further declines from October to December, with the largest drop observed between October and November.
  6. The average hourly count of rentals is the highest in the month of June followed by July and August.
  7. he average hourly count of rentals is the lowest in the month of January to March.
  8. The average count of rentals is the highest at 5 PM followed by 6 PM and 8 AM of the day.
  9. The average count of rentals is the lowest at 4 AM followed by 3 AM and 5 AM of the day.
  10. Low rentals in early morning than sudden hike in morning than gradual decline in afternoon and than again peck high in evening hours.

**Hypothesis testing conclusion**
  1. Since pvalue is greater than 0.05 so we can not reject the Null hypothesis. We don't have the sufficient evidence to say that working day has effect on the number of electric cycles being rented.
  2. P-value is less than 0.05 therefore, the average number of rental bikes is statistically different for different seasons and different weathers.
  3. There is statistically significant dependency of weather and season based on the number of number of bikes rented.

**Recommendations**
  1. Seasonal Marketing - Since there is a clear seasonal pattern in the count of rental bikes, Electric-Bike-Sharing can adjust its marketing strategies accordingly. Focus on promoting bike rentals during the spring         and summer months when there is higher demand. Offer seasonal discounts or special packages to attract more customers during these periods.
  2. Time-based Pricing - Take advantage of the hourly fluctuation in bike rental counts throughout the day. Consider implementing time-based pricing where rental rates are lower during off-peak hours        and higher during peak hours. This can encourage customers to rent bikes during less busy times, balancing out the demand and optimizing the resources.
  3. Weather-based Promotions - Recognize the impact of weather on bike rentals. Create weather-based promotions that target customers during clear and cloudy weather, as these conditions show the            highest rental counts. Electric-Bike-Sharing can offer weather-specific discounts to attract more customers during these favorable weather conditions.
