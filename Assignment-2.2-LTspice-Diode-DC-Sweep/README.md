# Assignment 2.2 – LTspice DC Sweep (Diode I–V)

**Student Name:** Talal Khan  

## Circuit Description
The circuit consists of a DC voltage source (V1), a 1 kΩ resistor (R1),
and a silicon diode (1N4148) connected in series to ground. This setup is
used to obtain the diode current–voltage (I–V) characteristic using a DC sweep.

## DC Sweep Settings
- Swept source: V1
- Sweep type: DC linear sweep
- Voltage range: 0 V to 50 V
- Step size: 0.1 mV

## Files Included
- diode_dc_sweep.asc – LTspice schematic file  
- schematic.png – Screenshot of the LTspice circuit  
- diode_iv.png – Screenshot of the diode I–V simulation plot  

## Result
The simulation plot shows the diode current I(D1) increasing as the input
voltage is swept. Due to the 1 kΩ series resistor, the current is limited,
resulting in an approximately linear rise at higher voltages.
