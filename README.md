# bhb_dist

This repository contains a catalog of spectroscopically-confirmed BHB stars from SEGUE data and (re)calibrated absolute magnitudes/distances based on photometry made available by SDSS DR16 and high-confidence members of Galactic globular clusters selected from Gaia EDR3's astrometry.   

The main file ("bhb_final_pm.csv") provides all photometric information of interest as well as atmospheric parameters and astrometric data. Notice that this catalog contains two diffent calibrations of distance based on the (g-r) or (u-g) colors and g-band magnitudes (Sloan system). We also provide the probability of each star being a genuine BHB star based on their logg estimates in comparison to the overall logg distributions for A-type stars in SEGUE. We only list those objects with probability > 50%, but the user is invited to utilize this parameter according to her/his needs. 

We also provide a secondary file ("bhb_final_pm_OrbParam.csv") with the same information as the above-described one, but including orbital parameters. These were calculated within the [McMillan2017](https://ui.adsabs.harvard.edu/abs/2017MNRAS.465...76M/abstract) potential using the [AGAMA](https://ui.adsabs.harvard.edu/abs/2019MNRAS.482.1525V/abstract) package. For this task, the position of the Sun in the Galactocentric cartesian system is (X,Y,Z)sun = (-8.2, 0.0, 0.028) kpc ([B-H2016](https://ui.adsabs.harvard.edu/abs/2016ARA%26A..54..529B/abstract), [BB2019](https://ui.adsabs.harvard.edu/abs/2019MNRAS.482.1417B/abstract)) and the velocity of the circular motion at this location is v_circ = 232.8 km/s (as in the McMillan2017 potential). The peculiar motion of the Sun with respect the local standard of rest is (U,V,W)sun = (11.10, 12.24, 7.25) km/s ([Schonrich+2010](https://ui.adsabs.harvard.edu/abs/2010MNRAS.403.1829S/abstract)). 16th, 50th, and 84th percentiles are provided from the resulting distributions of each kinematic/dynamical parameter following a Monte Carlo approach to perform 100 realizations of each star's orbit taking into account uncertainties in the observed quantities.

The "XXX_desc.txt" files provide the descriptions for the quantities in each column of each file.  

Please acknowledge and contact either guilherme.limberg@usp.br or fabriciaob@usp.br for any questions.

