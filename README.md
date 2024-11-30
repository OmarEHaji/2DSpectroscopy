# 2D Spectroscopy Non-Linear Regression Analysis  : Gaussian and Lorentzian Fits


## Overview 

This repo contains a Python projects for analysing 2-Dimensional Spectroscopy signal data by non-linear regression

## Key features 
- **Data Handling**: Reads spectroscopy data from a CSV file containing 3 columns: Pump, Probe and Signal
- **Curve Fittign**: Uses non-linear regresion for fit - least sqaures approach
	- 2D Gaussian 
	- 2D Lorentzian
- **Residual Analysis**: Calcualates residuals and evaluates model by RSS calculation
- **Visualisation**:
	- 2D scatter and contour plots - signal and residual contours
	- 3D Surface plots of both functions over the raw spectroscopy data

## Usage
**Dependencies**
  This project uses the following libraries:
  - numpy
  - scipy
  - matplotlib
  - pandas
  - mpl_toolkits

  Install dependencies using :
  '''bash
  pip install [relevant libaries]
