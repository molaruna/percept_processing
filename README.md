# percept_processing

This code processes JSON files for streamed neural data using Medtronic's Percept PC neurostimulator
with BrainSense Technology for time-series and spectral analyses. 

## Getting started
This code uses the current version of Python on Google Colab. As of February 2022, this version is Python 3.6.9. 

## Data
Neural electrophysiological data are derived from the BrainSense Percept PC neurostimulator (Medtronic). 
Anonymized Percept data are available on the [Rune Labs platform](https://app.runelabs.io/patients).
You can request access from me.

## Analysis
For the power spectral density analysis, time-domain data is converted into the frequency domain by computing the power spectral density with a hann windowing function, and spanning frequencies with a bin width of 1Hz until the Nyquist frequency is reached.

## License
This software is open source and under an MIT license.
