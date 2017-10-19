# CCA

Algorithm implemented for the SyncPy library : https://github.com/syncpy/SyncPy  

This algorithm compares the relationship that two dataset can share.Let X and Y be those datasets.It seeks out for linear projections of the two datasets such that the i^{th} projection of X is maximally correlated with the i^{th} projection of Y.  
The two datasets must have the same number of rows (same sample size) but can have a number of columns(features) that differs.  
For a more complete description of the algorithm see :

     - David Weenink, Canonical correlation analysis
     - Karl Stratos, A Hitchhiker’s Guide to PCA and CCA
     - Alvin C. Rencher, Methods of Multivariate Analysis
     
