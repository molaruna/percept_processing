# percept_processing

This code processes JSON files for streamed neural data using Medtronic's Percept PC neurostimulator
with BrainSense Technology for time-series and spectral analyses. 

## Getting started
This code uses the current version of Python on Google Colab. When written, this version was Python 3.6.9. 

## Data
Neural electrophysiological data are derived from the BrainSense Percept PC neurostimulator (Medtronic). 
You can request anonymized Percept data from me.

## Analysis
* For the time-series plots, voltage data from the neural sensing channel(s) and stimulation amplitude data from the stimulating contact(s) are visualized.
* For the power spectral density analysis, time-domain data is converted into the frequency domain by computing the power spectral density with a hann windowing function, and spanning frequencies with a bin width of 1Hz until the Nyquist frequency is reached.

## License
This software is open source and under an MIT license.
