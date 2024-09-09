Project 2 Get the country-specific covid case data from here. (Note pandas allows you to load a csv file from a URL. Make sure to use the "raw" link to the file on github.)

Pick four countries. Show the time series plot of new cases per day for the four countries from the day of the first nonzero case day. (Note we do not want to show cumulative cases by day.)
Plot a smoothed version of the country specific data using a smoother such as a moving average, lowess or spline.
Let e be the difference between your observed case counts and the smoothed version. Plot e over time. (e is called the "residual").
From the same website, download the daily death data. Calculate the overall case fatality rate = total deaths / total cases.
For your four countries, plot the estimate of the case fatality rate up to that day in the outbreak, starting from the day of the first case. That is, for day d plot the number of deaths divided by the number of cases occuring up to day d.
Create your report in an ipython document and check the document into the github classroom repository for project 2. Make sure to actually run the document so that the figures and results are present.
