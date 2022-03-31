Land Unavailability Data
===========

Land Unavailability (LU) data from ["Highly Disaggregated Land Unavailability"](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3478900) ([Cite](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=%22Highly+Disaggregated+Land+Unavailability%22&btnG=#d=gs_cit&u=%2Fscholar%3Fq%3Dinfo%3AcgQ1OyAhCM0J%3Ascholar.google.com%2F%26output%3Dcite%26scirp%3D0%26hl%3Den)).

Download 
------------

* [2022-03-24 Data Run](https://www.dropbox.com/sh/kinpoyc2z07v9vx/AADoAN_Nz6ZL4mRI5AOJf11Ra?dl=0)


Datasets
------------

📂`best-lu-for-fhfa-hp` &ndash; LU ML and HP data for FHFA House Prices  
📂`best-lu-for-freddie-mac-hp` &ndash; LU ML and HP data for Freddie Mac House Prices  
📂`best-lu-for-zillow-hp` &ndash; LU ML and HP data for Zillow House Prices  
📂`buildable-land` &ndash; Buildable Land for zip and zip3  
📂`lu-raw` &ndash; Raw LU data  

* `*lu_panel_ml_best.csv` files -- We use machine learning (ML) algorithms and land unavailability (LU) proxies at multiple levels of disaggregation to generate this panel dataset of LU estimates that can be used as an instrument for house prices in a panel data framework. 
* `*lu_total_ml_best.csv` files -- We use ML techniques to choose the optimal polygon shape for which to calculate total land unavailability. These datasets report the total land unavailability for those optimal polygon shapes, yielding a cross-sectional dataset of land unavailability estimates (e.g., one LU estimate for each CBSA). 
* `*lu_total_ml_best.csv` files -- We again use ML techniques to choose the optimal polygon shape. These files report the components of land unavailability.  


Notes and FAQ
------------

* Note that for geographic regions that don't change over time (e.g. Los Angeles county), there might be some differences in our calculation of Land Unavailability due to (1) the resolution of the shapefiles from the US census; and (2) a slight error tolerance from compiling and cutting the various satellite images together.
* The components in the `*lu_total_ml_best.csv` files will not necessarily sum to the totals in the `*lu_total_ml_best.csv` as the optimal polygon shape for which we calculate land unavailability is allowed to differ across the two calculations. 

License 
------------

For academic and government, non-commercial use only. For all other uses, please contact authors. 
