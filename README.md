# Neural Activity Regression

I used this project to practice regression on a public neural activity dataset and compare several model families after basic preparation and dimensionality reduction.

## Dataset

The notebook downloads `stringer_spontaneous.npy` from the public OSF link on first run and stores it in `data/`. The `.npy` file is intentionally ignored by git because it is generated locally and can be downloaded again.

## Structure

- `codes/Neural_Activity_Regression.ipynb` keeps the cleaned regression notebook.
- `data/` is the local download location for the public dataset.

## Method

The notebook inspects the neural response, running speed, pupil, and behavioral SVD arrays, prepares the regression inputs, and compares linear, regularized, kernel, tree-based, ensemble, and KNN regressors.

## Run

Install `numpy`, `pandas`, `matplotlib`, `scipy`, `scikit-learn`, `requests`, and `jupyter`, then open `codes/Neural_Activity_Regression.ipynb` from the project folder. The first run needs an internet connection to download the dataset.

## Limits

The dataset is much larger than the other course notebooks, so reruns can take longer. I kept the raw downloaded array out of the repo to avoid making the repository unnecessarily heavy.
