# Stock-analysis Project

# Overview of Project: 

The purpose of this project is to analyze the performance of 12 different stocks over a two year period. We analyzed these stocks for the years of 2017 and 2018. To acomplish this we captured the ticker name, opening and close price each day, the volume each day, and a few other data points that were not used in our analysis. Our task was to loop through the data analyzing the opening and closing prices to calculate annual returs for each ticker. We also summed the daily volume for each trading day of the year to determine the daily volume. Once the data was captured, we then needed to display that information in our table to see which stock performed the best over either 2017 or 2018. 

After accomplishing our task we noticed running the calculations took longer than necessary. We reviewed the code for opportunities to improve the performance. In our review we noticed the code was looping through the data numerous more times than necessary. By incorporating arrays we are able to loop through the information only one time to collect the data and greatly reduce the time spent looping over it multiple times to get all the data. 


## Results:

The Results of our study shows an astonishing difference in performance from year to year. 

![Screen%20Shot%202020-10-03%20at%202.17.50%20PM.png](https://github.com/austink24/stock-analysis/blob/master/Screen%20Shot%202020-10-03%20at%202.17.50%20PM.png)
![2018 returns](https://github.com/austink24/stock-analysis/blob/master/Screen%20Shot%202020-10-03%20at%202.18.26%20PM.png)


### The results of refactoring:
Our first attempt of the code used to acomplish the task was that by utilizing output arrays we are able to save time looping through  our data and store the information in the array for use later in our code. The using output arrays cut the time it takes to analyze the data from over 1 second to now under .20 of a second. 


![2017 timer](https://github.com/austink24/stock-analysis/blob/master/Resources/VBA_Challenge_2017..png)
![2018 timer](https://github.com/austink24/stock-analysis/blob/master/Resources/VBA_Challenge_2018%20copy.png)

![code1](https://github.com/austink24/stock-analysis/blob/master/Resources/code1.png)

![Code2](https://github.com/austink24/stock-analysis/blob/master/Resources/code2.png)

### Conclusions:

#### An advantage of refactoring:
The amount of improvement on the performance and readability of your code. While at first refactoring can be seen as a disadvanage due to time spent cleeaning up code that already does what it is intended to do, but the time saved when running or reusing the code becomes a huge advantage and time spent refactor is recovered multiple times over when your code performs better and is much easier to read and even modify in the future. 

#### Refactoring our VBA
The disadvantage was the amount of time spent refactoring, in my case not being familiar with the use of arrays for output really slowed down the process. After it was refactored it made everything worth it! THe advantage of refactoring was cutting down the processing time 500%! 

Our analysis of the 12 stocks over the 2017 and 12018 year clearly show only two companies were able to provide a positive return in both years. With ENPH being the best choice for investment as our study shows they were able to produce 200% profit over the two years doubling any investment in those two years.  
