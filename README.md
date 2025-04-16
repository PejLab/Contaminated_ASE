# Contaminated ASE

[![DOI](https://zenodo.org/badge/966400428.svg)](https://doi.org/10.5281/zenodo.15226466)

## Data Production Methods
This Dataset comprises of Synthetically Contaminated ASE Data from 40 LCL cell-line samples from the GEUVADIS Consortium. ASE was produced by spiking in a set proportion of reads (identified by the filename <contamination_in_percent>.csv) from contamination sample NA19159. ASE was produced at the variant level following best practice [protocols](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-015-0762-6). 

## Data Structure
The xz archive contains file <contamination>.csv where each file represents ASE data from each of the 40 samples at that contamination percentage. Rows in the file correspond to Gene IDS (idenitified by ENSEMBL ID) and column names represent the various sample IDS. 

