# Proteomics

![Status](https://img.shields.io/badge/status-alpha-red)
![DOI](https://img.shields.io/badge/DOI-in__progress-blue)

Proteomics analysis using:
1. Parsing mzML MS data using [pymzML](https://github.com/pymzml/pymzML)
2. Handling proteomics data with [Pyteomics](https://github.com/levitsky/pyteomics)
3. Analysis of proteomics and metablomics data with [pyOpenMS](https://pyopenms.readthedocs.io/en/release-3.5.0/)
4. Reading manufacturer raw formats with [multiplierz](https://github.com/BlaisProteomics/multiplierz)
5. Processing and visualization of MS2 spectra using [spectrum_utils](https://github.com/bittremieuxlab/spectrum_utils)
6. Analysis of (phopho)proteomics data with [PaDuA](https://padua.readthedocs.io/en/latest/)
7. Processing and visualization of LC-TIMS-Q-TOF data with [AlphaTims](https://github.com/MannLabs/alphatims)
8. Annotation of proteomics data at peptide level with [AlphaMap](https://github.com/MannLabs/alphamap) etc.

Total Ion Chromatogram (TIC) and Base Peak Intensity (BPI)  |  Extracted Ion Chromatogram (XIC)
:-------------------------:|:-------------------------:
![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/TIC.svg)  |  ![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/XIC.svg)

2D MS1 precursor map  |  2d MS1 ion mobility heatmap
:-------------------------:|:-------------------------:
![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/MS1_map.png)  |  ![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/bokeh_plot2.png)

MS2 (MS/MS) spectrum |  Mirrored MS2 spectrum
:-------------------------:|:-------------------------:
![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/custom_image(2).svg)  |  ![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/custom_image(3).svg)

Extracted Ion Chromatograms (XIC)  |  Ion mobility heatmaps
:-------------------------:|:-------------------------:
![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/custom_image2.svg)  |  ![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/ion_mob_hm.png)

Peptide coverage map  |  Lollipop plot (PTM/site plot)
:-------------------------:|:-------------------------:
![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/newplot.png)  |  ![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/newplot(2).png)

Differential peptide coverage map
:-------------------------:
![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/newplot(1).png)

Intensity histogram  |  Protein rank plot
:-------------------------:|:-------------------------:
![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/newplot2.png)  |  ![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/newplot8.png)

Pairwise correlation plot  |  Sample correlation matrix (heatmap)
:-------------------------:|:-------------------------:
![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/newplot3.png)  |  ![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/newplot4.png)

Volcano plot (square cutoffs)  |  Volcano plot (nonlinear cutoffs)
:-------------------------:|:-------------------------:
![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/newplot6.png)  |  ![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/newplot5.png)

Enrichment analysis (dot plot)
:-------------------------:
![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/newplot7.png)

PCA scatter plot  |  3D PCA loading plot
:-------------------------:|:-------------------------:
![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/newplot(4).png)  |  ![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/newplot(7).png)

PCA loading plot  with vectors  |  PCA loading plot  |  Scree plot
:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/newplot(5).png)  |  ![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/newplot(6).png)  |  ![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/newplot(8).png)

t-SNE projection  |  UMAP projection
:-------------------------:|:-------------------------:
![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/newplot(9).png)  |  ![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/newplot(10).png)

Protein-Sample Heatmap  |  Protein-Protein Heatmap
:-------------------------:|:-------------------------:
![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/newplot(12).png)  |  ![](https://github.com/hasanwraeth/Proteomics/blob/main/fig/newplot(13).png)


## Changelog
### - 2026-08-23
- **Updated:** Scripts updated in line with new packages due to lack of support from legacy packages.
