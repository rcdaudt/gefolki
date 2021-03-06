---------------------------------------------------------------------------------------------------------
All data provided in this Datasets to test GeFolki come from various institutions: 


• LIDAR data have been provided by Johan Fransson
from SLU (Swedish University of Agricultural Sciences),
and by Lars Ulander from FOI (Swedish Defence Research
Agency), for whom we are deeply grateful. 
All LIDAR images have been processed by SLU. 
The initial image used in this set is a 0.5x0.5m resolution DEM
processed by SLU.

The data acquisition has been funded by ESA through the BIOSAR 3 campaign
https://earth.esa.int/web/guest/campaigns



• all SAR images have been provided from the BIOSAR 3 campaign funding by ESA,
acquired by the airborne SETHI system from Onera.
All SLC images used here are avaible upon request:
https://earth.esa.int/web/guest/campaigns.


• The optical image over Sweden has been provided by Lantmäteriet.
It has been processed from a RGB orthophoto initial dataset: 

GSD-orthophoto 0.5m RGB
Lantmäteriet, Division Geodata
Lantmäterigatan 2, 801 82 Gävle
www.lantmateriet.se

---------------------------------------------------------------------------------------------------------
Images provided in DataSets have all been post-processed by Guillaume Brigot and Elise Koeniguer in Onera.
Guillaume Brigot, is a PhD student jointly supervised by Elise Koeniguer in Onera and Marc Simard in JPL. 
His PhD is supported jointly by TOTAL and Onera. 

• Resampling of LIDAR and optics images have been applied in order to initialize the coregistration over the 
radar image, by using only geoding information of initial images and SAR trajectories. 

• the RGB P-band SAR image has been processed by using the usual Pauli basis coding: 
Red:HH-VV, Green:HV+VH, Blue:HH+VV.
The image has been filtered by using the NLSAR toolbox developped by Charles Deledalle and available here:
https://www.math.u-bordeaux.fr/~cdeledal/nlsar.php

---------------------------------------------------------------------------------------------------------

The authors of GeFolki are thankful to Malcolm Davidson and Michael Foumelis from ESA-ESRIN for their 
very informative recommendations.



