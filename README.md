# Matplotlib-Challenge

This repository contains the code to perform necessary calculations and undertake  the necessary analysis and determine key metrics for a new pharmaceutical company that specialises in anti-cancer medications. The research looks at the treatment of 249 mice who where diagnosed with squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. the study tracks and traces how potential treatment from a wide varity of drugs for SCC impacted the tumour levels in the mice and how effective the drug combats SCC.

The following metrics are included for each drug within the study:
1) Mean
2) Median
3) Variance
4) Standard Deviation
5) Standard Error of Mean (SEM)

## Data Source
The data for this analysis comes from a dataset of 'Mouse Metadata' and 'Study Results'. The dataset includes information on each 'Mouse' as well as information on each 'Study' and the effect on the specific mouse for the relevant treatment drug applied. The data set can be found in this repository under Pymaceuticals/data

## Getting Started
To run the analysis, clone this repository and run the Pymaceuticals_AnalysisCode.ipynb notebook within the Pymaceuticals folder. The notebook contains the necessary code to read in the data, perform the calculations, and create the summary DataFrames.

## Requirements
The analysis requires the following libraries:
1) pandas
2) numpy
3) scipy.stats
4) matplotlib.pyplot

## Analysis Results 
* A summary statistics table that shows the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
* A bar plot that uses Pandas's DataFrame.plot() and Matplotlib's pyplot to display the number of data points for each treatment regimen.
* A pie plot that uses Pandas's DataFrame.plot() and Matplotlib's pyplot to show the distribution of male and female mice in the study.
* Calculation of the final tumor volume for each mouse across four of the most promising treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin), along with the quartiles, IQR, and potential outliers across all four treatment regimens.
* A box and whisker plot that shows the final tumor volume for all four treatment regimens, highlighting any potential outliers by changing their color and style.
* A line plot that shows the relationship between time point and tumor volume for a single mouse treated with Capomulin.
* A scatter plot that displays the relationship between mouse weight and average tumor volume for the Capomulin treatment regimen.
* Calculation of the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment, with the linear regression model overlaid on the scatter plot.
