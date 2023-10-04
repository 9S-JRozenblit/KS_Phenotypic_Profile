# KS_Phenotypic_Profile
Phenotypic profiles for biological data using KS statistics.

This file takes in .xlsx files of biologics data (controls and treatments on same plate) and will output:
(1) Heatmaps of the treatments and the controls (different concentrations)
(2) Heatmaps of features within each treatment
(3) KS statistics between treatment and control
(4) Mahalanobis distance between treatment and control distribution clusters
(5) Kernel Density Estimation

Note that this will take the file path, types of observations looking for within the xlsx file and eliminate features based on outputes of (1) - (5).
