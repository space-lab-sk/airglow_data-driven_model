[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4306913.svg)](https://doi.org/10.5281/zenodo.4306913)

## Data-driven modeling of atomic oxygen airglow over a period of three solar cycles
### Supplemental materials to the paper in [JGR: Space Physics](https://doi.org/10.1029/2020JA028991) ([pre-print](https://www.essoar.org/doi/abs/10.1002/essoar.10505187.2), [Full Text](https://agupubs.onlinelibrary.wiley.com/doi/epdf/10.1029/2020JA028991)):

- **Python notebook** ([airglow_data_driven_modeling.ipynb](/airglow_data_driven_modeling.ipynb)) that contains complete analysis and results presented in the article

- **Pandas Data Frames** with data for the machine learning techniques described in the [Python notebook](/airglow_data_driven_modeling.ipynb) to model airglow green line ([df_i5577_label_features_1964-1993.pkl](/df_i5577_label_features_1964-1993.pkl)) and red line ([df_i6300_label_features_1964-1993.pkl](/df_i6300_label_features_1964-1993.pkl)). 
Data Frames consists of:
  - airglow data (available via: https://ndmc.dlr.de/)
  - space weather indeces (downloaded from: https://omniweb.gsfc.nasa.gov/form/dx1.html)
  - thermosphere parameters (downloaded from https://ccmc.gsfc.nasa.gov/modelweb/models/nrlmsise00.php)
  - ionosphere parameters (downloaded from: https://ccmc.gsfc.nasa.gov/modelweb/models/iri2016$\_$vitmo.php)
  - Sun-Earth distance (calculated by: https://pypi.org/project/pyephem)
  
- **Pandas Data Frame** ([df_glow_1964-1993.pkl](/df_glow_1964-1993.pkl)) that contain airglow intensities calculated by the GLOW model (calculated by: https://github.com/scivision/ncar-glow)


---

### How to cite:

Mackovjak, Š., Varga, M., Hrivňak, S., Palkoci, O., & Didebulidze, G. G. (2021). Data‐driven modeling of atomic oxygen airglow over a period of three solar cycles. Journal of Geophysical Research: Space Physics, 126, e2020JA028991. https://doi.org/10.1029/2020JA028991

***BibTex:***  
*@article{https://doi.org/10.1029/2020JA028991,  
author = {Mackovjak, S. and Varga, M. and Hrivnak, S. and Palkoci, O. and Didebulidze, G. G.},  
title = {Data-Driven Modeling of Atomic Oxygen Airglow over a Period of Three Solar Cycles},  
journal = {Journal of Geophysical Research: Space Physics},  
volume = {126},  
number = {3},  
pages = {e2020JA028991},  
keywords = {airglow, machine learning},  
doi = {https://doi.org/10.1029/2020JA028991},  
url = {https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2020JA028991},  
year = {2021}  
}*
