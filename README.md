## Assignment-06

This is our sixth assignment for BIOL390 in the summer of 2020. The purpose of this project is to give you some practice manipulating and graphing COVID-19 data for analysis. Like before, you should fork my repo and clone it to your local machine. Follow the instructions to complete the assignment while committing periodically and pushing up to your GitHub remote. When you are done, do a final knit and submit the HTML file to complete this assignment. Then file a pull request so that I can admire your work on GitHub. This assignment requires the dplyr and ggplot2 skills that you should have been picking up by now from working in DataCamp. 

## Data URL
You will be using COVID-19 data from Our World in Data for this project. This dataset ought to be very useful for your reports! You can access it from here: [https://ourworldindata.org/covid-deaths](https://ourworldindata.org/covid-deaths)

## Instructions

* Create folders for raw_data and output

* Write a chunk that loads the needed tidyverse libraries but does not show up in any way in the final HTML document.

* Write a chunk that uses wget to download the complete csv data file from the Our World in Data and save is as raw_data/owid-covid-data.csv.  This chunk should also not show up in any way in the final HTML and should be cached so that you do not repeatedly download the file as you re-execute your code.

* Write a chunk that creates a tidy dataset called output/june_deaths_by_country.csv. This file should have variables named Country, Diabetes_Prevalence, Over_70, and Total_Deaths as of June 30th. This chunk should not display anything in the final HTML document.

* Write another chunk that creates a tidy dataset called output/european_deaths_by_date.csv. This file should have variables named Country, Date, and Total_Deaths. Once again, this should not show up in the final HTML.

* Write a chunk that uses ggplot2 to create a scatter plot that compares the total deaths between all countries by diabetes prevalence.  Please use the ggplot2 linedraw theme for your plot and provide meaningful axis titles. What is your interpretation of this plot?

* Write a chunk that uses ggplot2 to create a scatter plot that compares the total deaths between all countries by the percentage of people over 70 years of age.  Please use the ggplot2 linedraw theme for your plot and provide meaningful axis titles. What is your interpretation of this plot?
Write one last chuck that produces a line graph of the total number of deaths for each European country by date. Provide meaningful axis labels and color the lines by country name. Which country was the first to exceed 1,000 deaths? What date did that occur on?

Take some time and look over the variables in this dataset. This is one possible source of raw data for your project. I will show you another next time.
