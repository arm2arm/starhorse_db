# StarHorse
Example notebooks for accessing the StarHorse datasets: https://arxiv.org/abs/1904.11302

The data location:

*  https://gaia.aip.de - ADQL/PostgreSQL/TAP 
*  https://data.aip.de/starhorse - FITS/HDF5/CSV


# Dataset version
* 10.07.2019: **v0.5**

# Usage
## On the machine with Jupyter
  ```
   git https://github.com/arm2arm/starhorse_db.git 
   cd starhorse_db
   pip install -r requirements.txt
   jupyter notebook 
  ```
## running examples on the https://mybinder.org
* open the link https://gke.mybinder.org/
* add to the field '**GitHub repository name or URL**'  https://github.com/arm2arm/starhorse_db
* press the **launch** button

## Or direct buttons
- [Tutorial for SH (cmd_from_db)](cmd_from_db.ipynb):[![MyBinder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/arm2arm/starhorse_db/master?filepath=cmd_from_db.ipynb)
 [![Google Colab](https://badgen.net/badge/Launch/on%20Google%20Colab/blue?icon=terminal)](https://colab.research.google.com/github/arm2arm/starhorse_db/blob/master/cmd_from_db.ipynb)