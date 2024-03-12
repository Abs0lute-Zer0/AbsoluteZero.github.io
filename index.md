

# Group 304: Absolute Zero

## "We're up to snow good!"

# Home

### Class Name
EGR 314

### Professor
Dr. Kevin Nichols

### Semester
Spring 2024

### Team Members:
* Raj Kodithyala
* Jillian Brooke
* Alex Gutierrez
* Briana Wells

## Table of Contents

#### [Team Organization Charter](TeamOrganizationCharter.md) 

#### [User Needs, Benchmarking, and Requirements](UserNeedsBenchmarking&Requirements.md) 

#### [Design Ideation](DesignIdeation.md) 

#### [Presentation 1](Presentation1.md) 

#### [Block Diagram and Verification Table](BlockDiagram.md) 

#### [Component Selection](ComponentSelection.md)

#### [Microcontroller Selection](MicrocontrollerSelection.md)

#### [Hardware Proposal](HardwareProposal.md)

#### [SoftwareProposal](SoftwareProposal.md)

## Introduction

This project aims to create a functioning mobile weather station that users can use to receive relevant and accurate environmental readings. The core meteorological readings that this device aims to collect are humidity and temperature. This device must additionally fulfill all class requirements for this project to be considered a success. This means including a custom-chosen PIC, communicating with the user over wifi, and having a motor controlled using SPI/I2C. The team worked to derive a method of formulation/brainstorming to encourage creative thinking to ensure that the final product is a good representation of the values and requirements of the team and the class. The team additionally, inclooded the rover capabilities as an added challenge to the project. The team hopes that this project will better their understanding of robotics, circuit work, and coding in general.

## Team Organization

### Charter

The team met up for the first team meeting to discuss the roles and responsibilities that each member would be expected to fulfill. Over an hour the team worked to write a charter that was agreeable to all members. Below is the result of this meeting.

Our primary goal is to foster a creative learning environment in which every team member has a plethora of opportunities to improve. Through collaborative efforts, another team goal is to improve the communication skills of every member. Furthermore, another goal is for every team member to gain proficiency in all engineering skills discussed and taught in the EGR 314 class. Moreover, another goal is to establish engineering connections to better our careers. Finally, our last goal is to produce a product that accomplishes its tasks with positive customer satisfaction.

### Mission Statement

The team desired to develop an appropriate and accurate mission statement for this project. The team wanted the mission statement to reflect not only the project but also the relations between team members.

Our team’s mission is to develop a portable weather station capable of displaying multiple weather data points connected to an external site. This device aims to provide users with important information about local meteorological conditions.

For the rest of the Team Organization Document, please see 
[Appendix A: Team Organization Charter](TeamOrganizationCharter.md)

## User Needs, Benchmarking, and Requirements

### User Needs

To better understand how to design a product of this type, the team worked together to come up with a list of possible user needs that would provide essential information to keep in mind when it came time to begin designing a device. The team determined that the target users would most likely be individuals/companies with an interest in their local weather or researchers. A sample of these user needs is listed below:

* Device needs to be affordable
* Needs to be easily assembled/repaired
* It needs to ensure effortless relocation
* Device needs to be simplistic in control to ensure user accessibility
* The data recorded needs to be reliable and accurate
* Needs to be durable and able to withstand the conditions it is testing in

For the full list of user needs, please go to [Appendix B: User Needs, Benchmarking, and Requirements](UserNeedsBenchmarking&Requirements.md)

### Voices of Customers (VOC) Benchmarking 

For this, the team decided to do some research on our main experts who would be meteorological experts as well as casual day-to-day customers. We looked at what information is important for both types of customers to know in an easy and fast manner. The main data that was important for our customers to know was: the temperature forecast (with a maximum and minimum value), the humidity outside, and a reasonable weather prediction. This way the user can receive a notification to their phone so that way they can get ready for their day while taking into consideration the weather forecast.

For the list of searches done, please go to [Appendix B: User Needs, Benchmarking, and Requirements](UserNeedsBenchmarking&Requirements.md)

### Documented Progress of Organized Statements

**Board of Needs:** 

![image](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156485138/1c50efb9-c2e4-46b3-be68-892ffd01acc7)

Figure 1: Board of Needs

**Grouped Needs:**

![image](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156485138/1ac142df-68d1-4513-b9c8-efc182f107dd)

Figure 2: Group Needs

**Ranked Needs:**

![image](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156485138/8c476fa1-5221-4085-8f3c-b90763efc028)

