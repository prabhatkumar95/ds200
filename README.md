# DS200-Research Methods
Repo for ds200 course


# Data
The repository is for the analysis of <b>Air Quality Index for the city of Bengaluru</b>.

The data used has been refered from the [Open Governement Data Platform India](https://data.gov.in/)

The raw data can be downloaded from [here](https://smartcities.data.gov.in/catalog/environmentbengaluru?filters%5Bfield_catalog_reference%5D=2912669&format=json&offset=0&limit=9&sort%5Bcreated%5D=desc)
The cleaned data used for analysis can be found in the repo named as <b> data.csv </b>


# Observations

* Variation in ppm levels of PM10 is highest among the compounds reported in the data, where SO2 is faily consitent thoughout the time.

* The fluctuation in the levels of counpounds other than SO2 occurs during the winter (Oct-March) period. Though this is a general phenomenon observed in the country but the geographical characteristics of Bengaluru avoids a large fluction wrt to the country.

* Upon studying the correlation between the coumpunds themselves. It is normally observed that the values are generically indepndent of each other with the exception of PM10-PM2.5, which showcases strong correlation.

# References
\[1\] [Open Government Data Platform India](https://data.gov.in/)

\[2\] [Pandas Documentation](https://pandas.pydata.org/docs/)

\[3\] [Matplotlib Documentation](https://matplotlib.org/3.3.3/contents.html)