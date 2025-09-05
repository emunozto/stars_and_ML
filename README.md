This work was inspired by the research project I conducted during my graduate studies. The focus is on Be stars and the application of machine learning techniques to extract meaningful insights into their spectral properties and disk dynamics. The primary dataset was obtained from Kitt Peak Observatory, while additional publicly available data can be accessed through the Be Star Spectra (BeSOS) database  [BeSOS](http://besos.ifa.uv.cl/).
## Be-stars

**Introduction**  

Be stars are a peculiar class of rapidly rotating B-type stars surrounded by a circumstellar decretion disk concentrated along the stellar equator. The mechanism that drives the ejection of material from the stellar surface into this disk remains uncertain, though rapid rotation is believed to play a key role. The disk produces prominent emission lines, most notably from the Balmer series of hydrogen. In addition, numerous Fe II emission lines originate in the same region. Among the Balmer lines, H-\alpha is the brightest feature in the visible spectrum. The shape and properties of these line profiles provide direct insight into the disk’s structure, geometry, and dynamics.

Spectra can be categorized into two broad groups: stars with disks and stars without disks. For stars with disks, spectra were further subdivided according to inclination angle relative to the observer—classified as pole-on, edge-on, or intermediate.

This project applied machine learning algorithms to analyze Be-star spectral lines, with the dual goal of characterizing disk dynamics and identifying the regions responsible for generating different line profiles. A first step was to categorize spectra into two broad groups: stars with disks and stars without disks.


**Metodology**  

Unsupervised clustering was then performed using Complete Linkage Agglomerative Hierarchical Clustering, a bottom-up (ascending) approach that builds hierarchical cluster trees (dendrograms). To determine the optimal number of clusters, both the Elbow method and the Silhouette coefficient were employed as evaluation metrics.


**Conclusion**  

The clustering analysis revealed natural groupings consistent with physical expectations of disk geometry. Double-peaked H-α emission profiles emerged as a signature of circumstellar disks. The separation between the two peaks was found to correlate strongly with disk inclination: smaller separations for nearly pole-on systems and larger separations for edge-on orientations. These results demonstrate that unsupervised methods can recover meaningful physical distinctions directly from spectral data.
The H-alpha lines produced by the disk are double peak, the peak separation is strongly related to the disk inclination respect to the plane of observation.


**Apendix**  

B-type stars are hot, massive, and luminous stars belonging to spectral type B. Their effective temperatures range from 10,000–30,000 K, significantly higher than the solar value (~5,800 K), and they therefore exhibit a blue or blue-white color.

These stars typically have masses between 2–16 M☉ and radii several times that of the Sun. Their bolometric luminosities span a wide range, from 10² to 3×10⁴ L☉, placing them among the most radiant main-sequence and evolved stars.

Representative Examples

Rigel (β Orionis, B8 Ia): a blue supergiant.

Spica (α Virginis, B1 III–IV): a giant/subgiant system.

Achernar (α Eridani, B6 Vep): a Be star exhibiting emission lines from a circumstellar decretion disk.

Astrophysical Significance

B-type stars exert a strong influence on their environments through intense ultraviolet radiation and high-velocity stellar winds, which shape the surrounding interstellar medium. Their relatively short main-sequence lifetimes (~10–100 Myr) reflect their high masses and rapid fuel consumption. The most massive B stars evolve into core-collapse supernovae, contributing to chemical enrichment and compact object formation. Subclasses include Be stars, characterized by rapid rotation and disk-related emission features, and β Cephei variables, which exhibit pulsational instabilities driven by the κ-mechanism.
