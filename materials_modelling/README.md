# Exercises for the “Materials modelling” course

> Course content by François-Xavier Coudert.<br/>
> Placed under [CC-BY (Creative Commons Attribution)](https://creativecommons.org/licenses/by/4.0/) license

## Notebooks

- [`01-sodium-chloride.ipynb`](01-sodium-chloride.ipynb): Introduction exercise, your first MD simulations.
  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fxcoudert/binders/blob/master/materials_modelling/01-sodium-chloride.ipynb)
  [![Open in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fxcoudert/binders/HEAD?urlpath=lab/tree/materials_modelling/01-sodium-chloride.ipynb)
- [`02-analysing-trajectories.ipynb`](02-analysing-trajectories.ipynb): How to analyze MD simulations.
  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fxcoudert/binders/blob/master/materials_modelling/02-analysing-trajectories.ipynb)
  [![Open in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fxcoudert/binders/HEAD?urlpath=lab/tree/materials_modelling/02-analysing-trajectories.ipynb)
- [`03-exploring-phase-diagram.ipynb`](03-exploring-phase-diagram.ipynb): Explore the phase diagram of NaCl with MD.
  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fxcoudert/binders/blob/master/materials_modelling/03-exploring-phase-diagram.ipynb)
  [![Open in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fxcoudert/binders/HEAD?urlpath=lab/tree/materials_modelling/03-exploring-phase-diagram.ipynb)
- [`04-physical-properties-of-zeolites.ipynb`](): TBD
- [`05-metal-organic-frameworks.ipynb`](): TBD
- [`06-adsorption-in-nanoporous-materials.ipynb`](): TBD

## Installing

If you want to create your own environment to run these, you can do:

- create a Conda environment: `conda create --name materials python=3.13`
- activate your new environment: `conda activate materials`
- install all dependencies: `conda install pandas seaborn ase mdanalysis openmm nglview`
- start a Jupyter lab server: `jupyter lab`
