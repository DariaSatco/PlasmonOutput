# PlasmonOutput

Here we put the output file with calculated plasmon frequencies for SWNTs with diameter from 0.5 to 2 nm. 
The columns include the following data:

Efermi - Fermi energy in eV

Density of charge means:

![](https://latex.codecogs.com/gif.latex?%5Crho%28E%29%20%3D%20%5Cint_%7B-%5Cinfty%7D%5E%5Cinfty%20DOS%28E%29%20f%20%28E%29%20dE)

n,m are chiral indices ![](https://latex.codecogs.com/gif.latex?%28n%2Cm%29) of SWNT

family is ![](https://latex.codecogs.com/gif.latex?2n&plus;m)

diameter of SWNT is calculated as:

![](https://latex.codecogs.com/gif.latex?d_t%20%3D%20%5Cfrac%7B0.249%20%5Csqrt%7Bn%5E2&plus;m%5E2&plus;nm%7D%7D%7B%5Cpi%7D%20%5Cquad%20%5Ctext%7Bnm%7D)

Ei, Ej are initial and final subbands respectively

Plasmon frequency w_p in eV corresponds to the peak position in absorption spectra (for more details see https://arxiv.org/abs/1811.11451)

branches column is used to mark down different types of plasmons, which we call branch1, branch2, etc.

ratio is defined as: ![](https://latex.codecogs.com/gif.latex?%5Cfrac%7B%20A%28%20%5Comega_%7B%20P_%7Bij%7D%20%7D%20%29%20%7D%7B%5Cmax_%7Bij%7D%20A%28%20%5Comega_%7B%20P_%7Bij%7D%20%7D%20%29%20%7D)

Absorption column contains intensity of the plasmon absorption peak

The data is plotted in Fig. 6 in the paper "Intersubband plasmon excitations in doped carbon nanotubes"
The source code to run calculations is here: https://github.com/DariaSatco/cntabsorpt

If you have any further questions, feel free to contact me by e-mail daria.satco@skoltech.ru
