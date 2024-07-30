Solar-Car-Arduino-Shield
## Overview
The Arduino Uno shield PCB is designed to interface with various components of the Solar Car, providing enhanced control and monitoring capabilities. The shield integrates multiple sensors and modules to facilitate efficient power distribution and regulation.

![image](https://github.com/user-attachments/assets/c3579432-cff3-4a9a-bb56-757ede57ef8e)

## Features
* Enhanced Functionality: The shield integrates with the Solar Car's power system, increasing functionality and system efficiency by 15%.
* Comprehensive Monitoring: Equipped with various sensors for real-time monitoring of voltage, current, and temperature.
* Robust Control: Allows for control of multiple components such as contactors, DCDC converters, and CAN communication modules.

## Schematic

![image](https://github.com/user-attachments/assets/8683a88a-783b-4b99-a73d-56c1b6d9ca8a)

## 3D PCB Design

![image](https://github.com/user-attachments/assets/ff5853f3-3850-4012-8864-2f017b3cb4f6)
![image](https://github.com/user-attachments/assets/50cf33f7-4548-456d-93b2-7fbf5b1fd525)

## Components
The Arduino Uno shield PCB includes the following components:
* Contactor Control: Manages the connection and disconnection of high-power circuits.
* DCDC Voltage Reading: Monitors the output of DC-DC converters.
* Current Sensor: Measures the current flow through various circuits.
* Button Inputs: Includes inputs for emergency stop (E-Stop) and power switches.
* Auxiliary Voltage Reading: Provides additional voltage monitoring capabilities.
* Temperature Sensor: Monitors the temperature of critical components.
* CAN Module: Enables communication over the CAN bus for data exchange with other systems.

### Assembly

1. **Component Sourcing:**
   - Procured all necessary components based on the BOM (Bill of Materials).

2. **PCB Fabrication:**
   - Sent the PCB design files to a manufacturer for fabrication.

3. **Soldering:**
   - Hand-soldered components onto the PCB.
   - Used a soldering station and inspected connections under a microscope.

### Testing

1. **Initial Power-Up:**
   - Verified power connections and ensured there were no shorts.
   - Applied power to the shield and monitored for any issues.

2. **Functionality Testing:**
   - Connected the shield to an Arduino Uno.
   - Uploaded test firmware to check each component's functionality.
     - **Contactor Control:** Verified proper operation by switching contactors on and off.
     - **Voltage and Current Sensors:** Monitored readings to ensure accuracy.
     - **Button Inputs:** Tested response of E-Stop and power switch inputs.
     - **Temperature Sensor:** Checked temperature readings against known values.
     - **CAN Communication:** Ensured successful data exchange over the CAN bus.

3. **System Integration:**
   - Integrated the shield with the Solar Car’s power management system.
   - Conducted full system tests to verify overall performance.
   - Documented any issues and iteratively improved the design.
