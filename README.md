# matplotlib-challenge
Matplotlib Homework - The Power of Plots


Three observations or insights about the data:
1) For the four sampled drugs, only one datapoint (for Infubinol) is an outlier.  

2) Using the drug Capomulin as an example, there may not be enough timepoints to determine the long-term effectiveness of the drug.  Randomly sampling some mice:  There appears to be an overall downward trend in the tumor volume over time.  Some mice, such as j119, for example, seems to have its tumor volume continuing on a downward trend at day 45 while some mice, such as l509, start to slightly increasing.

3) There is a strong correlation (0.84) between mouse weight and Average Tumor Volume for the Capomulin regimen (which is >0.7).

NOTE: When determining outliers using upper and lower bounds, the example provided to us shows that the Drug Regimen Infubinol's potential outliers are 31 & 36.321346. My data only produced one outlier: 36.3213458. I checked the raw data and there was no value of 31 for any of the timepoints. The value I found is the least for this drug regimen (Mouse ID c326, timepoint 5).