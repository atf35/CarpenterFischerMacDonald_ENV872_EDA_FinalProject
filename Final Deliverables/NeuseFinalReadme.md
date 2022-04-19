---

# CarpenterFischerMacDonald_ENV872_EDA_FinalProject

Final Project Repository for Environmental Data Analytics (ENV 872L) at Duke University, Spring 2022

#Summary
<This repository contains all our data, analysis, and writeup surrounding our research questions- does specific conductance of the Nuese River in Kinston, North Carolina vary seasonally? And what are the specific drivers for specific conductance, calcium, magnesium or sodium? The repository contains all of our data, both raw and processed to a usable format. We pulled both discharge and water quality data from United States Geologic Survey (USGS) National Water information system (NWIS).>

#Investigators
<Atalie Fischer, Duke MEM, atalie.fischer@duke.edu
 Kathlyn MacDonald, Duke MEM, kathlyn.macdonald@duke.edu
 Jack Carpenter, Duke MEM, jack.carpenter@duke.edu>

#Keywords
<Specific Conductance, Neuse River, Kinston, North Carolina, Salinity, Seasonality>

#Database Information
<All the data used in this repository was pulled on April 10, 2022 from the USGS NWIS gage (site 02089500) between the years 1976 to 2022.>

#Folder structure, file formats, and naming conventions
<This repository contains 4 folders: data, code, project items, and final deliverables. The data folder holds both the raw and processed data pulled from the site listed above. Our readme file contains all of the coding work we did to run the analysis and results is in the code file. The project items folder contains the original templates provided by EDA class repository. Lastly, the final deliverables folder holds the final pdf version of our analysis.>

#Metadata
<The raw data file contains both discharge and water quality data sets.The raw flow data contains the Agency ID (USGS), the site number, date sampled, discharge rate in cubic feet per second and the approval code. The processed flow data contains the date, discharge rate (cubic feet/second), year and month. The raw water quality data contains: organization ID, organization full name, activity identifier, activity type code, activity media name (water), activity subdivision name, start date, start time, start time zone, end date, end time, end time zone, depth height value, depth height code, altitude reference point, activity top depth height value, activity top depth height code, activity bottom depth value, activity bottom code, project identifier, conducting organization, location ID, comments, aquifer, hydrologic condition, hydrologic event name, collection method ID, collection method name, collection equipment, results to the detection test, name of characteristic (sodium, conductivity, magnesium...), fraction test result, fraction test unit code, measure qualifier code, results status identifier, statistical base code, result value, result weight, result time basis, result temperature basis, result particle size basis, precision value, result comment, USGSP code, result depth height value, result depth heigh code, result depth height reference point. Lastly the processed water quality data contains only what we needed separated by monthly sampling: sample date, hydrologic condition, magnesium concentration (mg), calcium concentration (mg), sodium concentration (na), specific conductivity (uS/cm), year, month and the month rounded to the first date.>

#Scripts and code
<We used the dataRetrieval package to pull our data from the USGS site, without needing to download the large data set.>
