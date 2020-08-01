# Matplotlib Challenge - The Power of Plots
## Background
I have been given access to the complete data from a recent animal study. In this study, 250 mice identified with tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of my study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens and provide top-level summary of the study results.

Data was provided via 2 csv files and they are saved [here.](https://github.com/kanamoore/matplotlib-challenge/tree/master/data)

## Summary
Firstly, only Ramicane and Capomulin were successful at reducing tumor volume. Ramicane and Capomulin reduced average tumor volume by roughly 11%-12%, whereas other treatments increased average tumor volume by roughly 16%-22% after 45 days of treatment.

Secondly,there was a positive correlation between mouse weight and average tumor volume for the Capomulin treatment, r= 0.84, p = < 0.001.

Lastly, Capomulin yielded the highest mouse survival rate, which was about 84%, whereas Propriva yielded only 28% based on the number of mice on day 1 versus day 45 of the treatment duration.

## Data Analysis
For the code and result, please check [Jupyter notebook.](https://github.com/kanamoore/matplotlib-challenge/blob/master/pymaceuticals_starter.ipynb)

* Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generated a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the number of data points for each treatment regimen.


* Generated a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.


* Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculated the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlighted any potential outliers in the plot by changing their color and style.


* Generated a line plot of time point versus tumor volume for a single mouse treated with Capomulin.

* Generated a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

## Reference
 [Matplotlib documentation page](https://matplotlib.org/gallery/pyplots/boxplot_demo_pyplot.html#sphx-glr-gallery-pyplots-boxplot-demo-pyplot-py) for help with changing the style of the outliers.

