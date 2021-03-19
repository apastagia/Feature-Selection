# Feature-Selection
Machine Learning

1. Variance Threshold:
  The variance threshold is a simple baseline approach to feature selection. It removes all features which variance doesn’t meet some threshold. By default, it removes all 
zero-variance features, i.e., features that have the same value in all samples. We assume that features with a higher variance may contain more useful information, but note that 
we are not taking the relationship between feature variables or feature and target variables into account.
-> The get_support returns a Boolean vector where True means that the variable does not have zero variance.

2. Pearson Correlation:
  A Pearson correlation is a number between -1 and 1 that indicates the extent to which two variables are linearly related. The Pearson correlation is also known as the 
“product moment correlation coefficient” (PMCC) or simply “correlation”.

Pearson correlations are suitable only for metric variables

The correlation coefficient has values between -1 to 1
A value closer to 0 implies weaker correlation (exact 0 implying no correlation)
A value closer to 1 implies stronger positive correlation
A value closer to -1 implies stronger negative correlation
