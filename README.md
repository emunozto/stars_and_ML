This is part of the research project that I developed as a grad student. It focuses on Be Stars and the use of Machine Learning to produce meaningful insigths.
The data are free and can be obtained obtained from [BeSOS](http://besos.ifa.uv.cl/).
## Be-stars
Be-stars are a special type of B-stars that are rapidly rotating and have a ring surrounding its equator (decretion circumstrellar disk). 
The mechanism responsible for the disk material ejection from the central star is not well understood. 
This circumstellar disk produces emission lines and the strongest are the Balmer lines; besides Hydrogen lines there are many FeII emission lines that also
originate in the disk. The H-alpha is the brightest (red) visible spectral line in the Balmer Series. Profile line properties are related with the structure, 
geometry and dynamics of the disk. This project used ML algorithms to study Be-spectral lines, and to product insights of the disk dynamics, as well to understand the region where each type of profile was generated.
**Discussion: ** Separate spectral lines in two categories, the ones produced by stars with disk and those produced by stars without disk. For stars with disk, group them in three types, pole on, edge on and intermediate inclination.

Use Complete Linkage Agglomerative Hierarchical Clustering (unsupervised learning algorithms) to find native groups and use a bottom up approach (ascending) to build hierarchical cluster trees (dendrograms). Elbow method and Silhouette coefficient were used to assess the optimal number of clusters.
**Conclusion:**The H-alpha lines produced by the disk are double peak, the peak separation is strongly related to the disk inclination respect to the plane of observation.
