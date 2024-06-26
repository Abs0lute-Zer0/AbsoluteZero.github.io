# Hardware Implementation

### Team 314: Absolute Zero

### “We’re Up to Snow Good”

### Raj Kodithyala, Jillian Brooke, Alex Gutierrez, Briana Wells

## Final Schematic
![image](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156540341/90f9ca63-4097-418a-81f4-449eb497d122)

**Functionality**: The schematic features a temperature and humidity sensor to output weather station data to the MQTT server. It is set up to have a motor-controlled response utilizing a motor driver. Furthermore, the schematic contains four LEDs and a piezo buzzer. The motor will spin a flag and the buzzer will buzz when the temperature or humidity reads too high.

**Design and Decision-Making Process**: The team wanted to go beyond the standard project requirements. To further warn the user of extreme temperatures, a buzzer was implemented to provide an audio warning system. The motor is utilized to spin the flag providing a visual warning system. The combination of visual + audio warning systems will quickly alert the user to unsafe weather conditions. The motor will be provided with an external 9V power supply to sufficiently power and run the motor holding the flag. The LEDs provided in the circuit will turn on to indicate to the user that the system is powered up and fully functional. 

| **PCB Top View** | **PCB Bottom View** |
| ------------ | -------- |
|![image](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156540341/5dbf0915-0d06-4830-b0f5-ce3e7b6feaa4) |![image](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156540341/9350fd72-87bc-490a-a089-1febbcbc72de)|

| **PCB Top View** | **PCB Bottom View** |
| ------------ | -------- |
|![image](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156540341/d674856b-be0b-44fe-a3ad-abb45b48dfd1)|![image](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156540341/7e1defe4-4ddd-4f27-9354-725e57bb4b9c)|

**Version 2.0 Changes**: The main changes for version 2.0 occur on the PCB design. The components are currently spaced out, leaving a lot of empty space on the PCB. A smaller PCB design will allow a smaller construction of the final product making everything more compact. Some other minor changes include removing the wire mess on the final schematic. Replacing each wire with a symbol annotation will allow any viewer to easily identify the components and how everything is connected to the microcontroller. Another small change is to replace J15 with a piezo buzzer image so that the user that those two pins are connected to a piezo buzzer.

# [Team Bill Of Materials](https://docs.google.com/spreadsheets/d/1tEgSocMg7p1WsBFgXyOm4MPM_7w9kUdD/edit?usp=sharing&ouid=118237344388299811111&rtpof=true&sd=true) 
![Team_BillOfMaterials xlsx-Sheet1-1](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/135275139/3e3da93b-bb45-497c-af5e-22185401c795)



