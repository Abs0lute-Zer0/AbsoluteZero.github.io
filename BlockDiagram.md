## Block Diagram

![BlockDiagram-314 drawio](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156858888/c589fed9-7303-4ea9-8a6d-2e35288f99ac)

Figure 1: Block Diagram

The requirements for this project were a key consideration for the team when it came time to designing subsystems and grouping them into appropriate groupings. The requirements for this project were that the system must include at least two separate serial sensors, which could include the following: temperature, humidity, atmospheric pressure, wind speed, or other modalities with instructors' approval. Additionally, the project must include at least one motor controlled by a motor controlled via I2C or SPI.

The team then worked to divide the work between group members to ensure that all subsystems had a team member working on each section. The subsystems were divided as follows: 
* Briana Wells: Microcontroller and ESP32
* Raj Kodithyala: Humidity Sensor and Drive Motors
* Alex Gutierrez: Reaction Motor & SPI Motor Driver
* Jillian Brooke: Temperature Sensor and 3.3V Regulator

The Microcontroller and ESP32 Subsystems work to meet the requirement that the project must be able to communicate via wifi, to send the sensor data to the user. The humidity and temperature sensors work to fulfill the requirement to have at least two separate serial sensors, to measure the appropriate values in the device's environment. The SPI Motor Driver works to fulfill the requirement to include at least one motor controlled via I2C or SPI, used to raise a flag in the instance that the device detects environmental values that are deemed dangerous. Additionally, the extra Momenent system is an addition that the team decided to do to allow the device to traverse its environment.

## Verification Table

Table 1: Final Verification Table
![Screenshot 2024-04-18 130119](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156858888/96b8da88-f7dc-4e99-a0b5-a0a39222bc92)


The above table served as a guide for further assignments, particularly the hardware implementation.


![image](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156485138/266b5221-b74f-4d66-876d-0c172998cfbf)

Figure 2: Verification table legend
