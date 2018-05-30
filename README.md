Land Unavailability Data
===========

Land Unavailability Data used in ["Highly Disaggregated Land Unavailability"](https://chandlerlutz.github.io/pdf/land-unavailability.pdf)

Datasets
------------

Currently the data are available at the following levels of
aggregation (years correspond to geographic definitions from the US
census):
* 1999 MSAs
* 1999 MSA codes used by Saiz 2010
* 1990 counties
* 2000 counties 
* 2010 counties
* 2000 commuting zones 
* 2000 five digit zip codes
* 2010 five digit zip codes
* 2000 three digit zip codes
* US states



Folders
------------

* **Data_LU**: Land Unavailability total unavailability and
  unavailability due to slope, water, and wetlands. Zip and county
  files also contain a list-column with touching, adjacent polygons
  and summary statistics for Land Unavailability in these adjacent
  polygons.  These can all be read in using the R `readRDS()` function
  (the `data.table` package may be helpful in viewing these
  files). Zip code files contain
* **DATA_LU_csv**: Csv files with above information. The list-column
  with adjacent polygons is lost in the conversion to csv. 

License 
------------

For academic, non-commercial use only. For all other uses, please
contact authors. 
