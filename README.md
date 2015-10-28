#INFM600
Dataset creation for INFM600 Information Organization assignment

Version
-------

Version 1.0 (October 2015)


Description
-----------

The combination of datasets on Public Presubmission Community Meetings, Bus Routes and Bus Stops in Howard County led to the creation of the new dataset "Bus Connectivity to Community meetings". This dataset can be useful in verifying the following hypothesis:

    - "Howard County has poor bus connectivity to places of community meetings leading to a low public attendance." 

The result would be best reported using a geographical map. Bus routes can be depicted by colored lines representing different bus routes. Places (points) of community meetings and bus stops can be represented by two different colored pins. A dotted straight line can be drawn from the place of meeting to nearest bus stop. As the map is drawn to scale, this dotted line can help in finding the distance between two points. The bus routes will show the connectivity of various locations to places of community meeting. This would help us identify whether public transport is a major cause leading to low public attendance at community meetings.

This dataset has been generated according to the requirements of the assignment for course INFM600, Fall 2015, at the University of Maryland, College Park.


Files
-----

**_New_ _Dataset_**

**Bus_Connectivity_to_community_meetings.csv**
This is the dataset which contains the details and locations of Pre-submission Community Meetings joined with all the Bus Transit Routes in the Howard County.

*Reference*
```
Gupta, A. (2015). PreSubmission_community_meetings_and_bus_routes [Data CSV file]. Available from https://github.com/akhil381/INFM600/
``` 

	
**_Focal_ _Dataset_**

**Public_Presubmission_Community_Meetings.csv**
This dataset contains the information about the Pre-submission Community Meetings held in Howard County. It contains particulars like project name, meeting date and time, meeting location, location address, location coordinates and other details.

*Reference*
```
Howard County. (2015). Presubmission Community Meetings | Open Data Portal [Data Set] Retrieved October 28, 2015, from https://opendata.howardcountymd.gov/Planning-and-Zoning/Presubmission-Community-Meetings/5igv-8g2m
``` 


**_Supporting_ _Datasets_**
		
**Transit_Routes.csv**
This dataset contains the various transit routes of RTA bus service in Howard County with information about the route, link for schedule, along with other information.

*Reference*
```
Howard County. (2015). Transit Bus Routes | Open Data Portal [Data Set] Retrieved October 28, 2015, from https://data.howardcountymd.gov/geoserver/ows?service=WFS&version=1.0.0&request=GetFeature&typeName=general:Transit_Routes&outputFormat=csv
``` 

**RTA_Bus_Stops.csv**
This dataset is extracted from the .xlsx file that is provided to Google to find bus schedule and other information. We have used the data from the sheet 'stops' of the excel workbook which contains information about the bus stop name and its geometric location.

*Reference*
```
Howard County. (2015). General Transit Feed Specification Data | Open Data Portal [Data Set] Retrieved October 28, 2015, from https://opendata.howardcountymd.gov/Transportation/General-Transit-Feed-Specification-Data/6jm3-qf9k
``` 


License
-------

The data in the INFM600 repository by Akhil Gupta is licensed under a Creative Commons Attribution-NonCommercial 4.0 International License (see http://creativecommons.org/licenses/by-nc-sa/4.0/). 
   	

Credits
-------

Akhil Gupta.

