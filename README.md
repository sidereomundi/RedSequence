# RedSequence Notebook

This repository contains a Jupyter notebook (`red_sequence.ipynb`) used to analyse the red sequence of galaxies in COSMOS and SPT cluster datasets. The notebook is designed for execution in a Google Colab environment.

The assignment text is available in [photo_z_obs_cosmology.md](photo_z_obs_cosmology.md).

## Dependencies

The notebook installs and uses the following key Python packages:

- `emcee`
- `pygtc`
- `astropy`
- `numpy`
- `matplotlib`
- `scipy`
- `tqdm`

## Data files

FITS files containing COSMOS, DES and SPT data must be accessible from the runtime. In the original notebook these files are loaded from Google Drive paths such as:

```
/content/drive/My Drive/ObservationalCosmology/Photo-z/cosmosM.fit
/content/drive/My Drive/ObservationalCosmology/Photo-z/sptclust.0.60.fits
/content/drive/My Drive/ObservationalCosmology/Photo-z/SPTpol_500d_catalog_tablevOct3.fits
```

Ensure you have these data files available in a location that your environment can read (e.g. mounting Google Drive when using Colab).

## Running the notebook

1. Open the notebook in Jupyter or Google Colab.
2. Execute the first code cell to install dependencies and mount Google Drive if required.
3. Make sure the FITS files above are present at the specified paths.
4. Run the remaining cells to perform the red-sequence analysis.

