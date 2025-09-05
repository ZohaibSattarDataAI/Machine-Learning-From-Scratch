# 📐 Orthogonal Matching Pursuit (OMP) — Theory

## Definition
Orthogonal Matching Pursuit (OMP) is a greedy algorithm used for sparse approximation and sparse linear regression. It aims to represent a target signal or dataset as a linear combination of a small subset of features (atoms) from a larger set, updating coefficients through orthogonal projection at each step.

## Explanation
OMP operates by selecting, in each iteration, the feature that has the highest correlation with the current residual (the part of the target not yet explained). Once a feature is selected, it is added to the active set, and the coefficients for all selected features are recomputed via least squares. This orthogonalization step ensures that the residual is perpendicular to the space spanned by the selected features. The process repeats until a stopping condition is met.

The mathematical model solved is:

y = Xw + ε

Where:
- `y`: target vector (observations)
- `X`: dictionary/design matrix
- `w`: sparse coefficient vector
- `ε`: error/noise

**Key steps:**
1. Initialize residual as `y` and active set as empty.
2. Compute correlations of residual with all unused features.
3. Select feature with highest absolute correlation.
4. Add it to the active set.
5. Recompute coefficients using least squares on active set.
6. Update residual.
7. Repeat until stopping condition.

## Applications
- **Signal processing**: Efficient signal reconstruction from limited measurements.
- **Compressed sensing**: Recovering sparse signals with fewer samples than Nyquist rate.
- **Feature selection**: Identifying a small set of important predictors in regression problems.
- **Image processing**: Image compression, denoising, and super-resolution.
- **Machine learning**: Sparse model construction for interpretability and reduced complexity.

## Usage
- Use when the dataset is high-dimensional but the underlying model is sparse.
- Suitable for problems where computation time is critical, and a greedy approach is acceptable.
- Works best when features (columns of `X`) are not highly correlated.

## Advantages (Pros)
- Simple and intuitive to implement.
- Produces a clear, interpretable sequence of selected features.
- Orthogonalization step reduces bias in coefficient estimates.
- Efficient for moderately sized datasets.

## Disadvantages (Cons)
- Greedy nature may lead to suboptimal early choices that cannot be corrected.
- Performance deteriorates with highly correlated features.
- May not perform as well as convex optimization methods (e.g., Lasso) in noisy data.
- Requires a good stopping rule to avoid overfitting.

**References:**
- Tropp & Gilbert (2007). *Signal recovery from random measurements via orthogonal matching pursuit.*
- Pati, Rezaiifar & Krishnaprasad (1993). *Orthogonal Matching Pursuit: Recursive function approximation with applications to wavelet decomposition.*
