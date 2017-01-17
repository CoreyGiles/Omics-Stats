# Omics-Stats
Double cross validation and permutation tests for 'omics datasets

'Omics methods often generate large datasets, measuring hundreds or thousands of variables in each sample. While this is attractive from a biological perspective, situations were there are more variables than subjects are troublesome in a statistical sense. Fortunately, there are solutions available to overcome these issues, however they must be used with appropriate caution. Here, I lay out several robust approaches for statistical analysis of large 'omics datasets.

Two principle methods are required to appropriately assess megavariate data: regularization and cross validation. Both methods offer an opportunity for generalization of a model - that is, to avoid overfitting and improve predictions on unseen data.

Presented within, several regularization techniques are demonstrated within a cross validation framework. Double cross-validaiton and permutation tests are also implemented.