Figure 3: Ranked Needs

**Process of Creating User Needs:**
To find the required needs for the device and facilitate organizing the ideas into their categories, the team first brainstormed the needs of the customers based on what we felt the user would care about the most. Initially, the ideas were unrelated but after some work many themes were realized. The team then continued to expand on each theme with the required needs being centered around any potential users.

**Conversion of User Needs into Specifications:**
With every user need falling under a particular category, the team understood whether each user need was quantifiable or qualitative. After this analysis, it was easy to determine how the user needs would fall into a certain specification and what was needed for the final product. As an example, safety specifications were the first to be identified based on the assumed user needs which was used as a basis to convert other user needs to other specifications. 

**Assessment Based on Product Requirements/Aspects:**
The final product's design will be thoroughly assessed on all product aspects as they are all crucial. Safety and functionality will of course be given the most importance of assessment as that signifies a successful or failed product. Of course, there will be many places for improvement after the initial final product so therefore the customizability and manufacturability won't be assessed as heavily but should still be kept in mind when designing the final product. Finally, user experience is. After the safety, functionality, user experience, customizability, and manufacturability product aspects are assessed, the product will be deemed to be either successful or incomplete. Following the final assessment, expandability will be looked at to consider if the product can considered for further improvements. These assessments and checks will determine if the final design meets the product requirements. 


### Compiled List of Ideas

The team worked to sort and rank these needs based on the requirements of the project. Additionally, the team took into consideration the needs and requirements that users would also need for the project to be user-friendly and meet the criteria of the class.

Table 1: Short list of ranked project/customer needs

| Restated Customer Need (Explicit/Latent) | Meta Need | Ranking |
| ---------------------------------------- | --------- | ------- |
| Cost efficient | Functionality | 1 |
| Accurate | Functionality | 2 |
|barometer (measures atmospheric pressure)|Functionality|3|
|rigid body|Functionality|4|
|mobile|Functionality|5|
|economical|Accessibility|6|
|need-based|Functionality|7|
|survives a 6-inch drop|Functionality|8|
|Minimal amount of assembly|Functionality|9|
|Can send information over Wifi|Functionality|10|

For the rest of the list of ideas, please see 
[Appendix B: User Needs, Benchmarking, and Requirements](UserNeedsBenchmarking&Requirements.md)

## Design Ideation

**Team Idea Generation:**
The team felt it was best to first identify several big themes of ideas like safety features and sensor features and then brainstorm features that can fit each category. After writing any big concepts, every person expanded on an assigned concept and generated as many ideas as they could. 

**Brainstorming:**
Initially, the team planned on blindly generating lots of ideas but later on it was discovered that generating features based on pre-planned categories proved to be more efficient. Of course, there is a limitation to potential ideas if the categories have to be pre-planned and therefore the team thought it was best to also include free-flowing ideas that may not fall under any category. 

**Organization and Ranking Process:**
After all the ideas were generated, the team discussed what type of features were most important based on the categories that we thought of during the user needs generation section. As expected, the safety and functionality features were given high importance in a similar order of importance as previously stated in the user needs section. After the team settled on three design concepts each concept was sketched by a separate person. Jillian Brooke sketched the Weather Bug 2000 concept, Raj Kodithyala sketched the Motor Controlled Temperature Gauge concept, and Briana Wells sketched the Rover Weather Station concept.

For a more detailed explanation, please see [Appendix C: Design Ideation](DesignIdeation.md)

## Presentation 1

**Introduction:**
This section showcases the first milestone of the project which depicts the initial design concept phase. Demonstrated with a video, the team showcases the user and product requirements along with possible design solutions. 

