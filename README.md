# Fully Differential two-stage Op-amp with common mode feedback

With Regards Abhitej Divi ;)

This project involves designing a fully differential two-stage operational amplifier (with a first-stage differential 5T OTA and a second-stage common-source amplifier) that incorporates common-mode feedback. The design targets approximately 70 dB gain, a 60° phase margin, and stable operation above 150 MHz for both 1pF and 2pF cap loads.

## 1. Design Requirement: 

A) Technology: TSMC 180nm process \
B) Supply Voltage (V<sub>dd</sub>) = 1.8 V \
C) Voltage gain (A<sub>v</sub>) = 70dB \
D) Load Capacitor (C<sub>L</sub>) = 1pF and 2pF \
H) Gain Bandwidth Product (GBW) > 150MHz 

## 2. Schematic diagram

![image alt](https://github.com/abhitejdivi5/Analog-Blocks/blob/ede17b1840882ddd305fb75539875c9c78d120df/2stg_opamp_5t.png)
<p align="center">
<img width="900" alt="Schematic Diagram" src="img width="1306" height="753" alt="Image" src="[https://github.com/user-attachments/assets/d60188c4-c385-45cb-99e7-3434a9239cb1](https://github.com/abhitejdivi5/Analog-Blocks/issues/1#issue-3354274361)
" /">
</p>


## 3. Results
Bode plot is adopted which effectively depicts the design parameters: 

![3 BodePlot_after_increasing_width](https://user-images.githubusercontent.com/62088646/212535500-a4ffb4f3-c77d-459a-a637-91e7ca3809a0.jpg)

Hence \
Voltage gain (A<sub>v</sub>) = 39.4729dB ≈ 40dB \
Gain Bandwidth Product (GBW) ≈ 5 MHz \
Power Dissipation = 122 u W \
Also, the other defined design requirement were met.

For more accurate and comprehensive analysis do check out the [Cookbook](https://github.com/Bishal1022/Analog-IC-Design/blob/main/2.Analog_baseband_circuits/1.Differential_Amplifier/Cook-Book_of_Differential_Amplifier.pdf).
