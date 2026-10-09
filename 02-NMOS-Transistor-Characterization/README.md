# NMOS Transistor Characterization

## Objective

This project investigates the electrical characteristics of an NMOS transistor using LTspice and a 65 nm semiconductor technology model.

The analysis focuses on the drain current characteristics, operating regions, leakage current, temperature effects, and body bias.

## Simulation Environment

- Simulation Tool: LTspice XVII
- Technology Node: 65 nm
- NMOS Width (W): 65 nm
- NMOS Length (L): 65 nm
- Drain Voltage (VDS): 0–1.1 V
- Gate Voltage (VGS): 0.1–1.1 V

## I-V Characteristics

The NMOS transistor was analyzed by sweeping the drain-to-source voltage while applying different gate-to-source voltages.

The resulting I-V characteristics were used to identify the main transistor operating regions and observe the dependence of drain current on the applied voltages.

## Operating Regions

The simulation was used to examine the transistor behavior in different operating regions, including:

- Cutoff region
- Linear region
- Saturation region

## Leakage and Temperature Effects

The project also investigates leakage behavior and the effect of temperature on transistor characteristics.

These simulations provide insight into the behavior of MOS devices under different operating conditions.

## Body Effect

Body bias was investigated to observe its influence on the NMOS transistor characteristics and threshold behavior.

## Technology Scaling

The transistor behavior was also compared across different technology nodes:

- 65 nm
- 45 nm
- 32 nm

This comparison helps illustrate how transistor characteristics change as the technology node scales.

## Conclusion

The simulations provide a transistor-level analysis of NMOS behavior using LTspice.

The results demonstrate the relationship between terminal voltages and drain current, as well as the effects of leakage, temperature, body bias, and technology scaling.

## Single Transistor Characterization (65nm)
### LTspice Code
![LTspice Code 1](LTspice%20Code4.JPG)
## Simulation Result
### (Insert your first graph here – the one showing Id vs. Vds for VGS = 0.1V to 1.1V)
![Simulation Result 1](Simulation%20Result5.JPG)
##  Measured Values and Analysis
### Table 5.1: Drain current at VDS=1.1 VVDS=1.1 V for different VGSVGS values.
![Measured Values and Analysis 1](Measured%20Values%20and%20Analysis6.JPG)
##  Body Biasing Effect (NMOS)
###  LTspice Code
![LTspice Code 2](LTspice%20Code7.JPG)
## Simulation Result
### (Insert your second graph here – the log-scale curves for VBS = -0.5V, 0V, +0.5V)
![Simulation Result 2](Simulation%20Result8.JPG)
##  Measured Values and Analysis
### Table 5.2: NMOS drain current and leakage variation with body bias
![Measured Values and Analysis 2](Measured%20Values%20and%20Analysis9.JPG)
