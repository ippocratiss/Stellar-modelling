# Reproduction Package for the Paper "Dark Matter-Induced Stellar Oscillations"

## Authors
Jeremy Sakstein (<sakstein@hawaii.edu>)  
Ippocratis Saltas (<saltas@fzu.cz>)  

## Software

MESA version 15140 (<http://mesa.sourceforge.net>)   
MESASDK version 20200325 (<http://www.astro.wisc.edu/~townsend/static.php?ref=mesasdk>)   
GFORTRAN GCC version 9.2.0   
GYRE version 7.0   
Python 3.7.3   
Jupyter Notebook version 6.4.12   


## MESA Files

**MESA\_inlist:** MESA inlist used to produce the equilibrium solar model. Should be placed in $MESA\_DIR/star/test\_suit/simplex\_solar\_calibration.

**late\_pre\_zams\_1.0M.mod:** Pre-main-sequence model loaded by MESA\_inlist. Should be placed in $MESA\_DIR/star/test\_suit/simplex\_solar\_calibration.

**solar\_ref\_mesa.mesa:** Pulse data for the equilibrium solar model.

## GYRE Files

**GYRE\_inlist.in:** GYRE inlist used to produce the eigenfrequencies of the equilibrium solar model.

**summary\_mesa.txt:** GYRE summary file.

**detail.l1.n+N.h5:** Tabulated eigenfunctions for the mode with n=1 n=N. 

## Python Files

**V\_rms\_computation.ipynb:** Jupyter notebook that computes the RMS velocity.

**GS98\_OPAL\_CALIBR.txt:** Equilibrium solar model. See V\_rms\_computation.ipynb.

## Citation Policy

If you use any part of this reproduction package for independent work we recommend you cite this paper.
