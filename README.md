# Stock Analysis
## Overview of Project 
In this project, we are using VBA to analyze and compare the performance of selected stocks in years 2017 and 2018. In addition, we are using editing or refactoring our code to avoid implementing multiple loops and to improve the code’s performance. The refactoring in this case, facilitates the code to perform the same task in one tenth of the original time. This implies that the refracted code can be easily used for larger data sets.
## Results
Comparing the performance of the selected set of stocks between years 2017 and 2019 indicate that in 2017, only 1 stock (TERP) had a negative return (-7.2 %). The rest had positive returns with most of them above 50 % but in 2018 only 2 stocks had positive return and the rest decreased significantly
(See figures below)

![2017 stocks](/Resources/stocks2017.png?raw=true "2017 stocks")
![2018 stocks](/Resources/stocks2018.png?raw=true "2018 stocks")

The refactoring of the code led to a significant decrease in the performance time. The original code needed about 0.8 second to perform the task (See figures below)

![VBA performance 2017](/Resources/VBA_2017.png?raw=true "VBA performance 2017")
![VBA performance 2018](/Resources/VBA_2018.png?raw=true "VBA performance 2018")

After refactoring, the same job was done in about 0.08 second! (See figure below)

![VBA refactored performance 2017](/Resources/VBA_Challenge_2017.png?raw=true "VBA refactored performance 2018")
![VBA refactored performance 2018](/Resources/VBA_Challenge_2018.png?raw=true "VBA refactored performance 2018")

## Summary
-Advantage and disadvantage of refactoring: Avoiding multiple loops would reduce the time needed to run the analysis and make the code easier to be utilized for larger data sets. However, it is not easy to refactor complex code (especially if we are not writing the code from scratch) and it also may decrease its readability. 

-Advantage and disadvantage of refactoring for this sample: The refactoring of the code improved its performance 10 times. However, it was a bit more difficult to debug it.
