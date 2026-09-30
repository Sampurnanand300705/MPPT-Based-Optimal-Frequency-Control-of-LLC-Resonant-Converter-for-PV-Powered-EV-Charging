Project Explanation

MPPT-Based Optimal Frequency Control of LLC Resonant Converter in PV Systems

I developed a PV-based power conversion system in MATLAB/Simulink using an LLC resonant converter. The main objective of the project was to extract the maximum available power from the solar PV system while controlling the converter efficiently.

The system consists of a PV array, half-bridge inverter, LLC resonant tank, transformer, diode rectifier, output capacitor, and resistive load.

Instead of using conventional PWM duty-cycle control, I controlled the converter by changing its switching frequency. I implemented a metaheuristic optimization algorithm inside a MATLAB Function block to search for the Maximum Power Point (MPP).

The frequency adjustment was made adaptive:

When the operating point was far from the MPP, the controller used larger frequency steps to reach the MPP quickly.
When it approached the MPP, it used smaller steps to reduce power fluctuations and improve stability.

Finally, I tested the system under changing solar irradiance and temperature conditions to verify whether the controller could track the MPP effectively. I also checked the converter's ZVS and ZCS soft-switching behavior, which helps reduce switching losses and improve converter efficiency.
