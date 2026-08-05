# Kaggle Badge Lab

Small, reproducible notebooks for learning practical machine learning workflows on Kaggle.

## Included notebook

- `00_reproducible_regression_quickstart.ipynb` generates a synthetic regression dataset, creates a deterministic train/test split, trains a linear model, reports evaluation metrics, and verifies reproducibility.
- `data/linear_relationship_sample.csv` is a compact, deterministic regression sample suitable for tutorials, smoke tests, and documentation examples.

The notebook is intentionally self-contained: it downloads no data and uses no personal or sensitive information.

## Run locally

The notebook uses Python with NumPy, pandas, scikit-learn, and Matplotlib. These packages are available in Kaggle's standard Python environment.

## License

MIT
