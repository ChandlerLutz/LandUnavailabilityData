Land Unavailability Data
===========

Land Unavailability (LU) data from ["Highly Disaggregated Land Unavailability"](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3478900) ([Cite](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=%22Highly+Disaggregated+Land+Unavailability%22&btnG=#d=gs_cit&u=%2Fscholar%3Fq%3Dinfo%3AcgQ1OyAhCM0J%3Ascholar.google.com%2F%26output%3Dcite%26scirp%3D0%26hl%3Den)).

Download 
------------

* [2022-03-24 Data Run](https://www.dropbox.com/sh/kinpoyc2z07v9vx/AADoAN_Nz6ZL4mRI5AOJf11Ra?dl=0)


Datasets
------------

📂`buildable-land` &ndash; Buildable Land for zip and zip3  
📂`lu-raw` &ndash; Raw LU data  
6133867.png `01-zillow_us_hp.csv` - Zillow US national house prices 
📜`01-zillow_us_hp.csv` - Zillow US national house prices 
📜`02-zillow_county_2002_start.csv` 
📜`03-zillow_county_2011_start.csv` 
📜`04-zillow_cbsa_2002_start.csv` 
📜`05-zillow_cbsa_2011_start.csv`
📜`06-zillow_zip_2002_start.csv`
📜`07-zillow_zip_2011_start.csv`
📜`10-fhfa_at_us_hp.csv`
📜`11-fhfa_po_us_hp.csv`
📜`12-fhfa_lu_ml_at.csv`
📜`13-fhfa_lu_ml_po.csv`
📜`20-freddie_mac_us_hpi.csv`
📜`21-freddie_mac_lu_ml.csv`


Notes and FAQ
------------

* For the Zillow HPs, we compile the LU data using data starting in 2002 or 2011. In the Zillow data, the number of geographic units (e.g., the number of zip codes) increases over time. So, data starting in 2002 data will have a longer time series, but have few cross-sectional observations. 
* For geographic regions that don't change over time (e.g. Los Angeles county), there might be some differences in our calculation of Land Unavailability due to (1) the resolution of the shapefiles from the US census; and (2) a slight error tolerance from compiling and cutting the various satellite images together.


License 
------------

For academic and government, non-commercial use only. For all other uses, please contact authors. 
