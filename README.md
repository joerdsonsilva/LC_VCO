# Cryo_LCVCO

Repository containing the design and simulations of an LC VCO (Voltage-Controlled Oscillator), developed in CMOS technology for operation at room temperature and cryogenic conditions.

## VCO

The topology used is a cross-coupled LC VCO (LCVCO), as illustrated in the figure below. The oscillator employs an RLC tank with a pair of cross-coupled transistors to provide the feedback necessary for oscillation, while a current mirror sets the current of the cross-coupled pair, ensuring stability and control of the operating point.

<!--![Topologia do VCO](Images/LCVCO.png) -->
<!--*Figure 1: Cross-Coupled LC VCO Topology with Differential Output.* -->

.. image:: Images/LCVCO.png
    :align: center
    :alt: Schematic Oscilator
    :width: 800

Input and Output of a Cross-Coupled LC VCO:

- LO+ and LO-: Differential output pair
- VCC: Power supply terminal
- ICC: Bias current terminal
- VCTR: Control Voltage of the varactor
- GND: Ground terminal

## Parameters

| Parameter               | Value       |
| ----------------------- | ----------- |
| Technology              | IHP 130 nm  |
| Center Frequency        | 4.9 GHz     |
| Tuning Range            | 4.7–5.0 GHz |
| Control Voltage (Vctrl) | 0–3 V       |
| Supply Voltage          | 1.5 V       |

