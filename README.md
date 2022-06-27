# surfs_up

### Overview of the statistical analysis:

The purpose of this analysis was to look at the weather patterns of a specific location on Oahu where we would like to build a surf and ice cream shop, because both surfing and ice cream demand are largely dependent on weather.  Specifically, we are looking at temperature data for the months of June and December in Oahu in order to determine if the surf and ice cream shop business is sustainable year-round. We are able to do this by connecting to SQLite, SQLAlchemy, and Flask to process the data and display the results. 


### There is a bulleted list that addresses the three key differences in weather between June and December.

- The average temperature in December is only about four degrees cooler than the average temperature in June. 
- The minimum temperatures between December and June reflect the biggest difference between the two data sets of eight degrees.
- The max temperatures between December and June are just two degrees different - the max temp in December of 83 degrees is greather than 75% of all temperatures in June. This shows that the higher temperatures of December reflect the majority of June.

June

![alt text](https://github.com/lauren1478/surfs_up/blob/main/june%20weather.png)


December

![alt text](https://github.com/lauren1478/surfs_up/blob/main/december%20weather.png)

Summary:

### There is a high-level summary of the results and there are two additional queries to perform to gather more weather data for June and December.
The difference in temperatures between June and December are minimal to the point that the weather is so similar. After factoring in the standard devidation, one could experience days with the same temperatures in each month because the average temperature is only a four degree difference and the standard deviation is a 3.5 to 3.7 degree difference. Through this data, it does not seem likely that the temperature will have a great effect on the demand for surfing and eating ice cream. 

However, surfing is very dependent on not only temperature, but also wind and rain. We should run analysis on wind gusts and patterns, and also the historical chances of rain during each day of both months. Hawaii does encounter hurricanes so this data analysis could take into account hurricane season. All this data is important to research because surfing and eating ice cream are in demand when the weather is warm and dry.
