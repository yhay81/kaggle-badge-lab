# Transparent Linear Coefficients Model

This language-independent model predicts `target` from two numeric features:

```text
target = 3.0 * feature_1 - 2.0 * feature_2 + 5.0
```

The JSON artifact records the feature order, coefficients, intercept, intended use, and limitations. It exactly reproduces every target in `data/linear_relationship_sample.csv`.
