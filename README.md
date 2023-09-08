peakfit
=======

Python script to fit arbitrary line shapes to data. It uses Plotly for creating figures and outputs html interactive plots.

# Previous Repos/Codes uses

Most of the plot shapes and packages taken from https://plotly.com/python/v3/peak-fitting/
Mixed with the fitting procedure from this repo https://github.com/emilyripka/BlogRepo/blob/master/181119_PeakFitting.ipynb

The code uses jupyter notebooks that you must run under appropriate environment that includes the packages requested in the first cell. These are 

1. For plotting
  * chart_studio.plotly
  * plotly.graph_objects
  * plotly.figure_factory
  * plotly.io

2. For Fitting and data processing
  * numpy # Tools for working with floating point numbers among other things
  * pandas # Tools for reading and processing data
  * scipy
  * peakutils # Tools for peak finding and fitting
  * scipy import signal

# Contents

The code uses jupyter notebooks, so just run each cell to see the results. There is sample data to show how the code works.
There are two notebooks. One for single peak fit, and other for multiple peak fitting, to show how the code must be changed in case a different
function is neccesary. The peakfit package uses a Levenberg-Markquardt Least squares iteration to fit the given functions to the data.

# The plotting

The code uses plotly, that is now inside the chart studio package. 
Plotly allows creation of interactive plots in the notebook or in an html file.
The html file can be opened in any browser, after it is created.
For more info: https://plotly.github.io/
_You need to update the html file after each modification._
