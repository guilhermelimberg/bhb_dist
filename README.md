# bhb_dist

This repository contains a catalog of spectroscopically-confirmed BHB stars from [SEGUE](https://www.sdss.org/dr12/algorithms/segue_target_selection/) data and (re)calibrated absolute magnitudes/distances based on photometry made available by [SDSS DR16](https://www.sdss.org/dr16/) and high-confidence members of [Galactic globular clusters](https://ui.adsabs.harvard.edu/abs/2021MNRAS.505.5978V/abstract) selected from [Gaia EDR3](https://www.cosmos.esa.int/web/gaia/early-data-release-3)'s astrometry.   

The main file ("bhb_final.csv") provides all photometric information of interest as well as atmospheric parameters. Notice that this catalog contains two diffent calibrations of distance based on the (g-r) or (u-r) colors and g-band magnitudes (Sloan system). We also provide the probability of each star being a genuine BHB star based on their logg estimates in comparison to the overall logg distributions of A-type stars in SEGUE. We list those objects with probability >50%, but the user is invited to utilize this parameter according to her/his needs. 

The "XXX_desc.txt" file provides the descriptions for the quantities in each column of each file.  

Please acknowledge and contact either Guilherme Limberg -- guilherme.limberg(at)usp.br -- or Fabrícia Barbosa -- fabriciaob(at)usp.br -- for any questions.

The paper that describes the construction of this catalog is published as [Barbosa et al. (2022)](https://iopscience.iop.org/article/10.3847/1538-4357/ac983f) -- Open Access. You can find the proper citation at [NASA/ADS](https://ui.adsabs.harvard.edu/abs/2022arXiv221002820B/abstract). Also, you can check the [arXiv](https://arxiv.org/abs/2210.02820) version.
