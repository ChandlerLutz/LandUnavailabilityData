Land Unavailability Data
===========

Land Unavailability Data used in ["Highly Disaggregated Land Unavailability"](https://chandlerlutz.github.io/pdf/land-unavailability.pdf)

Datasets
------------

Currently the data are available at the following levels of
aggregation:
* 1999 MSAs
* 1999 MSA codes used by Saiz 2010
* 1990 counties
* 2000 counties 
* 2010 counties
* 2000 commuting zones 
* 2000 five digit zip codes
* 2010 five digit zip codes
* 2000 three digit zip codes

The data contain the following files. These can all be read in using
the R `readRDS()` function (the `data.table` package may be helpful in
viewing these files)

- **Land Unavailability** -- Land Unavailability including total
  unavailability and unavailability due to slope, water, and
  wetlands. 
  - The Land Unavailability data above can be thought of as "equal
    weighted" across a geographic region. Population weighted data,
    which can be useful for large geographic areas like counties or
    MSAs, can be constructed using the zip code Land Unavailability
    data (the lowest level of aggregation in the Land Unavailability
    dataset) and the
    [Missouri Data Bridge](http://mcdc.missouri.edu/websas/geocorr14.html).
- **Other Data** -- Other economic and geographic data used in the paper.

License 
------------

For academic, non-commercial use only. For all other uses, please
contact authors. 
