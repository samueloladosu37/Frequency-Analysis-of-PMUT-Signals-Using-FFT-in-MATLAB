
# Frequency Analysis of PMUT Signals Using FFT in MATLAB

## Introduction

This project involves the experimental analysis of Piezoelectric Micromachined Ultrasonic Transducers (PMUTs) by acquiring and processing their transmitted and received signals. The data was collected using an oscilloscope, capturing the oscillatory response of the PMUT system over time. Fast Fourier Transform (FFT) techniques were implemented in MATLAB to analyze the frequency components of these signals.

## Signal Acquisition

- The PMUT device was excited under a probe station in a non conductive liquid.
- The response signals were measured and recorded using an oscilloscope.
- Time-domain signals for both transmitted and received waves were recorded.

## Data Processing

- Time-domain signals were imported into MATLAB for analysis.
- FFT was applied to convert the signals from the time domain to the frequency domain.

## Preprocessing

- Raw data was cleaned to remove unwanted noise.
- Signals were normalized as needed to prepare for FFT.

## Fourier Transform Implementation

- MATLAB's built-in `fft` function was used to compute the frequency spectrum.
- Frequency bins were calculated based on the sampling rate.
- Magnitude spectra were plotted to visualize dominant frequencies.
- Peak detection was performed to identify significant resonant frequencies.

## Significance

- Characterization of the resonant frequency and bandwidth of the PMUT device.
- Understanding frequency peaks is crucial for applications in ultrasonic imaging, sensing, and communication.
- Provides a methodology for further signal processing and system optimization.

---

## Author

**Samuel Oladosu**  
[samueloladosu37@gmail.com] 


