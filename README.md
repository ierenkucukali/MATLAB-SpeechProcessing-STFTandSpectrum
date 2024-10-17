# MATLAB-SpeechProcessing-STFTandSpectrum
### Project Overview
The primary focus of this project is to analyze time-varying signals using Short-Time Fourier Transform (STFT) and generate spectrograms to visualize the frequency content of the signals over time.

Key features include:

STFT Computation: Breaking down the signal into overlapping windows and performing the Fourier Transform on each window.
Spectrogram Generation: Visualizing the frequency content of signals over time using MATLAB's built-in functions and custom code.
Windowing: Exploring the effect of different window types (e.g., Hamming, Hann, Rectangular) on the STFT.
Time-Frequency Analysis: Examining how varying the window length affects the resolution of time and frequency in the spectrogram.
### Requirements
MATLAB R2021a or higher.
Signal Processing Toolbox (optional, if using built-in MATLAB functions like spectrogram).
Instructions
The main file for this project is STFTandSpectrogram_st.mlx, which is a MATLAB live script. This script contains explanations and commands to perform STFT and generate spectrograms.

Key Sections:
Loading the Signal: Load a pre-recorded or generated time-domain signal.
STFT Computation: Compute the Short-Time Fourier Transform for the signal using different window sizes and overlaps.
Spectrogram Visualization: Plot the spectrogram for different configurations and visualize the effects of changing parameters.
Analysis of Time and Frequency Resolution: Understand how window length and overlap affect the time and frequency resolution.
Functions
The following custom functions are included or referenced in the project:

STFT(): Computes the Short-Time Fourier Transform of a signal.
Plot_Spectrogram(): Plots the spectrogram based on the STFT results.
MATLAB's built-in spectrogram() function for comparison.
### How to Run
Clone or download the repository.
Open MATLAB and navigate to the directory containing the files.
Open the STFTandSpectrogram_st.mlx file in MATLAB.
Execute the live script to see the results and visualize the spectrograms.
Results
Spectrograms: The script will generate spectrograms for different window sizes and types, allowing you to observe how these parameters affect the representation of time and frequency content.
Time and Frequency Resolution: You will observe the trade-offs between time resolution and frequency resolution based on different window parameters.
### License
This project is licensed under the MIT License.
