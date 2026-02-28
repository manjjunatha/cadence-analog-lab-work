# Inverter – Cadence Lab Experiment

## Objective
To design and simulate an inverter using Cadence Virtuoso.

## Technology
180nm  
VDD = 1.8V  

## Design Parameters
PMOS: W = 5µm, L = 180nm  
NMOS: W = 2µm, L = 180nm  

---

## 1. Schematic

![Schematic](inverter_schematic.png)

---

## 2. Symbol

![Symbol](inverter_symbol.png)

---

## 3. Test circuit

![Testbench](inverter_test_circuit.png)

---

## 4. Simulation Results

![Simulation Results](transeint_&_dc_analysis.png)

### DC Analysis
- Inverter VTC observed.
- Switching threshold ≈ 0.9V.

### Transient Analysis
- Output inverted relative to input.
- Rise and fall transitions visible.

---

## Learning Outcome

- Understood inverter operation.
- Learned symbol creation and testbench setup.
- Observed DC and transient characteristics.
