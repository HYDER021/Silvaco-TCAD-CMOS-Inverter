\# Silvaco TCAD CMOS Inverter and MOSFET Characterization



\## Overview



This project focuses on semiconductor device modeling and CMOS circuit analysis using \*\*Silvaco ATLAS TCAD\*\* and \*\*ATLAS MixedMode\*\*.



NMOS and PMOS devices were modeled and characterized through DC simulations, followed by the implementation and analysis of a CMOS inverter.



\## Objectives



\- Model NMOS and PMOS devices using Silvaco ATLAS

\- Analyze MOSFET transfer characteristics

\- Analyze MOSFET output characteristics

\- Implement a CMOS inverter using ATLAS MixedMode

\- Obtain the CMOS inverter Voltage Transfer Characteristic (VTC)



\## Tools Used



\- Silvaco ATLAS

\- ATLAS MixedMode

\- TonyPlot

\- TCAD



\## Simulations



\### NMOS Characterization



The NMOS device was simulated to obtain:



\- $I\_D-V\_{GS}$ transfer characteristics

\- $I\_D-V\_{DS}$ output characteristics



\### PMOS Characterization



The PMOS device was simulated using PMOS polarity to obtain:



\- $I\_D-V\_{GS}$ transfer characteristics

\- $I\_D-V\_{DS}$ output characteristics for multiple gate voltages



\### CMOS Inverter



The simulated NMOS and PMOS devices were integrated using \*\*ATLAS MixedMode\*\* to form a CMOS inverter.



The input voltage was swept from 0 V to 1.2 V and the corresponding output voltage was analyzed to obtain the Voltage Transfer Characteristic (VTC).



\## Results



\### NMOS Transfer Characteristics



!\[NMOS ID-VGS](graphs/NMOS\_IDVG.png)



\### NMOS Output Characteristics



!\[NMOS ID-VDS](graphs/NMOS\_Output\_Characteristics.png)



\### PMOS Transfer Characteristics



!\[PMOS ID-VGS](graphs/PMOS\_IDVG.png)



\### PMOS Output Characteristics



!\[PMOS ID-VDS](graphs/PMOS\_Output\_Characteristics.png)



\### CMOS Inverter VTC



!\[CMOS Inverter VTC](graphs/CMOS\_Inverter\_VTC.png)



\## Key Observations



\- NMOS drain current increases with increasing gate overdrive.

\- PMOS drain current magnitude increases as the gate voltage becomes more negative.

\- The output characteristics demonstrate linear and saturation behavior.

\- The CMOS inverter exhibits voltage inversion, with low input producing high output and high input producing low output.



\## Domain



\*\*VLSI | TCAD | Semiconductor Device Modeling\*\*



\## Author



Fahim Haider

