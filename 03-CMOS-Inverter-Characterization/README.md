# CMOS Inverter Characterization

## 1. Objective

This project investigates the electrical characteristics of a CMOS inverter using LTspice.

The main objectives are to analyze the voltage transfer characteristics (VTC), understand the switching behavior, and compare a CMOS inverter with an NMOS resistive-load inverter.

## 2. Simulation Environment

- **Simulation Tool:** LTspice XVII
- **Circuit Type:** CMOS Inverter
- **Analysis:** DC Sweep and Transient Analysis
- **Technology:** CMOS transistor-level simulation

## 3. Circuit Description

A CMOS inverter consists of two complementary MOSFETs:

- **PMOS transistor:** Connected to the positive supply voltage.
- **NMOS transistor:** Connected to ground.
- **Input (Vin):** Connected to the gates of both transistors.
- **Output (Vout):** Taken from the common connection between the PMOS and NMOS transistors.

The circuit produces an output voltage that is logically opposite to its input voltage.

## 4. Voltage Transfer Characteristics

A DC sweep is used to investigate the relationship between input voltage (Vin) and output voltage (Vout).

The voltage transfer curve helps identify:

- Logic HIGH and logic LOW output levels.
- The inverter switching region.
- The transition between NMOS and PMOS conduction.
- The overall inverter behavior.

## 5. CMOS vs. NMOS Resistive-Load Inverter

The project compares a complementary CMOS inverter with an NMOS resistive-load inverter.

The comparison focuses on:

- Static power consumption.
- Output voltage levels.
- Switching behavior.
- Circuit performance.

## 6. Results and Discussion

The simulation results are used to study the voltage transfer characteristics and switching behavior of the CMOS inverter.

The measured results and plots will be added after reviewing the LTspice simulation data.

## 7. Conclusion

This project provides practical experience in CMOS inverter characterization and transistor-level circuit simulation.

It also helps develop an understanding of voltage transfer characteristics, inverter switching behavior, and the differences between CMOS and resistive-load logic.

## 8. Tools

- LTspice XVII
- MOSFET transistor models
- DC Sweep Analysis
- Transient Analysis

## Analysis (Voltage Transfer Characteristic)
### LTspice Code
![LTspice Code 1](LTspice%20Code1.JPG)
## Figure 6.1: DC voltage transfer characteristics of the NMOS resistive-load inverter for three load
resistances.
### Simulation Result
![Simulation Result 2](Simulation%20Result2.JPG)
## NMOS resistive-load inverter DC parameters.
![NMOS DC Parameters](NMOS%20resistive-load%20inverter%20DC%20parameters.3.JPG)
##Transient Analysis (Propagation Delay)
### LTspice Code
![LTspice Code 4](LTspice%20Code4.JPG)
## Figure 6.2: Transient response of the NMOS resistive-load inverter for different load resistances.
### Simulation Result
![Simulation Result 5](Simulation%20Result5.JPG)
## NMOS resistive-load inverter transient parameters
![NMOS Transient Parameters](NMOS%20resistive-load%20inverter%20transient%20parameters.6.JPG)
## DC Analysis (Voltage Transfer Characteristic)
### LTspice Code
![LTspice Code 7](LTspice%20Code7.JPG)
## Figure 6.3: DC voltage transfer characteristic (VTC) of the CMOS inverter.
### Simulation Result
![Simulation Result 8](Simulation%20Result8.JPG)
## CMOS inverter DC parameters.
![CMOS DC Parameters](CMOS%20inverter%20DC%20parameters.9.JPG)
## Transient Analysis
### LTspice Code
![LTspice Code 10](LTspice%20Code10.JPG)
## Figure 6.4: Transient response of the CMOS inverter.
### Simulation Result
![Simulation Result 11](Simulation%20Result11.JPG)
## Comparative Discussion
### Comparison of NMOS resistive-load and CMOS inverters
![Comparison](Comparison%20of%20NMOS%20resistive-load%20and%20CMOS%20inverters.12.JPG)
