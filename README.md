# Air-Coupled NDT Analyzer

Interactive signal analysis interface for air-coupled ultrasonic non-destructive testing (NDT) of early-age concrete and mortar specimens using leaky Rayleigh waves.

## Live Interface

Access the analyzer at: **https://YOUR_USERNAME.github.io/Air-Coupled-NDT-Analyzer/**

## Features

- **16 analysis tabs** including time domain, FFT spectrum, PSD, spectrogram, envelope, phase, cross-correlation, cepstrum, autocorrelation, instantaneous frequency, condition comparison, statistics, window preview, direct acoustic detection, and attenuation analysis
- **Direct acoustic wave detection and separation** with B-scan, envelope B-scan, wiggle trace, signal classification, velocity-filtered separation, and overlay views
- **Attenuation analysis** with peak amplitude decay, energy decay, frequency-dependent spectral attenuation, and broadband coefficient extraction with geometric spreading correction
- **Embedded experimental data** from LDV measurements on mortar specimens (with and without foam coupling, 47 signals per condition)
- **Interactive controls** for bandpass filtering, windowing, time gating, and signal selection
- **Comprehensive documentation** panel for every analysis tab explaining the physics and parameter effects

## Experimental Setup

- Air-coupled ultrasonic transducer at 5 degree incidence angle
- Laser Doppler Vibrometer (LDV) surface velocity measurement
- 16-cycle tone burst excitation (50-90 kHz range)
- 6.6 mm lift-off, 85 mm mortar specimen
- 47 measurement points starting at 50 mm with 5 mm spacing
- 1 MHz sampling rate

## Usage

Open `index.html` in any modern web browser. All data and processing are self-contained in the single HTML file -- no server or installation required.

## License

This tool was developed for academic research in contactless NDT of early-age cementitious materials.
