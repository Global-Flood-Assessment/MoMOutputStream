# VIIRS Population add-on
[VIIRS Population Notebook](https://github.com/Global-Flood-Assessment/ModelOfModels/blob/master/VIIRS+MOM/VIIRS_Pop_Example.ipynb) explains the data and workflow of VIIRS population add-on.

The impacted watersheds are selected by:  
* "Alert" = "Warning" or "Watch"
* "Flag" = 3   #1-HWRF 2-DFO 3-VIIRS

The three new columns are added to MoM output:   
 - Totalpop: the total population in a watersheds
 - VIIRS_impactpop: the population impacted the flooded area extracted from VIIRS image
 - "VIIRS_impactpop_percent: VIIRS_impactpop / Totalpop (%)

The file is renamed the following way:  
MoM output:   
Final_Attributes_2022122606HWRF+20221225DFO+20221225VIIRSUpdated.csv  
MoM output with VIIRS population columns:  
Final_Attributes_2022122606HWRF+20221225DFO+20221225VIIRS_PopUpdated.csv  

