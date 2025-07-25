Data: NASA's exoplanet archive, which has data on every exoplanet that has been discovered. Extracted from: https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=PS. 

Data Cleaning: Through the link https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=PS, you can extract a csv version of the data presented. After being extracted, the data was filtered so that the majority of columns were removed, leaving only the columns shown below in the data dictionary. 

Data Dictionary: Dimensions: 67 Variables, 5869 observations
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

