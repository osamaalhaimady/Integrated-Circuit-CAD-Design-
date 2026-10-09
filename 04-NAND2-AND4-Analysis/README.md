# NAND2 and AND4 Gate Analysis

## 1. Objective

This project investigates the characteristics of CMOS NAND2 and AND4 logic gates through circuit simulation.

The analysis focuses on CMOS logic operation, power consumption, propagation delay, and technology scaling.

## 2. Simulation Environment

- **Simulation Tool:** LTspice XVII
- **Circuit Type:** CMOS NAND2 and AND4 Logic Gates
- **Analysis:** Circuit and Performance Analysis
- **Technology Nodes:** 65 nm, 45 nm, and 32 nm

## 3. NAND2 Logic Gate

A NAND2 gate has two inputs and one output.

The output is LOW only when both inputs are HIGH. For all other input combinations, the output is HIGH.

### Truth Table

| Input A | Input B | Output Y |
|---------|---------|----------|
| 0 | 0 | 1 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 0 |

The Boolean expression is:

Y = NOT (A AND B)

## 4. AND4 Logic Gate

An AND4 gate has four inputs and one output.

The output is HIGH only when all four inputs are HIGH.

The Boolean expression is:

Y = A AND B AND C AND D

## 5. Performance Analysis

The analysis considers the following characteristics:

- CMOS logic operation.
- Power consumption.
- Propagation delay.
- Transistor sizing and logic effort.
- Performance differences across technology nodes.

## 6. Technology Scaling

The project examines circuit behavior using 65 nm, 45 nm, and 32 nm technology models.

Simulation results can be used to compare circuit performance across these technology nodes.

## 7. Results and Discussion

The measured simulation results and corresponding plots will be documented here.

Comparisons will be based on the actual results obtained from LTspice.

## 8. Conclusion

This project provides practical experience in CMOS logic gate analysis and integrated circuit design.

It also develops an understanding of logic functionality, power consumption, propagation delay, and the effects of technology scaling.

## 9. Tools

- LTspice XVII
- CMOS transistor models
- Logic gate simulation
- Power and delay analysis
