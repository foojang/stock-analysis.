# stock-analysis.
Module 2 stock-analysis.

Project overview and purpose
The purpose of this project is to help Steve and his parents make informed decision on Green stocks they would like to invest in. Steve’s parents have decided they would like to be in better control of their investing and focus of environmentally friendly stocks. Steve asked us to put together a spreadsheet to examine the performance of 12 stocks performance for 2017 and 2018. The initial code runs effectively for the twelve stocks but we would like to have a quicker macro in place if Steve or his parents would like to examine more stocks or a longer period. We will refactor the code to have it run more efficiently. 
Results 
Below is the refactored code and the original code for the Stock Analysis. To help the macro run more efficiently we can reduce the number of times the macro needs to loop through the sheet to output the results. In the refactored code I added output arrays that will store data and now the loop will not have to run as many times to output he info. 
Refactored Code
 ![image](https://user-images.githubusercontent.com/95973377/147857527-4ba08334-91b1-4be2-8e6b-94317da71902.png)
Original Code
 ![image](https://user-images.githubusercontent.com/95973377/147857548-b6348e07-ef06-4af9-8bcf-f094f19a6d98.png)
The below analysis shows that 2017 was a bull market and all stocks but one was up. In 2018 the market was much more bearish and all, but two stocks were down. Only one stock RUN saw better performance then they did in 2017. 
 
 




Performance has been improved. In the original code each year took almost a second to run 
 
 
In the refactored code each year took around an eighth of a second to run 
 
 
Summary 
The advantages of refactoring code is you can receive results much faster and efficiently. For the current data refactoring does not make much of a difference but if we continue this analysis and add more years or if we expand beyond the twelve stocks our run times could balloon and make the macro useless. A disadvantage of refactoring code is we could take a working macro and break it. We may not be able to have it run more efficiently, and we could lose the original functionality. It is always best practice to backup data and save original code that you can put back in place. 

