# Comparing Seasonal Variations in Temperature and Precipitation in PMIP LIG and MH Simulations: Implications for Monsoon Patterns under Climate Change

*Final project for EOS 440, UBC*

*Please note: '!! WIP !!' means work in progress and not to be conisdered complete at this time.*

## Project objective

To compare and analyse the seasonal variations in precipitation between the PMIP Last Interglacial (LIG) and Mid-Holocene (MH), and modern day (PICONTROL) experiments with a specific focus on the depiction of global monsoon patterns. The project will explore how these models simulate monsoon behaviour and what this implies for future climate scenarios under ongoing climate change.

### Using the code

The code is provided in the form of jupyter labs, reccommended to be run via conda, or anaconda navigator for those with a preference for visual interfaces. Any necessary packages are provided, see below for instructions.

### Installing environment

1. Clone the repo
```bash
git clone https://github.com/KellySavanna/440_PMIP_modelling.git
```
2. Create environment from included yml file
```bash
conda env create -f environment.yml
```
3. Activate environment
```bash
conda activate env_440
```
### Running notebooks

1. Open the jupyter notebook, follow and/or run cells to see how it works.
```bash
jupyter notebook produce_figures.ipynb
```
OR

2.  View figures without running code:  !! WIP !!

### Important Files 

1. **[produce_figures.ipynb](produce_figures.ipynb)** 
 This is the main code source for reproducing the figures seen in the project report. 

3. **[environment.yml](environment.yml)** 
 Environment file, necessary for running notebooks.

Figures and information is cited where used; code uses CMIP6 datasets, particularly the contributions from PMIP4. For further informaiton on the PMIP4 project, see links below:

PMIP4 Webpage:
https://pmip4.lsce.ipsl.fr/doku.php

Citation and link for main paper considered in this project:
Otto-Bliesner, B. L., Braconnot, P., Harrison, S. P., Lunt, D. J., Abe-Ouchi, A., Albani, S., Bartlein, P. J., Capron, E., Carlson, A. E., Dutton, A., Fischer, H., Goelzer, H., Govin, A., Haywood, A., Joos, F., LeGrande, A. N., Lipscomb, W. H., Lohmann, G., Mahowald, N., . . . Zhang, Q. (2017). The PMIP4 contribution to CMIP6 – Part 2: Two interglacials, scientific objective and experimental design for Holocene and Last Interglacial simulations. Geoscientific Model Development, 10(11), 3979–4003. https://doi.org/10.5194/gmd-10-3979-2017
