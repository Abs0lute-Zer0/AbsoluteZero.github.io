## Block Diagram

![Block Diagram-314 drawio (5)](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156485138/d1b2f173-2f3a-421c-a1c0-bcb2f0a3a0b2)

Figure 1: Block Diagram

The requirements for this project were a key consideration for the team when it came time to designing subsystems and grouping them into appropriate groupings. The requirements for this project were that the system must include at least two separate serial sensors, which could include the following: temperature, humidity, atmospheric pressure, wind speed, or other modalities with instructors' approval. Additionally, the project must include at least one motor controlled by a motor controlled via I2C or SPI.

The team then worked to divide the work between group members to ensure that all subsystems had a team member working on each section. The subsystems were divided as follows: 
* Briana Wells: Microcontroller and ESP32
* Raj Kodithyala: Humidity Sensor and Drive Motors
* Alex Gutierrez: Reaction Motor & SPI Motor Driver
* Jillian Brooke: Temperature Sensor and 3.3V Regulator

The Microcontroller and ESP32 Subsystems work to meet the requirement that the project must be able to communicate via wifi, to send the sensor data to the user. The humidity and temperature sensors work to fulfill the requirement to have at least two separate serial sensors, to measure the appropriate values in the device's environment. The SPI Motor Driver works to fulfill the requirement to include at least one motor controlled via I2C or SPI, used to raise a flag in the instance that the device detects environmental values that are deemed dangerous. Additionally, the extra Momenent system is an addition that the team decided to do to allow the device to traverse its environment.

## Verification Table

Table 1: Verification Table
![image](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156485138/2a1b9f25-7edb-46dd-b786-642442e6027e)

The above table serves as a guide for further assignments, particularly the hardware implementation.
