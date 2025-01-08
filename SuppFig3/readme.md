### README SuppFig3
This directory contains the data and code for the figures and statistical tests shown in supplemental figure 3.

## There are two files in this directory:
- `SuppFig3.ipynb`, the Jupyter Python notebook used to visualize the data and perform statistical tests.
- The python notebook is further annotated with markdown explaining the purpose of the code, rationale behind statistical tests, and origin of the data/experiments.
- `SuppFig3 data.xlsx`, which is an excel spreadsheet used to organize the data. 
	- The data is organized by what figure it corresponds with.
	- The sheet titled `SuppFig 3C, D` contains the raw and calculated values for anti-yTubulin fluorescence in wild type, _yTubulin37C[3]_, _yTubulin23C[A14-9]_, and _yTubulin37C[S131A]_ mutants. 
	- The calculated values were then used for plotting in the jupyter notebook.  
- Visualization was done using the `seaborn` library. 
- statistical tests were chosen based on compatibility with the data: if the data was normally distributed, an unpaired student's t-test was used. If the data was non-parametric, a two-sided Mann-Whitney U test was used. a p value of 0.05 was used to determine significance.

 

