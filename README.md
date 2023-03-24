# exoplanet_clustering
STAT 541 Project: Exoplanet Clustering  

Project to find significant clusters of exoplanets based on their spectroscopy signature. End results should have a number of distinct planets types (cluster centers).  

Tasks:  
1. Exoplanet spectroscopy research  
  a) Need to determine what groups of wavelengths suggest about the atmosphere (e.g. oxygen, nitrogen, etc)  
  b) Recommend a bucket size for grouping wavelengths, should be aparent after doing 1a).  
2. transform data for clustering  
  a) Each line is a significant wavelength by planet. Data will need to be formatted to have one unique line for each planet, with their significant wavelengths sorted into buckets (might need exoplanet research to be done to determine significant buckets).  
  b) data may need cleaning and handling of null values.  
3. clustering and scoring  
  a) cluster using different, number of clusters, algorithms, and parameters.  
  b) score each algorithm using multiple metrics.  
  c) might need to do dimention reduction, but need to understand how to interpret results.  
  
Extra:  
 
4. Do a nonparametric best fit model of cluster centers.  
5. Animate cluster centers (the typical exoplanet by cluster).  
