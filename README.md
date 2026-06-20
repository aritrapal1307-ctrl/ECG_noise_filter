# ECG_noise_filter
# ECG Noise Removal Using Twin-T Notch Filter in LTspice

## Overview

This project demonstrates removal of 50 Hz power-line interference from an ECG signal using a Twin-T Notch Filter and an RC Low-Pass Filter.

## Objective

To simulate ECG acquisition, introduce artificial power-line noise, and recover a cleaner ECG waveform through analog filtering techniques.

## Components Used

- ECG Source (1 Hz sine wave)
- Noise Source (50 Hz sine wave)
- Behavioral Voltage Source (Signal Adder)
- Twin-T Notch Filter
- RC Low-Pass Filter

## Working Principle

1. A 1 Hz ECG signal is generated.
2. A 50 Hz interference signal is generated.
3. Both signals are added using a behavioral voltage source.
4. The Twin-T notch filter attenuates the 50 Hz component.
5. An RC low-pass filter removes residual high-frequency noise.
6. A cleaner ECG signal is obtained.

## Circuit Diagram

![Circuit](images/circuit.png)

## Noisy ECG

![Noisy ECG](images/noisy_ecg.png)

## Twin-T Notch Filter Verification

![Notch Test](images/notch_test.png)

## Final Output

![Final Output](images/final_output.png)

## Concepts Demonstrated

- Biomedical Signal Processing
- ECG Noise Removal
- Twin-T Notch Filter Design
- Low-Pass Filter Design
- LTspice Simulation
