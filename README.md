# Interpretation and comparison of interglacial PMIP experiments with Pre-Industrial piControl.

*Final project for EOS 440, UBC - Climate Modelling*



## Project objective

To compare and analyse the seasonal variations in precipitation and temperature between the PMIP Last Interglacial (LIG) and Mid-Holocene (MH), and Pre-Industrial (piControl) experiments with a focus on the depiction of global monsoon patterns and artic amplification. The project will explore how these variables respond to the variations in initial paramaters, such as orbital conifgurations and GHG levels, and what this implies for future climate scenarios under ongoing climate change.

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

Open the jupyter notebook, follow and/or run cells to produce the primary and supplementary figures for this project.
```bash
jupyter lab produce_figures.ipynb
```


### Important Files 

1. **[produce_figures.ipynb](produce_figures.ipynb)** 
 This is the main code source for reproducing the figures seen in the project report. 

3. **[environment.yml](environment.yml)** 
 Environment file, necessary for running notebooks.

Figures and information is cited where used; code uses CMIP6 datasets, particularly the contributions from PMIP4. For further informaiton on the PMIP4 project, see links below:

PMIP4 Webpage:
https://pmip4.lsce.ipsl.fr/doku.php

The Climate Laboratory - EOS440 course handbook, adapted from the ATM 623: Climate Modeling at the University at Albany:
https://phaustin.github.io/climate_students_eoas/home.html
https://www.atmos.albany.edu/facstaff/brose/classes/ATM623_Spring2019/

Citation and link for main paper considered in this project:
Otto-Bliesner, B. L., Braconnot, P., Harrison, S. P., Lunt, D. J., Abe-Ouchi, A., Albani, S., Bartlein, P. J., Capron, E., Carlson, A. E., Dutton, A., Fischer, H., Goelzer, H., Govin, A., Haywood, A., Joos, F., LeGrande, A. N., Lipscomb, W. H., Lohmann, G., Mahowald, N., . . . Zhang, Q. (2017). The PMIP4 contribution to CMIP6 – Part 2: Two interglacials, scientific objective and experimental design for Holocene and Last Interglacial simulations. Geoscientific Model Development, 10(11), 3979–4003. https://doi.org/10.5194/gmd-10-3979-2017
