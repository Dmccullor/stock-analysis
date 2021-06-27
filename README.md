# Green Stocks Analysis
## An analysis of sustainable energy stock performance for 2017 and 2018
### The purpose of this analysis
The  main focus of this analysis was to determine the performance of stocks of several companies in the sustainable energy sector. The analysis was done for the years 2017 and 2018 with the same 12 companies. The subroutines that have been written can also be used for other years with the same dataset format. The performance is displayed as a positive or negative percentage corresponding to a net gain or loss for the year and the magnitude of that change. Results are presented with the total daily volume for each stock.

### Results
Overall, 2017 was a much better year for green energy than 2018. Almost all of the companies observed saw growth except for one. In many cases the growth was quite substatial. 2018 was nearly the opposite. Most of the same companies in 2018 had a loss except for two.

The analysis can be ran in two different ways. The first method used nested loops to obtain stock data for each of the companies. This analysis worked fine, coming in at .492 seconds and .82 seconds for 2017 and 2018 respectively. However, the second method used output arrays to decrease the number of operations and came in much faster as shown in the images below.
![Image of 2017 Stock Analysis Runtime](https://github.com/Dmccullor/stock-analysis/blob/44c65928cdf39a30cb961b4d21f3fc981465d10d/Resources/VBA_Challenge_2017.png)
![Image of 2018 Stock Analysis Runtime](https://github.com/Dmccullor/stock-analysis/blob/44c65928cdf39a30cb961b4d21f3fc981465d10d/Resources/VBA_Challenge_2018.png)
