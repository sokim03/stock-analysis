# Stock-analysis
Analyzing stock data using VBA

#### Overview of Project: 
Helping Steve and his parents find the best stock option besides DQ, by analyzing yearly returns for multiple stock choices.

#### Results:
The overall stock performance in 2017 showed positive yearly returns
with the exception of TERP stock. Although the total daily volume
for DQ stock was the lowest out of all stock options, it gained the 
highest returns coming in at approximately 200%. On the other hand,
the overall stock performance in 2018 showed negative yearly returns
with the exception of ENPH and RUN stocks. DQ stock performed poorly 
in the year 2018. It may be challenging for Steve and his parents to
continue investing in DQ when the returns seem across the board. 
More data from previous and future years are needed to make a informed 
decision. 

![2017yearlyreturns](https://user-images.githubusercontent.com/96352427/149640327-b161d3f8-3ee7-44eb-ab79-c2854a66a7e8.PNG)
![2018yearlyreturns](https://user-images.githubusercontent.com/96352427/149640370-1541ac06-1b1b-46b0-8496-16f9bbb3cef1.PNG)

The difference of execution times from the original script 
and the refactored script was approximately 0.7 seconds apart.
The refactored script ran about 10-12 times faster than the 
original script. 

![AnalysisforAllStocks-2017](https://user-images.githubusercontent.com/96352427/149640387-bb489898-f8ab-4df3-be54-ccc122e80aeb.PNG)
![VBA_Challenge_2017](https://user-images.githubusercontent.com/96352427/149640412-29efb342-1c17-4393-b7c1-673345fda12b.PNG)

![AnalysisforAllStocks-2018](https://user-images.githubusercontent.com/96352427/149640399-59fad4ad-a521-4547-a714-3a87953c1ac0.PNG)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/96352427/149640422-9cc54644-5828-47cb-bd6a-976f572fb771.PNG)

The main difference in code to execute these different 
times was by looping through the data once instead of multiple
times as we did in the original code.

![refactoredcode](https://user-images.githubusercontent.com/96352427/149641237-3327ce03-6191-4fd7-9f29-ef4eade57817.PNG)

#### Summary:
The advantages of refactoring code is that it condenses 
the script to make it more readable for users, shortens time
for the future when coding large sets of data, and improves 
overall performance of the script. Some disadvantages may be 
that it could create bugs in the code when trying to refactor
complex codes or wasting time on trying to refactor. 

The refactored dataset performed better and shortened the 
time of generating our data. Although small, there was more 
advantages than disadvantages for our dataset. If this was a 
much bigger dataset, I believe the advantages would weigh
much more. 
