# Noise-Reduction-in-Audio-Communication
This repository presents a real-time audio denoising system developed in MATLAB, aimed at enhancing the intelligibility of speech signals degraded by Additive White Gaussian Noise (AWGN). The project simulates a digital communication environment using BPSK modulation and demodulation, followed by a multi-stage noise reduction pipeline. The system integrates adaptive noise suppression through the Normalized Least Mean Squares (NLMS) algorithm, spectral enhancement using Wiener filtering, and further refinement via spectral subtraction techniques. A custom-built GUI enables real-time visualization of waveforms, frequency spectra, and quantitative performance metrics such as Signal-to-Noise Ratio (SNR) and Mean Squared Error (MSE). Designed with modularity and extensibility in mind, the system supports both offline and live audio processing, making it applicable for research in speech enhancement, telecommunication systems, and assistive hearing technologies

Features:
1.Real-time audio input and processing
2.NLMS and Wiener filtering
3.Spectral subtraction and wavelet denoising
4.GUI controls for live playback and SNR display

How to Run:
1.Open realTimeProcessing.m in MATLAB
2.Ensure required toolboxes are installed
3.Run the script and allow microphone access

Toolboxes Required
1.Signal Processing Toolbox
2.DSP System Toolbox
3.Communications Toolbox

The source code is not publicly available in this repository. If you're interested in collaboration or academic reference, please contact me via email or GitHub Discussions.
