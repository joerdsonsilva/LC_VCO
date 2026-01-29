# Cryo_LCVCO

Repository containing the design and simulations of an LC VCO (Voltage-Controlled Oscillator), developed in CMOS technology for operation at room temperature and cryogenic conditions.

## VCO

The LC-VCO schematic was implemented in the Cadence Virtuoso environment, using the technology available in the SG13G2 folder for room-temperature simulations. To enable operation under cryogenic conditions, transistor characterization was provided by IHP and made available in the SG13G2C folder, allowing for the analysis of device behavior at low temperatures. The schematic and the testbench were implemented according to Figures 1 and 2, respectively.

![Schematic](../Images/Schematic.png)
*Figure 1: LC-VCO schematic.*

![Testbench](../Images/Testbench.png)
*Figure 2: Testbench Setup for the LCVCO.*


Input and Output of a Cross-Coupled LC VCO:

- LO+ and LO-: Differential output pair
- VCC: Power supply terminal
- ICC: Bias current terminal
- VCTR: Control Voltage of the varactor
- GND: Ground terminal


