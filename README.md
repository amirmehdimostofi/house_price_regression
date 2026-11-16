# House price regression

This repository is set up to predict house sale prices from property features. The modelling work is still in progress.

## Data

- `data/train.csv` — 1,460 properties and 81 columns, including `SalePrice`
- `data/test.csv` — a matching holdout file

Features cover lot size, zoning, neighbourhood, building type and quality, year built, living area, bathrooms, garage, and sale conditions.

## Method

`main_file.ipynb` currently loads the training data and inspects its shape and columns (1,460 rows × 81 columns). It does not yet train or evaluate a model. The notebook also points at a local path on one machine; the CSVs in `data/` are the copies that belong with this repo. `mainfile.py` is empty.

## Next steps

Point the notebook at `data/train.csv`, then add cleaning, a train/validation split, regression models, and error metrics (for example RMSE, MAE, and R-squared) before treating this as a finished portfolio piece.

```bash
jupyter notebook main_file.ipynb
```
