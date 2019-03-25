# KMO and Bartlett Tests in Python

- Bartlett Sphericity Test

Exploratory factor analysis is only useful if the matrix of population 
correlation is statistically different from the identity matrix. 
If these are equal, the variables are few interrelated, i.e., the specific 
factors explain the greater proportion of the variance and the common factors
are unimportant. Therefore, it should be defined when the correlations 
between the original variables are sufficiently high. 
Thus, the factor analysis is useful in estimation of common factors. 
With this in mind, the Bartlett Sphericity test can be used. The hypotheses are:

- H0: the matrix of population correlations is equal to the identity matrix
- H1: the matrix of population correlations is different from the identity matrix.


- KMO Test

KMO is a measure of the adequacy of sampling “Kaiser-Meyer-Olkin" and checks 
if it is possible to factorize the main variables efficiently.
The correlation matrix is always the starting point. The variables are more or
less correlated, but the others can influence the correlation between the two 
variables. Hence, with KMO, the partial correlation is used to measure the 
relation between two variables by removing the effect of the remaining variables.

