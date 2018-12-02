# APOVERTY: Stata module to compute poverty measures


## Abstract

     apoverty computes a series of poverty measures based on the (welfare) distribution described by varname. It is a revised and upgraded version of poverty published by Philippe Van Kerm.

	The poverty measures that can be computed by

     - headcount ratio extreme poverty hratio aggregate poverty gap
     - poverty gap ratio income gap ratio Watts index
     - Sen index Takayama index Thon index,

	and series of Foster, Greer and Thorbecke indices with parameters :
     - 0.5, 1.5, 2, 2.5, 3, 3.5, 4, 4.5, 5
     - Clark et al. indices with parameters :
     - 0.1, 0.25, 0.5, 0.75, 0.9

     The poverty line is either directly specified by the user or computed relative to the median of varname (half or two-third), see under "options" below. The extreme poverty line is directly speciefied as half of the poverty line used in the exercise.


## Suggested Citation
[Joao Pedro Azevedo, 2006. "APOVERTY: Stata module to compute poverty measures," Statistical Software Components S456750, Boston College Department of Economics, revised 13 Apr 2007.](https://ideas.repec.org/c/boc/bocode/s456750.html)

### Handle: RePEc:boc:bocode:s456750 

### Keywords
poverty; headcount; Sen index; income gap ratio; Greer-Thorbecke index; Watts index; poverty gap

### Note: 
This module should be installed from within Stata by typing "ssc install apoverty". Windows users should not attempt to download these files with a web browser.

