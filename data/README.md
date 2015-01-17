Selection of health-related data.  **This is only some of the available data.**   Additional resources can be found on the [wiki for this event](https://github.com/OpenDataSTL/health-hack-weekend/wiki).  You can also add data requests to the [data request page of the wiki](https://github.com/OpenDataSTL/health-hack-weekend/wiki/Data-Requests) and we'll do our best to help you find the information you need! 
  
Notes:  

There are five files related to pedestrian and cyclist crashes - **ped-2013-geo.json**, **ped-2014-preliminary-geo.json**, **bike-2013-geo.json**, and **bike-2014-preliminary-geo.json** contain the actual crash data.  This data needs additional mapping work. When available, lat/lngs were determined using TRAVELWAY\_ID and Log combined with Missouri routes from MSDIS.  There remain many points stranded on null island.  These points will likely have to be geocoded to the intersection of ON\_LOCATION\_STREET and AT\_LOCATION\_STREET.  The fifth file is **crash-codes.csv** which contains codes to help interpret the data.
  
**food-establishments.csv** is a complete export of active permitted food facilities. **food-establishments-rough-geocode.json** was a quick, first pass geocode that caught 91% of addresses.  Depending on your project, both files may be useful. 
  
**food-inspections.csv** is a complementary dataset of establishment inspections.  
  
There are additional sources listed in the wiki under [Data Liberation](https://github.com/OpenDataSTL/health-hack-weekend/wiki/Data-Liberation) that need extraction or transformation. Feel free to add to this list.  