[![Watch the video](https://youtu.be/PEDgt7GWlsU)]

The full recording of the presentation can be accessed [here](https://youtu.be/PEDgt7GWlsU) or via the preview seen in [Appendix D: Presentation 1](Presentation1.md)

## Selected Design

![Final Design Concept](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156485138/a75c8028-ddcb-4adc-b548-a1dbaf6c942a)

Figure 4: Selected Design

The Selected design illustrates the desired outcome for this project. The design includes a wheel system with an integrated controller to allow for users to control the trajectory of the device. Additionally, the device is centered around the temperature sensor and the humidity sensor which is related to a built-in alert system to notify users of dangerous conditions. If, for example, the temperature sensor detects a value that is deemed dangerous, such as 100 degrees Fahrenheit, or 40 Degrees Celcius, the device will raise a flag to warn the user. (The image depicts a scenario where the device has detected dangerous conditions). This device will work to ensure user safety with up-to-date readings communicated over wifi via the ESP32. NOTE: Controller and cord not drawn to scale. 


## Block Diagram

![Block Diagram-314 drawio (6)](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156485138/8d83a4cc-026c-4c6f-838a-c061de904e50)

Figure 5: Block Diagram

The requirements for this project were a key consideration for the team when it came time to designing subsystems and grouping them into appropriate groupings. The requirements for this project were that the system must include at least two separate serial sensors, which could include the following: temperature, humidity, atmospheric pressure, wind speed, or other modalities with instructors' approval. Additionally, the project must include at least one motor controlled by a motor controlled via I2C or SPI.

The team then worked to divide the work between group members to ensure that all subsystems had a team member working on each section. The subsystems were divided as follows: 
* Briana Wells: Microcontroller and ESP32
* Raj Kodithyala: Humidity Sensor and Movement system/motors
* Alex Gutierrez: SPI Motor Driver
* Jillian Brooke: Temperature Sensor and 3.3V Regulator

The Microcontroller and ESP32 Subsystems work to meet the requirement that the project must be able to communicate via wifi, to send the sensor data to the user. The humidity and temperature sensors work to fulfill the requirement to have at least two separate serial sensors, to measure the appropriate values in the device's environment. The SPI Motor Driver works to fulfill the requirement to include at least one motor controlled via I2C or SPI, used to raise a flag in the instance that the device detects environmental values that are deemed dangerous. Additionally, the extra Momenent system is an addition that the team decided to do to allow the device to traverse its environment.

For more details, please see [Appendix E: Block Diagram and Verification Table](BlockDiagram.md)

## Component Selection 

### Power Source

Table 2: Power Source Selected


| **Solution** | **Pros** | **Cons** |
| ------------ | -------- | -------- |
| 18650 Battery | -High Ah (2.2 Ah)<br/>-Popular<br/>-Rechargeable<br/>-Cheap ($2.40) | -Large<br/>-Requires Charger |

![image](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156540341/3ea3bab3-692d-44f9-86a0-9d2346b991f7)

**Rationale:** Rechargeable with high amperage capable of delivering the appropriate voltage and current to all the components.

### Voltage Regulator
Table 3: Voltage Regulator Selected

| **Solution** | **Pros** | **Cons** |
| ------------ | -------- | -------- |
| LM2575D2T | -Outputs 3.3V<br/>-Adjustable Output voltage<br/>-High Input Voltage Range (up to 40V)<br/>-Easy to use | -Expensive ($2.39)<br/> |

![image](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156540341/93d65025-36e2-4af8-bc03-323534548766)

**Rationale:**  - Voltage regulator handles high voltage inputs while outputting the required 3.3V. It is the most expensive of the group but the easiest to solder and integrate.

### Fuse
Table 4: Fuse Selected

| **Solution** | **Pros** | **Cons** |
| ------------ | -------- | -------- |
| 0215002.MXP Fuse| -Handles up to 250V<br/>-2 Amp Limiter<br/>-Easy To Replace<br/>-Large | -Large<br/>-Requires Holder<br/>-Expensive |

![image](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156540341/41d54f94-a70a-4fff-bf1d-154ded488948)

**Rationale:** This option is a reliable component with all the capabilities the team is looking for in terms of current limiting and circuit protection. While more expensive than the non-holder style fuses, the ability to quickly and easily replace this component is worth the extra expense in the eyes of the team.

### DC Motor
Table 5: DC Motor Selected

| **Solution** | **Pros** | **Cons** |
| ------------ | -------- | -------- |
| ROB-11696 Gear Motor | -Light (25.85 g)<br/>-Includes a gearbox (reduction ratio: 50)<br/>-Low Cost ($2.10)<br/>-Low Normal Operating Voltage (1-3V)<br/>-Easy to attach to shaft (dent in the shaft) | -Small shaft length<br/>-Small mounting holes<br/>-Import Tariff |

![image](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156540341/d8be4bbb-f09e-43cf-8586-0b630b4e385b)

**Rationale:** We decided to go with the ROB-11696 Gear Motor because it had a healthy balance between its size, weight, cost, and adaptability. It was very cheap for a  DC motor, while still being small and lightweight. The motor won't have to handle heavy loads. 

### Motor Driver
Table 6: Motor Driver Selected

| **Solution** | **Pros** | **Cons** |
| ------------ | -------- | -------- |
| IFX9201SGAUMA1 | -High voltages (40 V)<br/>-Dual Motor Driver (2 half h-bridges)<br/>-Small (7.8 mm x 10mm)<br/>-Easy to use | -Lots of extra pins (5/12 are used) |

![image](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156540341/4e4dfa77-b832-4165-8e59-1660e1290d8b)

**Rationale:** We chose this dual-motor driver because of its cost-effectiveness and ease of use. Utilizing a dual half-H-bridge motor driver, this component lets us drive two motors with ease while not taking up a lot of PCB space. 

### Temperature Sensor
Table 7: Temperature Sensor Selected

| **Solution** | **Pros** | **Cons** |
| ------------ | -------- | -------- |
| TC74A0-3.3VCTTR | -3.3 Operating Voltage<br/>-Digital Signals<br/>-Cheap ($1.15)<br/>-Easy to use | -Tiny (1.9 x 1.2 mm) |

![image](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156540341/193d6ecd-4b02-45da-9e36-100b8bdf4c23)

**Rationale:**  Option one is the most affordable, which works the best with the limited budget that the team is working in. Additionally, this component is the same one that the team will have worked with in class.

### Humidity Sensor
Table 8: Humidity Sensor Selected

| **Solution** | **Pros** | **Cons** |
| ------------ | -------- | -------- |
| HTU31DI.C31DRH/T | -I2C Compatible<br/>-Humidity operating range from 0 to 100%<br/>-Low input voltage required (5.5Vmax) | -Expensive ($3.73)<br/>-No exterior legs for easy soldering |

![image](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156540341/a711b543-25f6-49b7-90b2-90b6dea118fd)

**Rationale:**  Option three is the cheapest and has the same functionality as the rest of the sensors.

For more details, please see [Appendix F: Component Selection](ComponentSelection.md)

# Power Budget

### Components
Table 9: Power Budget of the Components.

| **Component Name** | **Part Number** | **Supply** | **#** | **Absolute** | **Total** | **Units** |
| ------------------ | --------------- | ---------- |-------| ------------ | --------- | --------- |
| Microcontroller | PIC18F27Q10 | 3.3V | 1 | 200 | 200 | mA |
| Motor | ROB-11696 | 3.3V | 1 | 110 | 110 | mA |
| Motor Driver | IFX9201SGAUMA1 | 3.3V | 1 | 60 | 60 | mA |
| Debug LEDs/Normal LEDs | XCMDK12D | 3.3V | 4 | 30 | 120 | mA |
| Piezo Buzzer | COM-07950 | 3.3V | 1 | 35 | 35 | mA |
| Humidity Sensor | 10142048-22 | 3.3V | 1 | 0.414 | 0.414 | mA |
| Temperature Sensor | TC74A0 | 3.3V | 1 | 0.35 | 0.35 | mA |
| OLED Screen | B085WCRS7C | 3.3V | 1 | 20.7 | 20.7 | mA |
| ESP32 | ESP32­WROOM­32 | 3.3V | 1 | 150 | 150 | mA |
|  | ­ |  |  | **Subtotal** | **696.464** | **mA** |
|  | ­ |  |  | **Safety Margin** | **25%** |  |
|  | ­ |  |  | **Total Current Required** | **870.58** |  **mA**|
|  | ­ |  |  |  |  |  |
| 18650 Batteries | USE-18650 | 3.7V | 2 | 2200 | **2200** |  **mA**|
|  |  |  |  | **Total Remaining Current** | **1329.42** |  **mA**|

### Current Calculations
Table 10: Current Calculations.


| **Power Source** | **Component Name** |**Part Number** | **Supply** | **Output** | **Absolute** | **Total** | **Units** |
| ---------------- | ------------------ | -------------- |------------| ---------- | ------------ | --------- | --------- |
| Power Source Selection | Four 18650 Batteries | USE-18650 | +7.4V | +7.4V | 2200 | 2200 | mA |
|  Voltage Regulator | 3.3V Regulator | LM2575D2T | +7.4V | 1 | 870.58 | 870.58 | mA |
|  |  |  |  |   | **Total Remaining Current** | **1329.42** |  **mA**|

### Estimated Battery Life
Table 11: Estimated Battery Life.


| **Component Name** |**Part Number** | **Supply** | **Capacity** | **Required** | **Units** |
| ------------------ | -------------- | ---------- | ------------ | ------------ | --------- |
| 18650 Batteries | USE-18650 | +7.4V | 2200 | 870.58 | mA |
|  |  |   | **Battery Life** | **2.53** |  **hr**|

### Notes
Each 18650 battery has a 3.7V output and 2.2 Ah. We will use two 18650 batteries in series to achieve a 7.4V output and maintain a 2.2Ah capacity. 

## Microcontroller Selection
Table 12: Requirements for the project.

| Design Considerations | PIC18F27Q10 |
| --------------------- | ----------- |
| How many GPIO Pins? | 25 |
| Built-in Analog to Digital Converter? How many? | Yes, 1 |
| Built-in Hardware PWM? How many? | Yes, 2 |
| Built-in I2C? SPI? How many? | Yes, 2 each |
| Built-in UART? How many? | Yes, 2 |

Table 13: Microcontroller Considerations.


| Microcontroller Considerations | PIC18F27Q10 |
| ------------------------------ | ----------- |
| Link (URL) to the Product Page | [PIC18F27Q10](https://ww1.microchip.com/downloads/aemDocuments/documents/MCU08/ProductDocuments/DataSheets/PIC18F27-47Q10-Data-Sheet-40002043E.pdf) |
| Links (URL) to Data Sheets | [PIC18F27Q10](https://ww1.microchip.com/downloads/aemDocuments/documents/MCU08/ProductDocuments/DataSheets/PIC18F27-47Q10-Data-Sheet-40002043E.pdf) |
| Links (URL) to Application Notes | [PIC18F27Q10](https://ww1.microchip.com/downloads/aemDocuments/documents/MCU08/ProductDocuments/DataSheets/PIC18F27-47Q10-Data-Sheet-40002043E.pdf) |
| Links (URL) to Code Examples | [PIC18F27Q10](https://ww1.microchip.com/downloads/aemDocuments/documents/MCU08/ProductDocuments/DataSheets/PIC18F27-47Q10-Data-Sheet-40002043E.pdf) |
| Links (URL) to External Resources | [PIC18F27Q10](https://ww1.microchip.com/downloads/aemDocuments/documents/MCU08/ProductDocuments/DataSheets/PIC18F27-47Q10-Data-Sheet-40002043E.pdf) |
| Production Unit Cost | $1.62 |
| Supply Voltage Range | 1.8 V - 5.5 V |
| Absolute Maximum Current for entire IC | 16 mA or 12 mA |
| Maximum GPIO Pin Current (Source/Sink) | 10 mA or 16 mA |
| 8-bit or 16-bit Architecture | 8-bit |
| Available IC Packages / Footprints | Surface Mount |
| Supports External Interrupts? | Yes |
| In-System Programming Capability and Type | Yes |
| Programming Hardware, Cost, and URL | MPLAB® PICkit™ 5 In-Circuit Debugger $94.99 |
| Works with MPLAB® X Integrated Development Environment (IDE)? | Yes |
| Works with Microchip Code Configurator? | Yes |


For more details, please see [Appendix G: Microcontroller Selection](MicrocontrollerSelection.md)

## Hardware Proposal
![Team_Schematic_V2](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156858888/e2dcfff7-42f2-44ea-b353-a81dcf872ced)

Figure 6: Hardware Proposal

### [Team Bill Of Materials](https://docs.google.com/spreadsheets/d/1tEgSocMg7p1WsBFgXyOm4MPM_7w9kUdD/edit?usp=sharing&ouid=118237344388299811111&rtpof=true&sd=true) 

For the hardware of this project, the team decided to break up the system inot four fifferent subsystems/ The subsystems were centered around the micro controllers, motors, tmeperature sensor, and humidity sensors. Those subsystems were designed by individual team members then combined into one team system schematic.

For more details, please see [Appendix H: Hardware Proposal](HardwareProposal.md)

## Software Proposal

![Team304_SoftwareProposal](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/135275139/08354b56-f796-4863-a2f2-b58312be190e)
Figure 7: Software Proposal

For the software of this project, the team decided to set up the code in a way that after the system is initialized and interrupts are enabled, the program will check on the temperature of the area, using the respective sensor via I2C communication, and update the user on the current temperature. After that, if the temperature is above a certain margin, the microcontroller will send a signal to the motor via SPI for it to raise a flag to alert the user about the higher temperatures, this flag will stay up until the temperature has decreased to below the alert margin. Lastly, the humidity sensor will check the humidity of the area and send the information to the user via I2C.

For more details, please see [Appendix I: SoftwareProposal](SoftwareProposal.md)

## [Appendix](Appendix.github.md)

Click to see all appendices. 

