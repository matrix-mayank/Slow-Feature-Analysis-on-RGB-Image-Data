# Slow-Feature-Analysis-on-RGB-Image-Data
This repository documents an implementation of Slow Feature Analysis on sample land tiles from UK's Peak District National Park, that was performed during Alan Turing Institute's Data Study Group in May 2023. 

The Slow Feature Analysis algorithm was developed by C. Wu et al. and here goes its citation: **C. Wu, B. Du, and L. Zhang, “Slow feature analysis for change detection in multispectral imagery,” IEEE Trans. Geosci. Remote Sens., vol. 52, no. 5, pp. 2858–2874, 2014.** Due credit goes to the authors of this study.

In the Jupyer notebook that you will find in this repository, the following steps are performed:

1. Ten year apart versions of 4 sample tiles (SK1091, SK0961, SK2096, SK0987) from UK's Peak District National Park are imported and downscaled using the _rasterio_ package in Python.
2. Tile pixel values are converted to _numpy_ arrays.
3. Slow feature analysis is performed on the arrays.
4. The resulting binary change maps are plotted.

**Full report** can be accessed here: 

**Sample results**:

