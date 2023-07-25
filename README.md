# stat403_project

- Preprocessed a heart attack disease dataset by removing null values to obtain 304 data samples
- Conducted EDA using KDE to examine distribution of continuous data and contingency table for categorical data
- Calculated correlation matrix to select features whose correlation score less than 0.7 for training
- Selected best multinomial logistic regression which achieved 0.85 F1 score with 8 features using LOO cross-validation
- Bootstrapped 10,000 samples to construct 95% confidence interval to estimate uncertainty of significant coefficients
