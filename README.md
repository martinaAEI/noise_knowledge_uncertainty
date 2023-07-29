# noise_knowledge_uncertainty
This repository includes python and mathematica notebook to compute fisher matrix and the noise analytical models considering TDI first generation A,E,\zeta.
The mathematica notebook include the test mass and optical metrology noises analytical models plus the TDI coefficients that are used to compute the transfer fuctions for gravitational waves
There are also 2 cvs files that contains the numerical evaluations of the transfer functions. The files are input of the python notebook that compute the fisher matrix. At the beginning of the python notebook there are lines to extract and read those files
The python notebook contrains the fisher matrix in case of 3 TDI channels when considering in the calculation the imaginary and real part togheter. Along with the fisher the code compute a practical case with unequal - fixed arm-length, 4 SGWB such as power law, FOPT, power law with running and gussian bump.  
All the result reported in the code as well as all the functions refer to the article : "Impact of the noise knowledge uncertainty for the science exploitation of cosmological
and astrophysical stochastic gravitational wave background with LISA "
