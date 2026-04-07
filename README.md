# PHASE-MODULATION-AND-DEMODULATION-USING-SCILAB
AIM

To write a program for Phase Modulation and Demodulation using SCILAB and to observe and measure the phase deviation and modulation index.

APPARATUS REQUIRED

Computer with i3 Processor or higher
SCILAB Software

THEORY

Phase Modulation (PM) is a modulation technique in which the phase of the carrier signal is varied in accordance with the instantaneous amplitude of the modulating signal, while the amplitude of the carrier remains constant.

Phase Deviation (Δφ)

Phase deviation represents the maximum change in phase of the carrier signal.

Δφ = kp * Am

Where:

kp = Phase sensitivity (rad/volt)
Am = Amplitude of modulating signal
Modulation Index (mp)
mp = Δφ

For sinusoidal signals:

mp = kp * Am
PM Signal Equation
s(t) = Ac cos(2πfc t + kp m(t))

For sinusoidal modulating signal:

s(t) = Ac cos(2πfc t + mp sin(2πfm t))

Where:

Ac = Carrier amplitude
fc = Carrier frequency
fm = Modulating frequency
kp = Phase sensitivity
mp = Modulation index

ALGORITHM

Define parameters:
Sampling frequency Fs
Time duration T
Carrier frequency fc
Modulating frequency fm
Phase sensitivity kp
Generate signals:
m(t) = sin(2πfm t)
c(t) = cos(2πfc t)
PM Modulation:
s(t) = cos(2πfc t + kp * m(t))
PM Demodulation:
Differentiate the PM signal
Apply envelope detection:
|s(t)|
Use low-pass filter to recover the original signal
Plot all signals:
Modulating signal
Carrier signal
PM signal
Demodulated signal

PROCEDURE

Refer to the algorithm and write the SCILAB code.
Open SCILAB software.
Create a new script file.
Enter the program and save it.
Execute the code.
Debug errors if any and re-run.
Observe the generated waveforms.

OUTPUT GRAPH
<img width="2880" height="1696" alt="pm" src="https://github.com/user-attachments/assets/0b8f818e-2c4e-4d80-b81f-7ffc81dedc8c" />


TABULATIONS
<img width="1280" height="858" alt="image" src="https://github.com/user-attachments/assets/61d2f0c1-eb7e-4543-99fb-3330086bb551" />



CALCULATIONS
<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/032c7cbe-bbbb-4303-a8fd-0cfc8ccabb94" />

RESULT
<img width="1280" height="960" alt="image" src="https://github.com/user-attachments/assets/68c4e5fe-d639-4d7c-a7a1-8a8cd31a1f7a" />

