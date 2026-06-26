# Logistic Regression for Diabetes Prediction – From Scratch vs Scikit-learn

Compare a hand-implemented Logistic Regression (gradient descent + fmin_tnc) with scikit-learn's version on the PIMA Indians Diabetes dataset.

## Dataset

- Source: PIMA Indians Diabetes Dataset
- Features: Glucose, BMI, Age, Blood Pressure, etc.
- Target: Outcome (0 = no diabetes, 1 = diabetes)

## Custom Implementation

- Sigmoid activation
- Log-loss (binary cross-entropy)
- Gradient descent using scipy.optimize.fmin_tnc
- Prediction with probability threshold (0.5)

## Results

| Model | Accuracy |
|-------|----------|
| Custom Logistic Regression | ~78.26% |
| Scikit-learn Logistic Regression | ~77.73% |

## Author

Fatma Abdullah

## License

Open source
