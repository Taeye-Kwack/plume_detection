# plume model
This is a study that calculates carbon dioxide emissions of the urban area by using the satellite's greenhouse gas observations.
I used column-averaged of carbon dioxide(XCO2) of OCO-2 and vertical column densities (VCDs) of tropospheric NO2 of TROPOMI. 
In urban areas, greenhouse gases are emitted directly from transportation and heating. 
The concentration of GHG is distrinuted in the form of plume, which decreases in value as they move farther away from urban areas. 

NO2's lifetime(few hours) is much shorter than that of CO2(hundreds of years), making it easier to identify the source. 
Also, NO2 is co-emitted with CO2 during combustion, so the source of CO2 can be determined.
This study uses CO2 and NO2 observations at the same time over Seoul domain to obtain CO2 emissions in urban areas and compare them with existing inventory data.
While inventory yields emissions by a bottom-up method, which is time-consuming and costly, 
it is simpler to produce emissions by a top-down method with satellite observations such as this study.

This study was conducted using the same method as the paper below.
(https://doi.org/10.5194/acp-19-9371-2019)
