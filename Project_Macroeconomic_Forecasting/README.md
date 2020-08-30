# Performance of shrinkage methods in macroeconomic forecasting

The project by Liudmila Kiseleva for the course [Computational Statistics](https://github.com/ljanys/CompStat/).

Based on the paper Smeekes, S., and Wijler, E. (2018). [Macroeconomic forecasting using penalized regression methods](https://www.sciencedirect.com/science/article/pii/S0169207018300074). *International Journal of Forecasting, 34*(3), 408-430.

Forecasting macroeconomic outcomes by the nonstructural methods appears to be not an easy task: macroeconomic data tends to be high-dimensional. Traditionally, shrinkage methods are considered to be a solution for performing forecasts in a high-dimensional setting with many potential predictors. I focus on ridge and lasso regressions. First, I describe their theoretical properties and explain their differences. Second, I simulate realistic macroeconomic time series to evaluate ridge and lasso performance in the sparse/abundant models; in the models with different number of predictors; in the models with cross-sectional and serial correlation. Finally, I apply ridge and lasso regressions to the [FRED Monthly Database for Macroeconomic Research](https://research.stlouisfed.org/econ/mccracken/fred-databases/) to compare their performance for few selected macroeconomic variables. I obtain predictable result: ridge and lasso tend to outperform each other when the Data Generation Process for the series differs. Therefore, I conclude that an optimal strategy for macroeconomists would be not to choose one shrinkage method to perform the forecast; but to combine few methods and compare the results.

You can access the notebook [here](https://github.com/milakis/R-codes/blob/master/Project_Macroeconomic_Forecasting/project_comp.ipynb).
