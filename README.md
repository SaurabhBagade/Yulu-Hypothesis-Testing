**Insights and Conclusions**

1.  There seems to be no NULL/NA values in the dataset.
    
2.  The number of ridership has been increasing year on year.
    
3.  Majority of the temperature ranges from 8 - 30 degree Celsius
    
4.  Humidity ranges from 20 - 100
    
5.  Majority of the days the ridership has been 0. For both the casual as well as registered users.
    
6.  The majority of data includes clear weather days.
    
7.  The data for different seasons is equally distributed.
    
8.  The outlier percentage for ridership in different seasons as well as different weather conditions remains below 5 % of total data
    
9.  Also for holiday and working days the ridership has very low outliers.
    
10.  The correlation heatmap shows a 0.98 correlation between the "temp" and "atemp" column. So we remove the "atemp" column.
    
11.  The count has the sum of registered + casual users so we keep all the columns.
    
12.  The count of casual users on non-working days is significantly higher than on working days.
    
13.  The count of registered users on working days is significantly higher than on non-working days.
    
14.  In different weather conditions the days with 0 ridership are higher.
    
15.  The data for count is not normally distributed. ( Concluded by QQ-Plot, Skewness, Kurtosis, Shapiro wilks test, Levine's test. Therefore we cannot use the ANOVA, so we use the KS-Test.
    
16.  This gives us a result that there is a significant difference between ridership count of different weather conditions. Where clear weather has the highest ridership and light rain has the lowest ridership.
    
17.  In different seasons the days with 0 ridership are higher.
    
18.  The data for different seasons' ridership count is not normally distributed. ( Concluded by QQ-Plot, Skewness, Kurtosis, Shapiro wilks test, Levine's test). Therefore we cannot use the ANOVA, so we use the KS-Test.
    
19.  This gives us a result that there is a significant difference between ridership count of different seasons. Where the fall season has the highest ridership and spring has the lowest ridership.
    
20.  The weather conditions and seasons are significantly associated.
    
21.  There is a positive correlation between temperature and count of riders.
    
22.  There is a negative correlation among the count of riders and humidity.
    

**Recommendations**

1.  The company should analyze why there are many days with 0 riders.
    
2.  There is a trend where the casual ridership increases on weekends and registered ridership increases on working days. The company should focus on how they can target the casual riders on weekends to make them registered riders. 
    
3.  The company can hook up registered riders by providing them with weekly/monthly passes at discounted prices. This will ensure that the days with 0 ridership are lower.
    
4.  The company can also provide coupons for casual users on weekends for increasing sales.
    
5.  In total there are many days with 0 ridership as well as large ridership. The Company should analyze the data when ridership spikes suddenly and do the same for less ridership days.
    
6.  As the temperature increases so does the ridership, the company can predict weather conditions and market their product according to the temperature predictions.
    
7.  The ridership remains steady for a certain humidity level than reduces. The company can target such geographical locations where the humidity is OK and the average temperature is around 30 degree Celsius. This will help boost the business sales.
    
8.  For clear weather conditions the ridership is highest while for the light rain weather the ridership is lowest. The Company can predict weather conditions for marketing products.
    
9.  Same goes for seasons where the people prefer bicycles in the Fall season and do not prefer in the spring season.
    
10.  As the weather and season are related the company can target to provide discounts and market its product well in the season of fall and clear sunny days.
    
11.  Overall Clear sunny days with average temperature above 25 degree Celsius in the season of Fall are the best days for the company to make revenue