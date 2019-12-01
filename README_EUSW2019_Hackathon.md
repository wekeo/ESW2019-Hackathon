# European Space Week (EUSW) Hackathon 2019

![EventBanner](https://github.com/WEkEO/ESW2019-Hackathon/blob/master/EUSWHackathon_2019.png)

The European Space Week (EUSW) will take place in Helsinki (Finland) on 3-5 December. The EUSW is an international event for European space programs in which policy makers, space experts and user communities participate. WEkEO will be present at the General Assembly and the EUSW Hackathon.

The EUSW hackathon is hosted by the European Commission during the EU Space Week 2019 and it lasts for 48 hours. Participants will develop prototypes concerning European Emergency Apps. Some examples are location-based emergency alerts, safe routes for emergency responders, etc. WEkEO will provide access to Copernicus data and cloud infrastructure. Experts from Copernicus and the European Global Navigation Satellite Systems (EGNSS) will support participants in the development of their ideas. There will also be emergency response professionals and business coaches. WEkEO will offer on-site and remote technical support for the participants at the EUSW hackathon.


More info about the event at: https://euspaceweek.eu/programme/eusw-hackathon/

Information about the EUSW Hackathon: https://www.wekeo.eu/news

WEkEO webinar for the event: https://www.youtube.com/watch?v=gS-yWWKsaF0



 # Table of contents
1. [The Challenge: European Emergency Apps](#challenge)
2. [Platform offering](#platform)  
3. [Dataset offering](#datasets)
4. [Data Access](#data)
5. [Processing Resources](#processingresources)
6. [Useful Links](#useful)


# The Challenge: European Emergency Apps <a name="challenge"></a>

Related topics to the challenge are:

### * Floods
In recent years, floods have become more frequent due to the increase of intense meteorological event.

### * Forest fires
The identification of fire hot spots and the spread of fire events can be done with satellite data.
This fires can take place in the natural environment or be related to industrial disasters.

### * Landslides
Extent of damages caused by landslides can be mapped with satellite data.



# Platform offering <a name="platform"></a>

WEkEO is a Data and Information Access System (DIAS) that provides access to Copernicus data and cloud-based processing resources. You can access WEkEO at https://www.wekeo.eu/

As a participant of the Copernicus Hackathon & Climathon you are offered:
- Essential access to Copernicus Data and Jupyter Notebooks.
- Advanced access to a Virtual Machine in the WEkEO cloud infrastructure so that you can process the data.


SSH Access 






# Dataset offering <a name="datasets"></a>

Some examples of the different types of datasets available at WEkEO are listed below. This is a very small sample of the type of data that you can find on WEkEO related to Emergency Management. 


You can browse the WEkEO datasets catalogue and download data at https://www.wekeo.eu/dataset-navigator/start



**Sentinel-1**

Sentinel-1 is an imaging radar mission that has a Synthetic Aperture Radar (SAR) instrument providing continuous all-weather, day-and-night imagery at C-band. Sentinel-1 can be used for the following Emergency Management applications: flood monitoring, earthquake analysis, landslide and volcano monitoring. Sentinel-1 can also be useful for Forest fires and scar analysis.


|  Dataset Name | Dataset ID | Geo Coverage   | Time Coverage  | Resolution   |  Format |  
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
|Sentinel-1 Level-1 Ground Range Detected (GRD) | EO:ESA:DAT:SENTINEL-1:L1_GRD | Global | Global | 03/04/2014 to now | No info | .tiff compressed in .zip | 
|Sentinel-1 Level-1 Single Look Complex (SLC) | EO:ESA:DAT:SENTINEL-1:L1_GRD | Global | Global | 03/04/2014 to now | No info | .tiff compressed in .zip | 


There are 4 different modes of operation for Sentinel-1. The Sentinel-1 data available at WEkEO is in Interferometric Wide Swath (IW) and Extra-Wide Swath (EW).



**Sentinel-2**

Sentinel-2 is an

|  Dataset Name | Dataset ID | Geo Coverage   | Time Coverage  | Resolution   |  Format |  
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
|Sentinel-2 Level-1C MultiSpectral Instrument (MSI) | EO:ESA:DAT:SENTINEL-2:MSI1C | Global | Global | 03/04/2014 to now | No info | .tiff compressed in .zip | 



In addition to data from Sentinel satellites, WEkEO has a wide range of datasets available. 
Some examples that might be useful are included below. 


**Climate**

|  Dataset Name | Dataset ID | Geo Coverage   | Time Coverage  | Resolution   |  Format |  
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
|ERA5 hourly data on single levels from 1979 to present | EO:ECMWF:DAT:ERA5_HOURLY_DATA_ON_SINGLE_LEVELS_1979_PRESENT | Global | 1979-2019 | No info | No info | GRIB, NetCDF (experimental) | 


**Marine**

|  Dataset Name | Dataset ID | Geo Coverage   | Time Coverage  | Resolution   |  Format |  
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
|Mediterranean Sea - High Resolution and Ultra High Resolution L3S Sea Surface Temperature |EO:MO:DAT:SST_MED_SST_L3S_NRT_OBSERVATIONS_010_012 |Latitude 30.25 to 46 degrees, Longitude -18.12 to 36.25 degrees | 01/01/2016 to now | No info | NetCDF | 




# Data Access <a name="data"></a>

**Copernicus Climate Data Store (CDS) Access** 

**Copernicus Climate Data Store (CDS) Access** 

https://cds.climate.copernicus.eu/#!/home

The Climate Data Store Application Program Interface (CDS) provides programmatic access to CDS data. 

• Self-register at https://cds.climate.copernicus.eu/user/register?destination=%2F%23!%2Fhome

• Login at https://cds.climate.copernicus.eu/user/login?destination=%2F%23!%2Fhome


If you are using Linux

• Install the CDS API key: 

Copy in the file $HOME/.cdsapirc (in your Unix/Linux environment):
url: https://cds.climate.copernicus.eu/api/v2
key: {uid}:{api-key}


• Install the CDS API client

The CDS API client is a python based library. It provides support for both Python 2.7.x and Python 3.

You can Install the CDS API client via the package management system pip, by running on Unix/Linux the following command: $ pip install cdsapi

If you are using Windows or macOS, you can find more information at:
https://cds.climate.copernicus.eu/api-how-to#install-the-cds-api-key


**Copernicus Marine Environment Monitoring Service** 

In case you want to find more information about marine products:

• Self-register at http://marine.copernicus.eu/services-portfolio/register-now/

• Login at http://marine.copernicus.eu/services-portfolio/access-to-products/?option=com_csw&view=account




# Processing Resources <a name="data"></a>

**SSH access** 

Each team will be given a username and password to access a Virtual Machine (VM) on WEkEO using Linux commands.
An example on how to access a VM through SSH can be seen below:

![Imagessh](https://github.com/WEkEO/ESW2019-Hackathon/blob/master/EUSWHackathon_2019.png)



# Useful Links <a name="useful"></a>

• Documentation and guides on how to access the data and the virtual machines are available at:
https://www.wekeo.eu/documentation/getting_started

• Copernicus Services (Atmosphere, Marine, Land, Climate Change, Security, Emergency)
https://www.copernicus.eu/en/services

• Copernicus Emergency Management Service
https://www.copernicus.eu/en/services/emergency

• European Flood Awareness System (EFAS)
https://www.copernicus.eu/en/european-flood-awareness-system

• European Forest Fire Information System (EFFIS)
https://www.copernicus.eu/en/european-forest-fire-information-system

• European Drought Observatory (EDO)
https://www.copernicus.eu/en/european-drought-observatory

• ESA Thematic Areas - Emergency Management
https://sentinel.esa.int/web/sentinel/thematic-areas/emergency-management

• ESA Thematic Areas - Emergency Management
https://step.esa.int/main/toolboxes/snap/

• GDAL
https://gdal.org/

• How to visualize NetCDF data
https://www.youtube.com/watch?v=XqoetylQAIY

• Jupyter
https://jupyter.org/

• Panoply
https://www.giss.nasa.gov/tools/panoply/

• QGIS
https://qgis.org/en/site/

• SciPy
https://www.scipy.org/

• SciTools
https://scitools.org.uk/

• Xarray
http://xarray.pydata.org/en/stable/
