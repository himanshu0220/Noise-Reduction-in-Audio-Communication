# Real-Time Audio Noise Reduction System (MATLAB)

This project implements a real-time adaptive noise reduction system using MATLAB. It uses techniques like BPSK modulation, NLMS filtering, Wiener filtering, and wavelet denoising.

## Features
- Real-time audio input and processing
- NLMS and Wiener filtering
- Spectral subtraction and wavelet denoising
- GUI controls for live playback and SNR display

## How to Run
1. Open `realTimeProcessing.m` in MATLAB
2. Ensure required toolboxes are installed
3. Run the script and allow microphone access

## Toolboxes Required
- Signal Processing Toolbox
- DSP System Toolbox
- Communications Toolbox

## Comparison with Existing Methods

| Criteria               | Our Work | LMS-Based | NLMS Only | Wavelet-Wiener |
|------------------------|----------|-----------|-----------|----------------|
| Real-time Processing   | ✅ Yes   | ❌ No     | ❌ No     | ❌ No          |
| SNR Improvement        | ✅ High  | Medium    | Medium    | High           |
| GUI Visuals            | ✅ Full  | Basic     | ❌        | ❌             |
| Modular Design         | ✅ Yes   | ❌        | ❌        | ❌             |


## ⚠️ The source code is not publicly available in this repository. If you're interested in collaboration or academic reference, please contact me via email or GitHub Discussions.
