# EMG Signal Detection (Level Detector)

This project involves designing an EMG (Electromyography) signal measurement system with an instrumentation amplifier, filter, rectifier, notch filter, and a level detector to process muscle electrical activity for biomedical applications.

## Features
- Signal acquisition followed by 2 second-order low pass filters with a cutoff around 500 Hz and an overall gain of 800.
- Notch filter to cutoff 50Hz power line noise.
- Rectifier circuit to compensate for negative voltages.
- Level detector to display processed signal levels through LEDs.

## Technologies Used
- **Hardware**: ECG electrodes, TL072 CP (ICs), 3 LEDs
- **Software**: LTspice for simulation, Altium Designer for PCB design

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repository-name.git

