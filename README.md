# surfs_up
  Challenge 9

## Project Overview
I would like to open a Surf & Ice Cream shop on a beach in Oahu; however, the weather can play a big role in the success of the business. W. Avy, a potential investor, is interested in the temperature data for the months of June and December. We had previously analyzed precipitation levels across a yearlong period and W. Avy was impressed with the results. Now, we want to impress him again with descriptive statistics on temperature data to show that the business is sustainable year-round. Results and conclusions are outlined below.

## Resources
            Data Sources: climate_analysis.ipynb, hawaii.sqlite
            
            Software: Python 3.9.7, SQLite, & Jupyter Notebook
## Results
First, our June Analysis. As you can see below, we analyzed 1,700 data points to find the average, max and, min temperatures for the month. The temperature averaged just under 75 degrees and only saw a max of 85 degrees. 

![june_temp_stats](https://user-images.githubusercontent.com/96352625/156905717-07a7987d-83ba-4a59-8313-605f32af66a1.png)

Second, the December analysis. In the table below, it shows we had 1,517 data points to analyze, and the average temperature fell only a few degrees to 71. The max temperature was 85 degrees and the minimum was 56 degrees. 

![dec_temp_stats](https://user-images.githubusercontent.com/96352625/156905722-6db67cfb-fe53-4e35-981a-9a19275c5b64.png)

Based on these results, we can conclude three major points:
* As expected, June was warmer than December. However, the average temperature difference between the two months was less than 4 degrees; a very consistent temperature in the low 70s - perfect for ice cream eating.
* The max temperature for June and December is 85 and 83 degrees, respectively. Although one might think heat may bring in more customers, if it's too hot people may stay away from the hot sands of the beach. Therefore, max temperatures around the low 80s are consistent and sound like perfect ice cream eating temperatures. 
* June and December both show similar temperature trends. One month that starts the summer and other in the middle of winter; they both represent high months for the rest of the year. Additionally, both months are important tourist, beach, and surf seasons that the shop will want to be in business to serve. The consistency across months, will help provide for more consistent customers. 
 
## Summary
It is important to note that temperature data includes minimum temperatures which likely fall at night when the store is closed and no one is surfing. Therefore, the average temperature is impacted by times that the business may not be as interested in. However, we still find that the consistent temperatures between the two months are impactful findings for W. Avy and his board as they make their final decision. Average temperatures in the low to mid 70s and max temperatures in the low 80s are ideal for the shop.

Although this analysis did not go beyond the temperatures for June and July, there are other weather patterns that may affect the business. First, wind trends would be helpful. Querying for wind speeds throughout the months because high winds will impact the surf environment and the number of surfers on the ocean. Second, querying for rain fall/precipitation would be helpful as it's an important weather element to understand. Not many people eat ice cream in the rain, so minimal rain fall would be ideal. However, even with the temperature analysis completed, the analysis supports the Surf & Ice Cream shop being succesful year-round.
