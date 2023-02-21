Land Unavailability Data
===========

Land Unavailability (LU) data from ["Highly Disaggregated Land Unavailability"](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3478900) ([Cite](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=%22Highly+Disaggregated+Land+Unavailability%22&btnG=#d=gs_cit&u=%2Fscholar%3Fq%3Dinfo%3AcgQ1OyAhCM0J%3Ascholar.google.com%2F%26output%3Dcite%26scirp%3D0%26hl%3Den)).

Download 
------------

* [2023-02-19 Data Run](https://www.dropbox.com/sh/n2283soj2xopa7b/AABPqECSbjQoxyjtO3h_pxdEa?dl=0)
* [2022-06-17 Data Run](https://www.dropbox.com/sh/vhfquhq42pw9cra/AAC7dKyzu3ByqBxatIiZ_1bza?dl=0)


Datasets
------------

 
- `01-zillow_us_hp.csv` - Zillow US national house prices 
- `02-zillow_county_2002_start.csv` - Zillow county data starting in 2002: LU-ML IV and house prices
- `03-zillow_county_2011_start.csv` - Zillow county data starting in 2011: LU-ML IV and house prices
- `04-zillow_cbsa_2002_start.csv` - Zillow cbsa data starting in 2002: LU-ML IV and house prices
- `05-zillow_cbsa_2011_start.csv` - Zillow cbsa data starting in 2011: LU-ML IV and house prices
- `06-zillow_zip_2002_start.csv` - Zillow zip code data starting in 2002: LU-ML IV and house prices
- `07-zillow_zip_2011_start.csv` - Zillow zip code data starting in 2011: LU-ML IV and house prices
- `10-fhfa_at_us_hp.csv` - FHFA US national house prices -- all transactions
- `11-fhfa_po_us_hp.csv` - FHFA US national house prices -- purchases only
- `12-fhfa_lu_ml_at.csv` - FHFA cbsa data all transactions: LU-ML IV and house prices 
- `13-fhfa_lu_ml_po.csv` - FHFA cbsa data purchases only: LU-ML IV and house prices
- `20-freddie_mac_us_hpi.csv` - Freddie Mac US national house prices
- `21-freddie_mac_lu_ml.csv` - Freddie Mac cbsa data: LU-ML IV and house prices
- 📂`buildable-land` &ndash; Buildable Land for zip and zip3  
- 📂`lu-raw` &ndash; Raw LU data 

Notes and FAQ
------------

* For the Zillow HPs, we compile the LU data using data starting in 2002 or 2011. In the Zillow data, the number of geographic units (e.g., the number of zip codes) increases over time. So, data starting in 2002 data will have a longer time series, but have few cross-sectional observations. 
* For geographic regions that don't change over time (e.g. Los Angeles county), there might be some differences in our calculation of Land Unavailability due to (1) the resolution of the shapefiles from the US census; and (2) a slight error tolerance from compiling and cutting the various satellite images together.


License 
------------

For academic and government, non-commercial use only. For all other uses, please contact authors. 
