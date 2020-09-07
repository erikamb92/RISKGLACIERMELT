Data Descriptor

Title

Emerging water scarcity risks in Peruvian glacier-fed river basins

Authors

Erika Martínez*, Fabian Drenkhan, Charles Zogheib, Boris F. Ochoa-Tocachi, Wouter Buytaert

2020

*Corresponding author: erika.martinez17@alumni.imperial.ac.uk

#################################################### DATA ACCESSIBILITY NOTES #########################################################################################

The maps of EXPOSURE, VULNERABILITY, HAZARD and RISK are provided in a GEOTIFF format.


There are four folders provided in the data repository, named:
1) EXPOSURE
2) VULNERABILITY
3) HAZARD
4) RISK

The first two folders contain the maps of EXPOSURE and VULNERABILITY from the VUB (Vilcanota-Urubamba) basin in a GeoTIFF format.
The third and fourth folder contain 4 scenarios of HAZARD and RISK corresponding to the current annual average normal year (avg), and annual average drought year (avg_dry),
current monthly maximum normal (max) and monthly maximum drought (max_dry) contribution of glacier melt in the VUB.


Guidelines when opening datasets:

After unzipping, the maps can be opened using any GIS-based software.


At each individual raster pixel and vector point along a river the value of either EXPOSURE, VULNERABILITY, HAZARD or RISK is listed in 
the legend under the "Pixel value". As the maps are at a very high resolution, zooming in is required to delineate details.

The file naming convention in use is the following:
<component>_<scenario>.<format>

<component>
EXPOSURE: exposed human-natural systems. District-wise distribution of people in the VUB basin, the closest abstraction point to the Vilcanota-Urubamba river surface water, assumption that all people are equally exposed

VULNERABILITY: vulnerabilities of human-natural systems. Selection of 16 different descriptors related to main sectors of water use, infrastructure, and policies

HAZARD: climate-related hazard. Threat of water scarcity driven by glacier meltwater reductions, defined by a water scarcity indicator

RISK: intersection of HAZARD, EXPOSURE and VULNERABILITY

<scenario> (only applies for HAZARD and VULNERABILITY)
avg: contribution of glacier melt to streamflow during an annual average normal year

avg dry: contribution of glacier melt to streamflow during an annual average drought year 

max: contribution of glacier melt to streamflow during a monthly maximum normal

max_dry: contribution of glacier melt to streamflow during a monthly maximum drought 

<format>
tif: Tagged Image File Format

e.g. HAZARD_max_dry.tif