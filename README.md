<!-- README.md is generated from README.Rmd. Please edit that file -->
maxentmodelselectr
==================

**maxentmodelselectr** is an R package under development (pre-release). The contents of this repository are not currently intended for public use.

### Description

Training, selecting, and evaluating maximum entropy (Maxent) distribution models. This package provides tools for user-controlled transformation of explanatory variables, selection of variables by nested model comparison, and flexible model evaluation and projection. The methods implemented here are based on the strict maximum likelihood interpretation of maximum entropy modelling (Halvorsen, 2013, Halvorsen et al., 2015).

The predecessor to this package is the MIA Toolbox, which is described in detail in Mazzoni et al. (2015).

### System Requirements

The maximum entropy algorithm utilized in this package is provided by the MaxEnt Java program (Phillips et al., 2006). This software is freely available, but may not be distributed further. Therefore, you must download the MaxEnt program (v3.3.3k) from <https://www.cs.princeton.edu/~schapire/maxent/>, and place the 'maxent.jar' file in the 'java' folder of this package. This folder can be located by the following R command: system.file("java", package = "maxentmodelselectr").

You must have a Java Runtime Environment (JRE) installed on your computer for the MaxEnt program to function. You can check if you have Java installed, and download it if necessary, from <http://java.com/download>.

### References

Halvorsen, R. (2013) A strict maximum likelihood explanation of MaxEnt, and some implications for distribution modelling. Sommerfeltia, 36, 1-132.

Halvorsen, R., Mazzoni, S., Bryn, A. & Bakkestuen, V. (2015) Opportunities for improved distribution modelling practice via a strict maximum likelihood interpretation of MaxEnt. Ecography, 38, 172-183.

Mazzoni, S., Halvorsen, R. & Bakkestuen, V. (2015) MIAT: Modular R-wrappers for flexible implementation of MaxEnt distribution modelling. Ecological Informatics, 30, 215-221.

Phillips, S.J., Anderson, R.P. & Schapire, R.E. (2006) Maximum entropy modeling of species geographic distributions. Ecological Modelling, 190, 231-259.
