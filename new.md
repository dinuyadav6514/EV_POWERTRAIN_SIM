# Simulink Model Overview

Description: Detailed block diagram of the EV powertrain system.

Components: Includes Battery, Motor Controller, Motor, Vehicle Dynamics, Longitudinal Driver, and NEDC drive cycle integration.

Insight: Models power flow and vehicle behavior, simulating real-world conditions effectively.
![model](<Screenshot 2025-08-04 004824.png>)
![model](<Screenshot 2025-08-04 004646.png>)


# State of Charge (SoC) Graph
Description: Displays the battery's State of Charge over time.

Observation: Shows a gradual decline from a high value to a lower level over approximately 800 time units, with minor fluctuations indicating discharge during operation.

Insight: Reflects realistic battery usage under a simulated drive cycle.
![SOC Curve](<Screenshot 2025-08-04 005005.png>)

# Current Drawn from Battery Graph

Description: Shows the current drawn from the battery over time.

Observation: Features periodic spikes corresponding to acceleration, with lower values during steady-state or deceleration.

Insight: Highlights dynamic current demands based on driving conditions.

![Current Drawn](<Screenshot 2025-08-04 004926.png>)


# Reference Speed vs. Vehicle Speed Graph





Description: Compares reference speed (yellow) and vehicle speed (cyan) over time.



Observation: Reference speed shows periodic peaks, with vehicle speed closely tracking it, indicating good control system performance.



Insight: Demonstrates the model's ability to maintain desired speed profiles.


![Reference speed, vehicle speed](<Screenshot 2025-08-04 004852.png>)


# Conclusion

The Simulink model successfully simulates the Tata Nexon EV powertrain, with results aligning with expected EV behavior under various driving conditions. The analysis of SoC, speed tracking, and current draw provides valuable insights into system performance and efficiency.
