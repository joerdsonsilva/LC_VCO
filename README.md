# Cryo_LCVCO

Repository containing the design and simulations of an LC VCO (Voltage-Controlled Oscillator), developed in CMOS technology for operation at room temperature and cryogenic conditions.

Projeto de VCO (Voltage Controlled Oscillator) para 4.9 GHz em IHP 130nm.

| Parâmetro          | Valor           |
| ------------------ | --------------- |
| Tecnologia         | IHP 130 nm      |
| Frequência central | 4.9 GHz         |
| Faixa de sintonia  | 4.7–5.0 GHz     |
| Vctrl              | 0–3 V           |
| Alimentação        | 1.5 V           |


The topology used is a cross-coupled LC VCO (LCVCO), as illustrated in the figure below. The oscillator employs an RLC tank with a pair of cross-coupled transistors to provide the feedback necessary for oscillation, while a current mirror sets the current of the cross-coupled pair, ensuring stability and control of the operating point.

![Topologia do VCO](Images/LCVCO.png)
*Figura 1: Topologia do LCVCO cross-coupled com saída diferencial.*
