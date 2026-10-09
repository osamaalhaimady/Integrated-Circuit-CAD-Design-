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
