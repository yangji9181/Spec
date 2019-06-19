# HINSE
Meta-Graph Based HIN Spectral Embedding

This github repository is under construction.

## Data Preprocessing
Filter DBLP based on Vocab-Label author list
```
python dblp_data.py
```

## Metagraph Instance Matching
Match the metapath/metagraph instances from HIN. One need to specify the dataset flag. You need to install ```wine``` before running the commend!!!
```
python3 submodule.py dblp
```

## Eigenlist Generating

Calculated eigenvalues and plot the final eigenvalue plots using python. The 2nd argument is the dataset name, and the 3rd and 4th arguments are 
```
python3 eigen_cal_all.py dblp
```

## Autoencoding Data
