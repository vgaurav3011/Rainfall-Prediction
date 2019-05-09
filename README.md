# Rainfall Patterns Analysis of India
## Component of Automatic Irrigation System using Machine Learning
## Winning Project for Futureskills Hackathon by NASSCOM, 2018

The dataset used for the prediction of rainfall and to study seasonal variations of rainfall is having a year range from 1901 to 2015 with month wise distribution of precipitation in mm for all major Indian states and Union Territories.  It has the following columns filled with precipitation data (mm) for all the months, annual and seasonal amounts of rainfall:
1. Subdivision : String which represents the unique identity of state or union territory
2. YEAR 
3. JAN 
4. FEB 
5.  MAR
6. APR 
7. MAY 
8. JUN 
9. JUL
10. AUG 
11. SEP 
12. OCT 
13. NOV  
14. DEC 
15. ANNUAL 
16. Jan-Feb 
17. Mar-May 
18. Jun-Sep 
19. Oct-Dec


## Data Exploration
The Indian Monsoons are generally having a variation for onset in all of the states within the months ranging from June to September starting from Kerala in June and going all up to the New Delhi by July. The variations observed in the patterns of rainfall are visible within the months of June to September at peak and can be represented as a histogram as follows:
![alt text](https://github.com/vgaurav3011/Rainfall-Prediction/blob/master/histogram.png?raw=true)

The annual variation of rainfall observed in India notes two important observations:
1. It reiterates the fact that the peak rainfall occurs from June to September
2. It also gives an interesting fact that if the months of October, November and December have high rainfall then we get a healthier year of rains which can be used to study the crop yield of specific areas on a higher level.
![alt text](https://github.com/vgaurav3011/Rainfall-Prediction/blob/master/annual_rainfall.png?raw=true)
The seasonal variations of Rainfall is also studied especially in the onset months of June to September since they can contribute maximum variation to irrigation and ensure a good crop yield.
![alt text](https://github.com/vgaurav3011/Rainfall-Prediction/blob/master/seasonal_variation.png?raw=true)
For an automatic irrigation system, it is therefore easily identified that we need to take account the variation from June to September the most.
![alt text](https://github.com/vgaurav3011/Rainfall-Prediction/blob/master/seasonal_variation2.png?raw=true)
![alt text](https://github.com/vgaurav3011/Rainfall-Prediction/blob/master/seasonal_variation3.png?raw=true)
![alt text](https://github.com/vgaurav3011/Rainfall-Prediction/blob/master/variation.png?raw=true)

## Regression Models

The following models were found to be suitable for studying rainfall patterns as per many reference papers:
1. Linear Regression (Only for Analysis Purpose)
2. Lasso Regression
3. Elastic Net Regression
4. Random Forest Regression
5. SGD Regression (Only for Analysis Purpose)
6. Ridge Regression
7. Support Vector Regression
Out of all these, the Random Forest Regression has the minimal mean absolute error and is found to accommodate all seasonal variations and patterns of Rainfall in India compared to all other alternative counterparts.
