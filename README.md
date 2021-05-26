# Woolly-Monkey-GLM
Code for a Bayesian GLM for the common woolly monkey (Lagothrix lagothricha). 

This repository contains the code for creating a Bayesian generalized linear model (GLM) associating a specified extent with each occurrence point. The code is written so that it is useable with any presence/absence data and raster layers, although the original use and results were reported at the American Society of Mammalogists 2021 Conference (see abstract below).  The code depends on the R packages 

All code is provided for educational and research purposes only.

Ariek Barakat Norford

Abstract: Species distribution models (SDMs) are a useful tool for understanding past, current, and future distributions of species based on their ecological niche.  The main assumption of SDMs is that the environmental conditions in which a species is found at one point in time and space are representative of its niche, while all other geographic locations are not.  For highly mobile animals, considering the conditions near this presence point may improve these models.  To test this, we used a Bayesian generalized linear model (GLM) with uninformative priors to regress the probability of occurrence of the common woolly monkey (Lagothrix lagothricha) to environmental covariates measured either as an average in a buffer region around the occupancy data (presences and target group absences) at three biologically informed scales – minimum home range size (radius=600m), daily travel length (radius=1km), and maximum home range size (radius=1.5km) – or with no buffer region.  We modeled occurrence at 4 scales, … The model at the minimum home range scale performed better in terms of F1 (0.33 vs. 0.30), which measures precision and recall, but worse for AUC (0.52 vs. 0.53), which measures sensitivity and specificity.  The daily travel distance was best in terms of AUC (0.55).  Scale may have little influence on models of L. lagothricha, but future studies should compare the effect of scale in species with different home range sizes and daily travel distances to determine broader patterns.

