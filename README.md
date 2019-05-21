# statsassignment

This is the statistical modelling prac.

I will be using data from 
https://confluence.csiro.au/display/Digiscape/Climate+Forecast+Data+aggregation
https://dcdp.research.csiro.au/silo?lat=-35.4184&lon=149.0937&format=csv&start=19600101

The data was collected at 
Tuggeranong(Isabella Plains) Weather Recording Station
Falconer Street Monash ACT
latitude            -35.4184
longitude           149.0937

The data is presented as a long string with spaces for line breaks and commas for column breaks.
I transferred the data as a txt file and then saved to a csv file.

There are two header rows. The first provides variable names and the second provides units which each variable was measured in.

date,rad,tmax,tmin,rain,vp,evap
-,MJ/m^2,oC,oC,mm,hPa,mm

DATE                    date          dd/mm/yyyy

RADIATION               rad           MJ/m^2
Solar Radiation	MJ/sq m	Solar radiation is for the previous day. 

MAXIMUM TEMPERATURE     tmax          oC
Maximum temperature for the 24 hour period to 9 am on the day of reporting.	Measured in degrees Celsius.

MINIMUM TEMPERATURE     tmin          oC
Minimum temperature for the 24 hour period to 9 am on the day of reporting.	Measured in degrees Celsius.

RAINFALL                rain          mm
Rainfall (Precipitation) is the amount of rain for the 24 hour period to 9am on the day of reporting. Measured in millimetres.

VAPOUR PRESSURE         vp            hPa
The vapour pressure (in hectopascals) is calculated from the dewpoint temperature (in degrees Celsius), via the equation
          vapour pressure = exp (1.8096 + (17.269425 * dewpoint)/(237.3 + dewpoint))

EVAPORATION             evap          mm 1
Evaporation	is the amount of water loss by evaporation from a pan of water per day for the 24 hour period to 9am on the day of reporting. 
The pan is about 120cm in diameter and about 25cm deep. The water levels are measured and compared each day. The difference in the levels is the amount of evaporation.	Measured in millimetres.

 
