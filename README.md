# stock-analysis
# Analysis Report - Module 2 Challenge

## 1.Overview of Project:
The project is to provide an overview of stock analysis for each year and yearly investment return in the percentage increase or decrease in price from the beginning of the year to the end of the year. This project provides the details of each ticker, yearly volume and Return (in percentage) to determine the stock performance in larger sets with an elevated performance execution time.

## 2.Results:

## 1)Stock Performance between 2017 and 2018 :
1. In [2017 report](https://github.com/raajasrini/stock-analysis/blob/main/Resources/VBA_Challenge_2017.png), All tickers has good return increase except “TERP” which is 7.2% decrease. Tickers DQ (199.4%), ENPH(129.5%), FSLR(101.3%) and SEDG(184.5%) are above 100% returns.

2.In [2018 report](https://github.com/raajasrini/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png), tickers ENPH (81.9% ) and RUN ( 84.0%) are good return and all other tickers are decrease in returns. 

 ## 2) Execution Time :
#1. The execution time of code in refactored script was approx 0.17 seconds for 2017 and 0.125 seconds for 2018

#2. The execution time of code in original script was approx 0.80 seconds for 2017 and .79 seconds for 2018

#3.The refactored script improved the performance compared to the original script. The code was factored to have specifics needed to generalize and one time loop with arrays to hold each ticker results elevated performance compared to original script.

## Summary:
## 1)Pros and Cons of Refactoring code :
  
 * **Pros of refactoring code :** # 1.Analyze non function requirements to built efficient Code by simple steps, using less memory, or improving the logic of the code to make it easier for future users to read.
 * **Cons of refactoring code:**
#1. Deeply Analyze non functional requirements to meet the future needs.
#2. Manually clear all the unused memories.

## 2) Pros and cons apply to refactoring the original VBA script:
#1.	Reduced for- loops. Loop through all the data one time in order to collect the same information.
#2.	Improving the logic to generalize and introduce design patterns.
#3.	Simple needed steps of the code to make it easier for future users to read. 
#4.	Eliminated unwanted memory and reduced the code size to increase performance.
