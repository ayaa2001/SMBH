# SMBH

## Introduction and Motivation

The mass_luminosity_function is a Python package for calculating the mass-luminosity function of quasars. The mass-luminosity function is an important statistical relationship between the masses of supermassive black holes (SMBHs) at the centers of galaxies and the luminosities of the quasars

## Installation

The package is installable on Python 3.x and can be installed using:

```pip install SMBH```

## Use Example

The mass_luminosity_function (SMBH) package includes some functions, to load the data and then calculate and plot the mass luminosity function for quasars to know its evolution over cosmic time. 
Here's an example of how to use it:

```
from SMBH import entery
from SMBH import classify

# Load observational data
data = entery(RA,DEC,Z,M,LB)

#classify the quasars to subsets at different redshift and masses
subsets= classify(data)

# Plot the mass-luminosity function
```

## Description of the functions
```Entery``` function

Take in the input variables redshift, mass, and luminousity.

```Classify``` function

```Mmean``` function

```Bmean``` function
