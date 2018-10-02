# Python wrappers for ease of use for lab stuff

## Built With

vim :^)

## Latest Version

New versions of the functions will be available as soon as they're pushed. This might take up to a few days, depending on the internet connection used.

## Authors

* **Some weeaboo**
* **That weeaboo's waifu**

## Acknowledgments

Hat tip to my m'lady

## Dependencies

Most functions only require basic Python and numpy. Linear regression additionally requires matplotlib.pyplot and scipy.optimize. Ideally, one should also have uncertainties installed. The import function also imports Pandas.

## Functions

### linreg

Simple linear regression function that utilizes outputs from scipy.optimize's curve_fit and plots the result with matplotlib.pyplot's plot. Uses a*x+b as its fit function. Use unumpy=True if the xarr and yarr arrays are uarrays.

linreg(xfit,xarr,yarr,markeraus='-',grenz=True,markergrenz='--',color='orange',labelaus='Lineare Regression',labelgrenz=None,unumpy=False,first=0,last=-1,xnum=100,xfitrestrictl=None,xfitrestrictr=None,yfitrestrictl=None,yfitrestrictr=None):

### mean

Simply calculates the sum of an array over its length.

### omega

Turns a periodic time into angular frequency.

### a, b, s, Da, Db

Calculate linear regression by hand. Requires x and y inputs.

### t

Find out if values are good or not. Optimal values are t < 2.

### s_t

Calculate uncertainty for certain devices. I don't know what this is for exactly.

### impfunc

Imports ufloat, unumpy as unp, numpy as np, matplotlib.pyplot as plt, curve_fit from scipy.optimize, and pandas as pd.

## Installation

$ pip install .

You can also just put this in the right directory.