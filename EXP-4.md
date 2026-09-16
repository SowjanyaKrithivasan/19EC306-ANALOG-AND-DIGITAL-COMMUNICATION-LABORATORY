# Aim:
To obtain Pulse Width Modulation & Demodulation using PCM trainer kit.

# THEORY:
Pulse Width Modulation
This technique of modulation controls the variation of duty cycle of the square wave (With some fundamental frequency) according to the input modulating signal. Here the amplitude variation of the modulation signal is reflected in the ON period variation of square wave. Hence, it is a technique of V to T conversion.
Pulse Width Demodulation
The input signal is Pulse Width Modulated, so the ON time of the signal is changing according to the modulating signal. In this demodulation technique during the ON time of PWM signal one counter is enabled. At the end of ON time, counter gives a particular count, which directly corresponds to- the amplitude -of input signal. Then this count is fed to a DAC. The output of DAC corresponds to
the amplitude of input signal. Thus train of varying pulse widths gives varying count values and accordingly DAC give outputs, which is directly proportional to amplitude of input signal. This is then filtered to get original signal. Thus at the output we get the original modulating signal extracted from PWM wave.
 
# EQUIPMENTS:
Experimental kit DCL -08 Connecting chords
Power supply
20 MHz Dual trace oscilloscope
NOTE: Keep The Switch Faults In Off Position.
 

# PROCEDURE:
Refer to the block diagram (Fig. 2) and carry out the following connections	and switch Connect the Power Supply with proper polarity to the kit DCL-08 and switch it on.
Put jumper JP3 to 2nd position.
Keep CH1 knob of CRO on 1 Volt/ divac. Keep CH2 knob of CRO on 2 Volts/ divac. Keep Times/ div knob on 1 msec.
Keep the CRO in Dual channel (Auto/ TV mode). Use X10 for expansion. After proper triggering of CRO, observe both the signals PWM IN and PWM

# BLOCK DIAGRAM:
<img width="858" height="552" alt="image" src="https://github.com/user-attachments/assets/7a0765c4-10e5-441d-997b-147e9b01a94a" />

# Tabulation:
<img width="1256" height="685" alt="image" src="https://github.com/user-attachments/assets/eeeb257f-78dc-434d-a494-28b3c2fa2d0d" />

# Model Graph:
<img width="652" height="567" alt="image" src="https://github.com/user-attachments/assets/1d30cf0e-73f3-40a2-9028-825a60d7d120" />

# OUTPUT GRAPH:
<img width="616" height="793" alt="image" src="https://github.com/user-attachments/assets/55aaf571-e94e-4179-88a8-6c56b9387801" />

# Result:
Thus the pulse width modulated and demodulated signals is generated and output is verified.

