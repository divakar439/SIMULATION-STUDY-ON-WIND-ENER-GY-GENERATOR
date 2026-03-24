# EXP-5-SIMULATION-STUDY-ON-WIND-ENERGY-GENERATOR

## Aim
To design and simulate a wind energy generator using Permanent Magnet Synchronous Generator (PMSG) in MATLAB/Simulink and obtain output parameters.

---

## Software Used
- MATLAB (2021 or above)
- Simulink

---

## Theory
Wind energy is a renewable energy source used to generate electricity using wind turbines. It has minimal environmental impact compared to fossil fuels.

A Wind Energy Conversion System (WECS) consists of:
- Wind turbine
- PMSG generator
- Power electronic converters
- Load or grid

PMSG is preferred because:
- High efficiency
- No need for external excitation
- Suitable for variable speed operation

Wind energy is variable in nature, so methods such as:
- Energy storage
- Hybrid systems
- Grid interconnection
are used to maintain balance between supply and demand.

---

## Components Used
- Wind Turbine
- Permanent Magnet Synchronous Generator (PMSG)
- Three-phase RLC Load
- Step Block
- Manual Switch
- Constant Block
- Product Block
- Bus Selector
- Scope
- Demux

---

## Simulation Parameters

| Parameter        | Value              |
|----------------|-------------------|
| Wind Speed     | 12 m/s            |
| Step Change    | 12 → 8 → 12 m/s   |
| Pitch Angle    | 0 degree          |
| Per Unit Speed | 1.2 p.u           |

---
## Circuit Diagram
<img width="1917" height="991" alt="image" src="https://github.com/user-attachments/assets/de2e85f7-31f3-496f-be58-1d529aa7930f" />


## Procedure
1. Open MATLAB.
2. Open Simulink Library Browser.
3. Add required components:
   - Wind turbine, PMSG, RLC load
   - Step, Constant, Product, Manual Switch
   - Scope, Demux, Bus Selector
4. Connect all components as per the model.
5. Set wind speed and pitch angle.
6. Apply step change in wind velocity.
7. Run the simulation.
8. Observe the output waveforms.

---
## Output Waveforms
<img width="1918" height="896" alt="image" src="https://github.com/user-attachments/assets/6f978f0c-81e6-4cb0-b476-faf5746f89af" />
<img width="1918" height="893" alt="image" src="https://github.com/user-attachments/assets/a8e3de2f-a98c-4910-8f61-0bd248fae111" />
<img width="1902" height="923" alt="image" src="https://github.com/user-attachments/assets/13801e24-860d-4093-b4a3-cb603643d439" />

## Result
The simulation of the PMSG-based wind energy system was successfully completed. Three-phase voltage and current waveforms were obtained.
