# Stock-analysis Project

# Overview of Project: 

The purpose of this project is to analyze the performance of 12 different stocks of over a two year period. We analyzed these stocks for the years of 2017 and 2018. To acomplish this we captured the ticker name, opening and close price each day, the volume each day, and a few other data points not used in our analysis. Our task was to loop through the data analyzing the opening and closing prices to compare in our calculations to see each ticker's annual return. We also summed all the volume for each trading day of the year to determine the daily volume. Once the data was captured, we then needed to display that information in our table to see which stock performed the best over either 2017 or 2018. 

After accomplishing our task we noticed running the calculations was taking longer than expected. We reviewed the code for opportunities to improve the performance. We determined that incorporating arrays we are able to loop through the information one time and vastly improve the performance. 


## Results:

The Results of our study shows an astonishing difference in performance from year to year. 

![Screen%20Shot%202020-10-03%20at%202.17.50%20PM.png](https://github.com/austink24/stock-analysis/blob/master/Screen%20Shot%202020-10-03%20at%202.17.50%20PM.png)
![2018 returns](https://github.com/austink24/stock-analysis/blob/master/Screen%20Shot%202020-10-03%20at%202.18.26%20PM.png)


The results of refactoring our first attempt of the code used to acomplish the task was that by utilizing output arrays we are able to save time looping through  our data and store the information in the array for use later in our code. The using output arrays cut the time it takes to analyze the data from over 1 second to now under .20 of a second. 


![2017 timer](https://github.com/austink24/stock-analysis/blob/master/VBA_Challenge_2017..png)
![2018 timer](https://github.com/austink24/stock-analysis/blob/master/VBA_Challenge_2018.png)


### Conclusions:
