# Notebooks
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mpinkert/Notebooks/master)

List of notebooks

## CurveAlign
Notebooks for preparing image files for CurveAlign analysis.

1.) CurveAlign tiling and processing: A notebook which turns a large image into smaller image tiles with associated CurveAlign defined ROIs.

## Deprecated or unfinished
These notebooks are out-of-date or unfinished code that does not provide useful examples.

The deprecated folder also occurs in some sub-folders, where it contains old notebooks relevant to that folder.

## Fiducial Registration
Notebooks that demonstrate how to perform the fiducial phantom registration for the LINK paper, to register between US, SHG, and OCT.

1.) Single registration example: How to obtain a registration transform from a phantom for US and MPM

2.) Apply registration example: How to apply an US or MPM registration determined by the Single registration example notebook

3.) Apply OCT registration: An example of how to register the OCT data given a pre-existing transform.

4.) Resolution and scan rate shifts: This notebook calculates image shifts due to changing the resolution or scan rate in OpenScan.

## ITK
Notebooks that deal with the base Insight Toolkit.

1.) ITKWidgets testing: A notebook for looking at the ITK widget image viewer.

## Polarimetry
Notebooks for processing data for a polarimetry collaboration with the Vitkin lab at the University of Toronto, Canada.

1.) Mueller polarization state registration: This notebook is meant for registering between the 24 polarization state combinations in Mueller registration.

2.) Polarimetry exploratory analysis: Snippets of data analysis for the polarimetry chapter in Michael Pinkert's dissertation.

3.) Polarimetry final analysis: Snippets of data analysis for the polarimetry chapter in Michael Pinkert's dissertation.

## PyImageJ
Notebooks that use the PyImageJ software package to call on ImageJ from Python

1.) IJ macro test: A demonstration of how to use an ImageJ macro in PyImageJ

2.) PyImageJ demonstration: A demonstration of the BigStitcher algorithm using PyImageJ

3.) Rigid registration with pyimageJ: A demonstration of working with windows to use the rigid registration imageJ plugin

## Text Processing
Notebooks for performing text processing.

1.) Move citation position: Take a LaTeX file and move the citation position before or after punctuation, to accomodate changing journal reference styles.

## Ultrasound
Notebooks for processing ultrasound data.

1.) Visualsonics reassembling: A notebook which converts .mats to .tifs, for a specific task of converting Visualsonics output data to tifs for processing.