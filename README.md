# Green Stocks VBA Analysis

##Overview of Project
Steve requested a way to analyze multiple stocks and their returns over several years. Originally, his parents wanted to invest in DAQO stock only. Steve requested an additional 11 stocks to analyze in order to determine which was the best stock to invest in. 
Client also requested that after the initial 12 stocks were analzyed, that he would also be able to use the same worksheet to analyze the entire stock market, if needed. This requred a refactoring of the original code in order to accomodate analysis of the entire stock market.

## Results

### Findings

Based on the Total Daily Volume and Return rate of the 12 stocks analyzed, ENPH has the greatest return year over year when looking at 2017 and 2018. RUN also had year over year growth. These are the only two stoks that should positive trends. 
DQ stock, which was the original investment goal, had the largest 2017 return rate. However, that same stock had the largest loss in 2018, compared to the other stocks. 

![This is an image](https://github.com/cwilkis/Module-Challenge-2/blob/main/Resources/2017%20data.png) ![This is an image](https://github.com/cwilkis/Module-Challenge-2/blob/main/Resources/2018%20data.png)

### Recommendations

Data shows that ENPH stock is the safest investment due to continuing growth year over year. If client wanted to diversify and invest in multiple stocks, RUN also showed year over year growth. 

## Summary

There are many advantages to refactoring code. First, refactoring code allows the program to run faster. Second, it makes code cleaner. There is less need for multiple sub routines if code is refactored. 

The main disadvantage of refactoring code is time. Depending on the length of the code, refactoring can be tedious and involve retesting many of the functionalities of the code. Depending on the time constraints and budget of the project, refactoring may not be feasible.

The advantages far outweighed the disadvantages in this stock analysis. The screen shots below show 2017 with and without refactoring. The program ran almost 5x faster once refactored. 

![This is an image](https://github.com/cwilkis/Module-Challenge-2/blob/main/Resources/2017%20not%20refactored%20timing.png) ![This is an image](https://github.com/cwilkis/Module-Challenge-2/blob/main/Resources/2017%20refactored%20timing.png)

However, the time took to refactor and test the code on this excel sheet was not light. While the code was not long, there were several places that code had to be re-written in order to make the program run faster. While many projects will have to weigh time vs efficiency, the results of refactoring are hard to ignore. Refactoring, overall, is more efficient in the long run. 
