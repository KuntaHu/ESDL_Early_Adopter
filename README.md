# ESDL_Early_Adopter
GLOBAL HEATWAVE AND WILDFIRE ANALYSIS BASED ON THE ESDL DATA

ESDC webpage: http://www.earthsystemdatacube.net/

Thanks ESDL team for provision of computing server and guidance. 
And thanks the ESDL Forum for answering the questions about programming. 
Very grateful to all data owners for kindly providing the data sets free of charge from the owners, the ESDL team or ESA.

In the help of ESDL data cube, it becomes much easier to reach the climate data derived from satellite data such as GFED, precipitation, temperature and carbon emission. Based on these long-term data, first we search regionally the Europe for the most dramatic burnt area in the history from 1995 to 2014. And then zoom in the vision into specific area located in Portugal as the study area. Next, the 2D spatial visualization is applied to search the study area by Year, Month and Week. The default functions in ESDL makes the spatial analysis by specific grouped time dimension accessible easily. Finally, the study area in specific ignition time are confirmed then used for the next step.

In the second part, multi-variables time series analysis are implemented in order to verify the spatial analysis conclusion and also provide the comparison results across time from multi-source like precipitation, temperature and carbon emission. The relationship between these four variables are strong. Low precipitation and high air temperature are always aligned before and during the wildfire which can be regarded as the main causes of the wildfire. And then the carbon emission also enlarges dramatically during the fire since the biomass fuel consumes the oxygen, and produced mass of carbon dioxide. Based on the time series analysis, we could make it clear about the complex relationship between different impact variables. And finally, we return to the spatial analysis in 2D and draw the distribution of extreme temperature and low precipitation in study area, which could provide an spatial vision for the burnt area with temperature and precipitation. Another reason is that the smaller scale in time with temperature and precipitation by week could further help us to analyze the short-term consequence caused by them, since GFED only provides the monthly burnt area and carbon emission.

Project	        Name in ESDC	    Description

GFED4	
  burnt_area	
  Burnt Area based on the GFED4 fire product.
  
  c_emissions	
  Carbon dioxide emissions due to natural fires expressed as carbon flux.
  
GPCP	
  precipitation	
  Precipitation based on the GPCP dataset.
  
ERAInterim	
  air_temperature_2m	
  Air temperature at 2m from the ERAInterim reanalysis product.


