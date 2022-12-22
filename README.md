# Time-Series-U.S.-Retail-Sales-of-Cars
U.S. Retail Sales of Cars, in millions of dollars, from 1993 to Jul.2022

   - Retail-Sales-of-Cars.Rmd: Original code of our report  
   - Retail-Sales-of-Cars.html: Final report    
   - NewCarSales.txt: Raw data  

## Introduction

In this study, we analysis the data of U.S. retail sales of cars from 1993 to Jul.2022. 

1. Log-transformation and first-order differencing are used to eliminate the trend and seasonal structure.
2. Three multiplicative decomposition models are constructed.

    - Model 1: Multiplicative Decomposition Model to Sales (1993-2017)
    - Model 2: Multiplicative Decomposition Model (With Lag Residuals)
    - Model 3: Multiplicative Decomposition Model to Log Return Sales

3. Forecast data of sales from 2018 to 2022 by Model 1 is compared to the real data.
4. Partial F-test is used to determine the necesserity of variables.
5. Residual diagnostics are performed to compare the goodness of three models.
6. Seasonal static index are calculated, tabulated, and interpreted.
7. Model 1 and model 3's prediction ability of static seasonal index are compared.
8. Sales data from Mar.2020 to Jul.2022 during COVID-19 period are discussed.

## Data

The data gives monthly U.S. retail sales of cars, in millions of dollars, for the time period 1993 through Jul.2022. 

For the span of the data there were three time periods judged to be contractions by the Business Cycle Dating Committee. They are Apr.2001 to Nov.2001, Jan.2008 to Jun.2009, and Mar.2020 to Apr.2020. The first was caused by a drop in manufacturing, and perhaps was also a consequence of the 2000 dot com bubble. The second was the recession caused by a financial crisis which involved, among other problems, inflated real estate prices.The third, only two months in length, occurred at the onset of the COVID pandemic.

## Remarks

1. The multiplicative decomposition model is suitable for the data.
2. The prediction of model 1 is not accurate, and the predicted data is higher than the actual data.
3. The month of highest car sales is August and the month of lowest car sales is January. There is a stable high level of car retails from March to August following by an obvious decrease in September and a recovery in February of the next year.
4. Although model 1 is not adequately to estimate the trend structure in the following 24 months, it still has the ability to estimate the static seasonal structure.
5. During Covid-19, there was a significant drop in car sales. Unlike the impact of the Great Recession in 2008, the magnitude of the impact of Covid-19 on U.S. car sales was more dramatic, more abrupt, and shorter in duration. Another difference is that the Great Recession directly affected the overall car sales market trend and took a long time to recover.
