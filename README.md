# CaPTk Histogram Matching

Flywheel gear that implements [CaPTk's application for histogram matching](https://cbica.github.io/CaPTk/preprocessing_histoMatch.html) (image intensity normalization based on reference image).

NOTE: images must be co-registered

## Dependencies:
- CaPTk (gear uses the existing Docker container 2021.03.29)

## Required inputs:
- Input image
- Reference image

## Optional configuration:
- histogram bins
- histogram quantiles
- output file name (defaults to output.nii.gz)
