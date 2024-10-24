# EEG Signal Analysis Using Welch's Power Spectral Density (PSD) Estimation
This project demonstrates how to analyze EEG signals by calculating their Power Spectral Density (PSD) using Welch's method and visualizing the results across different frequency bands (Delta, Theta, Alpha, Beta, Gamma). The project focuses on reading EEG signals from text files, calculating PSD, and performing frequency band analysis on multiple signals.

EEG (Electroencephalography) signals are often analyzed by breaking them down into distinct frequency bands, which can reveal important neural activity. This project provides a script to load EEG signals, calculate their PSD using the Welch method, and analyze the power distribution across the following frequency bands:

- Delta (0.5–4 Hz): Typically associated with deep sleep.
- Theta (4–8 Hz): Linked with drowsiness or meditation.
- Alpha (8–13 Hz): Present during relaxation or closed-eye wakefulness.
- Beta (13–30 Hz): Related to active thinking and problem-solving.
- Gamma (30–60 Hz): Linked to high-level information processing.

## Features
- Loading EEG Signals: Reads EEG signals from .txt files into arrays.
- Welch's Method: Uses the Welch method to estimate Power Spectral Density (PSD) for both signals.
- Frequency Band Analysis: Divides the signal into the main EEG frequency bands and calculates the average power within each band.
- Visualizations: Plots the raw EEG signals, their PSDs, and highlights the power in each frequency band for easy comparison.


## Plots and Output
After running the script, you will see the following outputs:

### 1. Raw EEG Signals:
Plots of the two loaded EEG signals.

### 2. PSD Comparisons:
Plots of the PSD for both signals, computed using Welch’s method.

### 3. Frequency Band Analysis:
Highlighted PSD plots for each frequency band (Delta, Theta, Alpha, Beta, Gamma) with red markers for emphasis.

### 4. Printed Output:
The script prints the mean PSD values for both signals in each frequency band.
