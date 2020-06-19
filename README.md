# SSH Mapping Data Challenge 2020a

This repository contains codes and sample notebooks for downloading and processing the ssh-mapping data challenge.

* needs a short description of the challenge
* a short acknowledgement to WeatherBench?

[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/ocean-data-challenges/2020a_SSH_mapping_NATL60/master)

## Leaderboard

| Method | SSH RMSE | Spectral score | Notes | Reference |
|--------------------|----------------------------------|----------------------------|----------------------|------------------|
| Statistical interpolation |  xx  |  YY |  Covariances not optimized |  quickstart demo  |
 
 ## Quick start
 You can follow the quickstart guide in [this notebook](https://github.com/ocean-data-challenges/2020a_SSH_mapping_NATL60/blob/master/quickstart.ipynb) or lauch it directly from <a href="https://binder.pangeo.io/v2/gh/ocean-data-challenges/2020a_SSH_mapping_NATL60/master?filepath=quickstart.ipynb" target="_blank">binder</a>.

## Download the data
The data are hosted... and are distributed with the following structure:

## Baselines and evaluation

```
 **IMPORTANT:** The format of the predictions file is a
  NetCDF dataset with dimensions `[init_time, lead_time, lat, lon]`. Consult the notebooks for examples. You are
   stongly encouraged to format your predictions in the same way and then use the same evaluation functions to ensure
    consistent evaluation.
```
### Baselines
The baselines are created using Jupyter notebooks in `notebooks/`. The SSH reconstructions are saved as a
 NetCDF file in the **ADJUST** `predictions` directory of the dataset. 
 
### Statistical interpolation baseline
An example of how to load the data and run a statistical space-time interpolation is given in **ADJUST** `notebooks/3-cnn-example.ipynb`. 
  
### Evaluation
