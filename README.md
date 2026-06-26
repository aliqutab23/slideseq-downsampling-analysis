# Slide-seq Downsampling Analysis

This repository contains a Python script developed from my research experience at the Broad Institute of MIT and Harvard.

The script analyzes downsampled Slide-seq summary outputs by filtering matched barcodes, calculating transcript counts across barcode quantiles, fitting an exponential model with SciPy, and generating plots comparing observed and predicted transcript recovery.

## What the script does

- Reads matched expression summary files and downsampled summary files
- Filters barcodes to matched barcodes
- Calculates average transcript counts for top 20%, 40%, 60%, 80%, and 100% barcode groups
- Fits an exponential model using SciPy least-squares optimization
- Generates a plot of observed and predicted transcript recovery across downsampling ratios

## Tools used

- Python
- NumPy
- SciPy
- Matplotlib
- argparse
- pathlib

## Note

This repository includes the analysis script only. Raw research data and internal files are not included.
