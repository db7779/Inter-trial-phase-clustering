# Inter-trial-phase-clustering (ITPC) calculation using Python
This repository provides a function that calculates ITPC of EEG data, making use of complex Morlet wavelet convolution for the time-frequency analysis, and subsequently averages ITPC for a time interval. 
A second function for region of interest (ROI) averaging (across channels of the predefined ROIs) is also provided.

In this example, data is contained in matlab files, with fields specifying the 3 conditions, 64 channels, trials and subjects.
