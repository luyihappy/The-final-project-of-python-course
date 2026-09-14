[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/luyihappy/The-final-project-of-python-course/HEAD)
[![CC BY 4.0][cc-by-shield]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

# The final project of python course: Temperature Regression

Our group's final project.




## Layout

Description of the directory layout.

- `README.md` This is the file you're viewing right now.
- `environment.yml` Defines the required Python packages using conda. Try to pin to specific major versions of your
  dependencies as their behavior may change in the future.
  The environment is currently called `my_environment` and you'll likely want to rename it to something less generic.
- `temperature_data.csv` This is the data from which we make the regression analysis.
- `The_final_project_Temperature_Regression.ipynb`  This is the jupyter notebook document of the temperature regression.
  


## Requirements

To run the Notebooks online, click on the _Launch Binder_ badge above. Alternatively, to run on your own computer,
install Python using _e.g._ [Miniforge](https://github.com/conda-forge/miniforge) or [Anaconda](https://docs.conda.io)
and make sure all required packages are loaded by issuing the following terminal commands

``` bash
conda env create -f environment.yml
source activate my_environment
jupyter-lab
```


## Risk assessment

The code might not be usable in the future package breaking. The method to solve this problem is to set the code running environment according to the respective versions given in the file 'environment.yml'.

