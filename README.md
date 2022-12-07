This is my PM566 final project website home. The website is online at
https://kailaan00.github.io/pm566-final/

**Title:** "Change in Types of Crime Before and During the COVID-19 Pandemic"
**Description:** 
The COVID-19 pandemic had changed the world as we knew it like no other occurrence before. It changed people’s lifestyles, their habits, and overall created a “new normal”. People’s mindsets and priorities have changed so drastically, that it would be interesting to note whether or not it brought a change to criminal behavior and activity. For this project, I chose to focus on Los Angeles City Data, specifically, ‘Crime Data in LA from 2020 to present’ and ‘Crime Data in LA from 2010 to 2019’. These particular data sets document incidents of crime, transcribed from crime reports. This data has been provided by the Los Angeles Police Department. Based on these data sets, the question I would like to address is:

How has the prevalence of certain types of crimes in Los Angeles changed since the start of the COVID-19 pandemic?

This final project for PM 566 will examine how the prevalence of certain crimes have changed in LA county as a result of the pandemic and will do so through designing a number of interactive figures that will make it easier to visualize crime instances and characteristics of certain crimes that have taken place.  It will also make it possible to detect and analyze certain patterns and contingencies that may be apparent.

**Data:**
My data sources can be accessed here through the following links.  The data
sets were fairly large, and so one would need to download the data sets
on their own.

Here are the steps to downloading the data sets and reading
them into R:

1.  Go to both links and click ‘export’ and then, ‘CSV’ in order to
    download the data sets as CSV files to your computer:
    <https://data.lacity.org/Public-Safety/Crime-Data-from-2010-to-2019/63jg-8b9z>
    <https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8>
2.  Rename the data sets to: “crimedata_2020topresent.csv” and
    “crimedata_2010to2019.csv”
3.  Then, you can read in the data using the code a few lines below with
    the data.table::fread function.


