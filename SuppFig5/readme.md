### README SuppFig5
This directory contains the data and code for the figures and statistical tests shown in supplemental figure 2.

## There are two files in this directory:
- `SuppFig5.ipynb`, the Jupyter Python notebook used to visualize the data and perform statistical tests.
- The python notebook is further annotated with markdown explaining the purpose of the code, rationale behind statistical tests, and origin of the data/experiments.
- `SuppFig5 data.xlsx`, which is an excel spreadsheet used to organize the data. 
	- The data is organized by what figure it corresponds with.
- Visualization was done using the `seaborn` library. 
	- statistical tests were chosen based on compatibility with the data: if the data was normally distributed, an unpaired student's t-test was used. If the data was non-parametric, a two-sided Mann-Whitney U test was used. Frequency differences were calculated using the chi-squared goodness of fit statistical test. a p value of 0.05 was used to determine significance.  
- The last sheet is titled `STATS` and contains the stats tables generated by the python notebooks.
 

