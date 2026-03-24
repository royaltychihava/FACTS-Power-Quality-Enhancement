[FACTS_Power_Quality_Report.pdf](https://github.com/user-attachments/files/26215702/FACTS_Power_Quality_Report.pdf)
# Modeling and Simulation of FACTS Devices for Power Quality Enhancement

## Overview
This project investigates the application of Flexible AC Transmission Systems (FACTS) devices to improve power quality and overall performance of electrical power systems.

## Objective
To evaluate how FACTS devices provide fast dynamic compensation and enhance system stability under different operating conditions.

## Modeling Approaches

### Dynamic Modeling
- Implemented a detailed 48-pulse, three-level multipulse GTO-based converter  
- Designed associated control structure for transient analysis  
- Captured fast dynamic response of FACTS devices  

### Phasor Average Modeling
- Used simplified algebraic equations  
- Focused on steady-state system performance  
- Suitable for large-scale system studies  

## Tools Used
- MATLAB  
- Simulink  

## Key Results & Conclusions

- Identified Bus 4 as the weakest node in voltage regulation, requiring reactive power compensation to maintain stability within the 0.97–1.03 p.u. range  

- Closed-loop control of the 48-pulse converter outperformed open-loop control, achieving:
  - Improved reference tracking  
  - Reduced steady-state error  
  - Enhanced disturbance rejection  

- Achieved decoupled control of active and reactive power:
  - Id regulates active power  
  - Iq regulates reactive power  

- Implemented direct control strategy by:
  - Adjusting zero voltage vectors to control output magnitude  
  - Modifying phase angle to regulate converter output voltage  

- STATCOM successfully regulated voltage at the weakest bus using indirect control via DC-link voltage  

- Phasor average model simplified system analysis:
  - Reduced computational complexity  
  - Eliminated need for PLL  
  - Provided a balance between accuracy and simulation speed  

## Conclusion
This project demonstrates the effectiveness of FACTS devices, particularly STATCOM, in improving voltage stability and power quality, while highlighting the trade-offs between detailed dynamic modeling and simplified phasor approaches.

## Files
- FACTS_Power_Quality_Report.pdf  
- MATLAB/Simulink files  

## Author
Royalty Holyworth Chihava
