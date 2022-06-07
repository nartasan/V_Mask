# V_Mask is a control chart method
Code has used time series data for different ID's and CUSUM/CUMEAN are calculated for V-Mask analysis (explained https://github.com/nartasan/CUMEAN-and-CUSUM-in-pandas-python)
Deatils of the V-Mask can be found https://sixsigmastudyguide.com/cumulative-sum-chart-cusum/.
In this code the coefficients of h and k are assumed 4*STD and 0.5 based on https://support.minitab.com/en-us/minitab/18/help-and-how-to/quality-and-process-improvement/control-charts/how-to/time-weighted-charts/cusum-chart/methods-and-formulas/methods-and-formulas/
Based on step 4, we need to find the updated max and mean of CUSUM or CUMEAN over the time
Then apply the V-mask filter
