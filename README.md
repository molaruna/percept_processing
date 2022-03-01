# percept_processing

This code processes JSON files for streamed neural data using Medtronic's Percept PC neurostimulator
with BrainSense Technology for time-series and spectral analyses. 

## Getting started
This code uses the current version of Python on Google Colab. Currently, this version is Python 3.6.9. 

## Data
Neural electrophysiological data are derived from the BrainSense Percept PC neurostimulator (Medtronic). 
Anonymized Percept data are available on [Google drive](https://drive.google.com/drive/folders/1TzThqu1ECBqDxZUbRWec5stw4LztcuOy?usp=sharing) and [Rune Labs](https://app.runelabs.io/patients).
You can request access from me.

## Analysis
For the power spectral density analysis, time-domain data is converted into the frequency domain using `welch()` 
with a hann window, spanning frequencies in a 1Hz sampling resolution until the Nyquist frequency is reached.

## License
This software is open source and under an MIT license.
