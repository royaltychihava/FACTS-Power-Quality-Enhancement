<img width="1914" height="935" alt="Effect_of_capacitive_load_at_Bus_4_on_bus_voltage_and_STATCOM_reactive_power" src="https://github.com/user-attachments/assets/db0e2d57-d366-4442-8828-70a878881c15" />
<img width="1913" height="935" alt="Effect_of_inductive_load_at_Bus_4_on_bus_voltage_and_STATCOM_reactive_power" src="https://github.com/user-attachments/assets/2730ca3b-52f4-4fcc-8dad-9bb219c94fff" />
<img width="816" height="597" alt="STATCOM_control_block_diagram" src="https://github.com/user-attachments/assets/0c163a7c-43c2-4376-a593-e9873a70522e" />
<img width="1032" height="600" alt="Power_System_Network_with_a_STATCOM_connected_to_Bus_4" src="https://github.com/user-attachments/assets/d981f26a-0667-4db2-b1c4-bb33558feb2f" />
<img width="1897" height="928" alt="Pole_Voltages_of_48_pulse_converter" src="https://github.com/user-attachments/assets/f345f0c7-90c7-40cf-95f2-4a904a881669" />
<img width="1892" height="941" alt="Output_3_phase_voltage_of_48_pulse_converter" src="https://github.com/user-attachments/assets/b7739458-a035-4cc4-9bc2-a63435bfc341" />
<img width="641" height="506" alt="Space_vectors_in_the_synchronous_reference_frame" src="https://github.com/user-attachments/assets/10bde276-6580-464c-9288-fc6ccef606e3" />
<img width="1892" height="941" alt="Output_3_phase_voltage_of_48_pulse_converter" src="https://github.com/user-attachments/assets/8a4ef147-6691-4691-b557-74d24ab1dd38" />
<img width="1897" height="928" alt="Pole_Voltages_of_48_pulse_converter" src="https://github.com/user-attachments/assets/62f4a525-96dc-4e7c-8898-7d718ebbe6a7" />
<img width="1130" height="802" alt="Connection_of_2_six_pulse_converters_in_a_48_pulse_converter" src="https://github.com/user-attachments/assets/d96c985c-19c2-4a93-93e6-b4461b8ccb61" />
<img width="285" height="799" alt="Block_configuration_of_the_48_pulse_converter" src="https://github.com/user-attachments/assets/a59aa89a-5787-4ef0-8535-b08d15727956" />
<img width="1784" height="722" alt="Block_diagram_1_of_a_48_pulse_converter_connected_to_the_grid" src="https://github.com/user-attachments/assets/d7488d94-6c40-4174-a811-6b83375caea6" />
<img width="1166" height="775" alt="Block_diagram_2_of_a_48_pulse_converter_connected_to_the_grid" src="https://github.com/user-attachments/assets/1444680e-264d-4442-9f27-fc24c2f0f842" />
<img width="1777" height="575" alt="Complete_system_model_of_48_pulse_converter_connected_to_the_grid" src="https://github.com/user-attachments/assets/6d658666-c0ae-4fe1-9515-c85d95a7061c" />
[FACTS Power Quality Simulink models.zip](https://github.com/user-attachments/files/26216371/FACTS.Power.Quality.Simulink.models.zip)
[FACTS_Power_Quality_Report.pdf](https://github.com/user-attachments/files/26215702/FACTS_Power_Quality_Report.pdf)
# Modeling and Simulation of FACTS Devices for Power Quality Enhancement

## Overview
This project investigates the application of Flexible AC Transmission Systems (FACTS) devices to improve power quality and overall performance of electrical power systems.

## Objective
To evaluate how FACTS devices provide fast dynamic compensation and enhance system stability under different operating conditions.

---

## Modeling Approaches

### Dynamic Modeling
- Implemented a detailed 48-pulse, three-level multipulse GTO-based converter  
- Designed associated control structure for transient analysis  
- Captured fast dynamic response of FACTS devices  

### Phasor Average Modeling
- Used simplified algebraic equations  
- Focused on steady-state system performance  
- Suitable for large-scale system studies  

---

## Simulation Models and System Design

### Power System with STATCOM
![Power System](https://github.com/user-attachments/assets/d981f26a-0667-4db2-b1c4-bb33558feb2f)

Grid-connected power system with a STATCOM installed at Bus 4 to provide reactive power support and improve voltage stability.

---

### STATCOM Control Structure
![Control](https://github.com/user-attachments/assets/0c163a7c-43c2-4376-a593-e9873a70522e)

Control system used to regulate reactive power and maintain bus voltage through dq-axis current control.

---

## Converter Design

### 48-Pulse Converter Configuration
![Converter](https://github.com/user-attachments/assets/d96c985c-19c2-4a93-93e6-b4461b8ccb61)

Topology of the 48-pulse converter formed by combining multiple 6-pulse converters to achieve improved harmonic performance.

---

### Complete Converter System Model
![System Model](https://github.com/user-attachments/assets/6d658666-c0ae-4fe1-9515-c85d95a7061c)

Full Simulink implementation of the grid-connected converter system used for dynamic analysis.

---

## Simulation Results

### Capacitive Load Condition
![Capacitive](https://github.com/user-attachments/assets/db0e2d57-d366-4442-8828-70a878881c15)

Demonstrates the effect of a capacitive load on bus voltage and STATCOM reactive power response.

---

### Inductive Load Condition
![Inductive](https://github.com/user-attachments/assets/2730ca3b-52f4-4fcc-8dad-9bb219c94fff)

Shows system behavior under inductive loading, highlighting the STATCOM’s ability to regulate voltage.

---

### Converter Output Voltage
![Voltage](https://github.com/user-attachments/assets/b7739458-a035-4cc4-9bc2-a63435bfc341)

Three-phase output voltage of the 48-pulse converter demonstrating high-quality waveform generation.

---

## Tools Used
- MATLAB  
- Simulink  

---

## Key Results & Conclusions

- Identified Bus 4 as the weakest node in voltage regulation, requiring reactive power compensation to maintain stability within the 0.97–1.03 p.u. range  

- Closed-loop control of the converter achieved:
  - Improved reference tracking  
  - Reduced steady-state error  
  - Enhanced disturbance rejection  

- Achieved decoupled control:
  - Id regulates active power  
  - Iq regulates reactive power  

- STATCOM effectively regulated voltage using DC-link control  

- Phasor modeling reduced complexity while maintaining accuracy  

---

## Conclusion
This project demonstrates the effectiveness of FACTS devices, particularly STATCOM, in improving voltage stability and power quality, while highlighting the trade-offs between detailed dynamic modeling and simplified phasor approaches.

---

## Files
- FACTS_Power_Quality_Report.pdf  
- FACTS Power Quality Simulink models.zip  

---

## Author
Royalty Holyworth Chihava
