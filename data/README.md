##Instructions on how to obtain the data:

I obtained the data from the Los Angeles City Data website. The data sets were fairly large, and so one would need to download the data sets on their own. Here are the steps to downloading the datasets and reading
them into R:

1.  Go to both links and click ‘export’ and then, ‘CSV’ in order to download the data sets as CSV files to your computer:
    <https://data.lacity.org/Public-Safety/Crime-Data-from-2010-to-2019/63jg-8b9z>
    <https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8>
2.  Rename the data sets to: “crimedata_2020topresent.csv” and “crimedata_2010to2019.csv”
3.  Then, you can read in the data using the code a few lines below with the: data.table::fread function.
