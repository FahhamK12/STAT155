Research Introduction

Question: Does using a certain discovery method correlate with different exoplanet parameters being measured?

Reproducibility: Each project and its code should be able to be reproduced by simply copying it into RStudio.

Introduction: Exoplanet discovery is a relatively new field of science. As a result, the data that has been collected has some biases. For example, exoplanets with a long orbital period are not common discoveries since we haven't had the opportunity to see them make full orbits around their stars. With this limiting factor existing, different discovery methods have their own limiting factors. This project intends to discover those factors.

Hypothesis: Certain discovery methods will correlate to different exoplanet parameters.

Dataset: The dataset being used in NASA's exoplanet archive, which gives data on all known exoplanetary systems. The data was collected through various missions and telescopes. Variables such as discovery method, planet name, and planet mass are given.

Key Variables: 
| Variable        | Description                         |
|-----------------|-------------------------------------|
| pl_name         | Planet name                         |
| hostname        | Host star name                      |
| discoverymethod | Method used to detect the exoplanet |
| pl_orbper       | Orbital period (days)               |
| pl_orbeccen     | Eccentricity                        |
| pl_orbsmax      | Semi-major axis (AU)                |
| pl_massj        | Planet mass (Jupiter masses)        |
| pl_rade         | Planet radius (Earth radii)         |
| pl_eqt          | Effective Temperature (K)           |
| st_rad          | Steller Radius (Solar Radii)        |
| st_teff         | Stellar effective temperature (K)   |
| st_mass         | Stellar mass (Solar masses)         |

sessionInfo()
R version 4.4.2 (2024-10-31 ucrt)
Platform: x86_64-w64-mingw32/x64
Running under: Windows 11 x64 (build 26100)

locale:
[1] LC_COLLATE=English_United States.utf8  LC_CTYPE=English_United States.utf8   
[3] LC_MONETARY=English_United States.utf8 LC_NUMERIC=C                          
[5] LC_TIME=English_United States.utf8    

time zone: America/Los_Angeles
tzcode source: internal

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
[1] tidyr_1.3.1          datadictionary_1.0.1 dplyr_1.1.4          ggplot2_3.5.2       
[5] Matrix_1.7-1 
