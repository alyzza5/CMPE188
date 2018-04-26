# CMPE188

Work so far:
- removed unneccessary columns from datasets
- removed NULL from illegal dumping 
- 911 datasets will not be used b/c they do not have the zip code or lat/long. Thus, can't be compared to other sets like originally thought 
- combine streetlights and illegal dumping sets by lat/long

preprocessing steps
- (NOT NECC.) addresses to lat/long https://stevemorse.org/jcal/latlonbatch.html
- (DONE) delete null location for dump set
- (CANCELED) remove nulls from 911 data, canceled, 

To Do:
- find correlations between category of illegal dumping and dist. to streetlight
- based on type of dumping, predict distance from streetlight 
