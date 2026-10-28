# Analog Electronics — Amplifier Design and Simulation

**Sanaz Mazrae**  
Department of Electrical Engineering, Sharif University of Technology

Two Electronics III projects focused on the analysis and design of bipolar and CMOS amplifiers using **Keysight ADS**. MATLAB Live Scripts are also used for selected small-signal and frequency-response calculations in Project 1.

## Project 1 — BJT and CMOS Amplifier Analysis

The first project studies four amplifier configurations: a common-emitter BJT stage with an active load, a BJT differential amplifier, a differential amplifier with a current-mirror load, and a CMOS amplifier using 180 nm transistor models. The analyses cover DC biasing, small-signal parameters, frequency response, parasitic capacitances, common-mode behavior, power consumption, and output swing.

[Project report](project-1/Report.pdf) · [ADS schematics](project-1/ADS_Workspace.zip) · [MATLAB Live Scripts](project-1/matlab/)

## Project 2 — Two-Stage CMOS Amplifier Design

The second project develops a two-stage CMOS differential amplifier with a 1.8 V supply. It examines transistor sizing, open-loop gain, common-mode input range, feedback stability, capacitive and Miller compensation, slew rate, and output swing.

The report presents the following results for the designed and compensated circuit:

| Parameter | Reported result |
|---|---:|
| Calculated low-frequency gain | 66.57 dB |
| DC power consumption | 0.998 mW |
| Phase margin with tuned Miller compensation | Approximately 64° |
| Unity-gain frequency | 338.9 MHz |
| Slew rate | 162.8 V/µs |

[Project report](project-2/Report.pdf) · [ADS schematics](project-2/ADS_Workspace.zip)

## Project Files

The ADS workspace archives contain the circuit schematics and data-display setups. Generated simulation datasets are not included. Re-running the CMOS simulations requires a compatible **180 nm device model library** configured in ADS; the process models are not distributed with the repository. The `.mlx` files in Project 1 can be opened in MATLAB Live Editor.
