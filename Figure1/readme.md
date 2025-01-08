### README FIG1
This directory contains the data and code for the figures and statistical tests shown in figure 1.

## There are two files in this directory:
- `FIG1.ipynb`, the Jupyter Python notebook used to visualize the data and perform statistical tests.
- The python notebook is further annotated with markdown explaining the purpose of the code, rationale behind statistical tests, and origin of the data/experiments.
- `Fig1 data.xlsx`, which is an excel spreadsheet used to organize the data. 
	- The data is organized by what figure it corresponds with. 
	- The raw data is stored in the tab titled `raw data Fig 1C, 1D, 1F, 1H`.
		- Calculations were also done in this spreadsheet. 
		- Interphase was defined as at least 30 minutes prior to nuclear envelope breakdown, and prometaphase was defined as the timepoint where both the apical and basal centrosome had fully matured. 
		- There are columns that store the interphase and prometaphase data separately, both the raw data and the data after background subtraction. 
			- Background was determined based on the intensity of empty pixels in the image. These values were subtracted out from centrosomal and cytoplasmic signal. 
		- After subtraction, the ratio of either apical centrosome/cytoplasm, basal centrosome/cytoplasm, or apical centrosome/basal centrosome was determined using background-subtracted values. 
	- After calculation, the data was organized for visualization in the tab titled `organized data Fig 1C, D, F, H`. 
		- Visualization was done using the `seaborn` library. 
		- statistical tests were chosen based on compatibility with the data: if the data was normally distributed, an unpaired student's t-test was used. If the data was non-parametric, a two-sided Mann-Whitney U test was used. a p value of 0.05 was used to determine significance. 
	- The tab titled `CS angle Fig 1I, 1J, 1K` contains the raw and calculated data for the angle measurements in Figure 1I-K. 
		- The angle of displacement was generated using the imaris measurement spot tool to place a point on the centrosome's location in interphase (point A), the center of the cell (point B), and the location of the centrosome at metaphase (point C), which yields the angle of the line ABC. 
- The last sheet is titled `STATS` and contains the stats tables generated by the python notebooks.
 
