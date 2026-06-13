# Module-3_Week-6
Week-6 coding challenge 

You are given a medical diagnostics dataset containing multiple correlated numerical features with possible extreme values caused by measurement errors.
Your task is to analyze the dataset and study how outliers affect statistical and probabilistic assumptions. Use the scikit-learn load_breast_cancer() dataset. Use only numerical features, randomly sample 300 rows, and ignore the target variable.

1. Statistical Analysis
• Compute mean, median, variance, standard deviation, skewness, and
kurtosis.
• Identify features that strongly deviate from normality and visualize their
distributions.

3. Linear Algebra
• Standardize the data using matrix operations.
• Compute the covariance matrix manually (do not use .cov()).
• Verify symmetry and perform eigen decomposition.
• Identify the top variance directions using eigenvalues.

5. Probability
• Assume a multivariate Gaussian distribution.
• Compute Mahalanobis distance for each observation.
• Convert distances to probabilities using the chi-square distribution.
• Flag observations in the lowest 1% probability region.

4. Outlier Handling
• Detect outliers using Z-score and IQR methods.
• Compare these with Mahalanobis-based outliers.
• Remove multivariate outliers to create a cleaned dataset.

6. Post-Cleaning Analysis
• Recompute covariance matrix and eigenvalues.
• Compare results before and after outlier removal.
Briefly comment on the impact of outliers on variance and Gaussian
assumptions.
