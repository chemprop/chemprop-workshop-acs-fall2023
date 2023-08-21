# Chemprop Workshop - ACS Fall 2023

Presenters: Kevin P. Greenman, Haoyang (Oscar) Wu, and William H. Green

This repo contains the slides, notebooks, and datasets for our Chemprop workshop at the ACS Fall 2023 conference. This workshop was part of the [CATL open-source software workshop series](https://chemsoftware.wordpress.com/fall2023/) at the conference.

## Workshop Agenda
1. Presentation ([slides](https://github.com/kevingreenman/chemprop-workshop-acs-fall2023/blob/main/20230816_acs_fall_chemprop_and_datasets.pdf))
2. Interactive demo ([colab](https://github.com/kevingreenman/chemprop-workshop-acs-fall2023/blob/main/chemprop_colab_demo_acs_fall2023.ipynb))
3. Interactive exercises ([colab](https://github.com/kevingreenman/chemprop-workshop-acs-fall2023/blob/main/chemprop_colab_demo_acs_fall2023_exercises.ipynb), [colab solution key](https://github.com/kevingreenman/chemprop-workshop-acs-fall2023/blob/main/chemprop_colab_demo_acs_fall2023_exercises_key.ipynb))

## Datasets
The CSV files in `data/` are used in the interactive exercises notebook and are sourced from several recent datasets published by our group:

`CombiSolu-Exp.csv`:
```
@article{vermeire2022predicting,
  title={Predicting Solubility Limits of Organic Solutes for a Wide Range of Solvents and Temperatures},
  author={Vermeire, Florence H and Chung, Yunsie and Green, William H},
  journal={Journal of the American Chemical Society},
  volume={144},
  number={24},
  pages={10785--10797},
  year={2022},
  publisher={ACS Publications}
}
@dataset{vermeire_florence_2022_5970538,
  author       = {Vermeire, Florence and
                  Chung, Yunsie and
                  Green, William},
  title        = {{SolProp Dataset for: Predicting Solubility Limits 
                   of Organic Solutes for a Wide Range of Solvents
                   and Temperatures}},
  month        = jul,
  year         = 2022,
  publisher    = {Zenodo},
  version      = {v1.2.},
  doi          = {10.1021/jacs.2c01768},
  url          = {https://doi.org/10.1021/jacs.2c01768}
}
```

`critprop_data_only_smiles_mean_value_expt.csv`:
```
@article{biswas2023predicting,
  title={Predicting Critical Properties and Acentric Factors of Fluids Using Multitask Machine Learning},
  author={Biswas, Sayandeep and Chung, Yunsie and Ramirez, Josephine and Wu, Haoyang and Green, William H},
  journal={Journal of Chemical Information and Modeling},
  year={2023},
  publisher={ACS Publications}
}
@dataset{biswas_sayandeep_2023_8072892,
  author       = {Biswas, Sayandeep and
                  Chung, Yunsie and
                  Ramirez, Josephine and
                  Wu, Haoyang and
                  Green, William},
  title        = {{Data sets and machine learning models for: 
                   Predicting critical properties and acentric factor
                   of fluids using multi-task machine learning}},
  month        = apr,
  year         = 2023,
  publisher    = {Zenodo},
  version      = {1.1.0},
  doi          = {10.5281/zenodo.8072892},
  url          = {https://doi.org/10.5281/zenodo.8072892}
}
```

`wb97xd3.csv` (modified by concatenating the reactant and product SMILES columns with ">>" in between, and retaining only the reaction SMILES and `dE0` property column):
```
@article{spiekermann2022high,
  title={High accuracy barrier heights, enthalpies, and rate coefficients for chemical reactions},
  author={Spiekermann, Kevin and Pattanaik, Lagnajit and Green, William H},
  journal={Scientific Data},
  volume={9},
  number={1},
  pages={417},
  year={2022},
  publisher={Nature Publishing Group UK London}
}
@dataset{spiekermann_kevin_2022_6618262,
  author       = {Spiekermann, Kevin and
                  Pattanaik, Lagnajit and
                  Green, William H.},
  title        = {{High Accuracy Barrier Heights, Enthalpies, and 
                   Rate Coefficients for Chemical Reactions}},
  month        = apr,
  year         = 2022,
  note         = {{v1.0.1 adds InChI strings for the reactant and 
                   product}},
  publisher    = {Zenodo},
  version      = {v1.0.1},
  doi          = {10.5281/zenodo.6618262},
  url          = {https://doi.org/10.5281/zenodo.6618262}
}
```
