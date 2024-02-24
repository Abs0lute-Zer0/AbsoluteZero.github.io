# Software Proposal

### Team 314: Absolute Zero

### “We’re Up to Snow Good”

### Raj Kodithyala, Jillian Brooke, Alex Gutierrez, Briana Wells

![Team304_SoftwareProposal](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/135275139/08354b56-f796-4863-a2f2-b58312be190e)
Figure 1: Overall Software Proposal

For the software of this project, the team decided to set up the code in a way that after the system is initialized and interrupts are enabled, the program will check on the temperature of the area, using the respective sensor via I2C communication, and update the user on the current temperature. After that, if the temperature is above a certain margin, the microcontroller will send a signal to the motor via SPI to raise a flag to alert the user about the higher temperatures, this flag will stay up until the temperature has decreased to below the alert margin. Lastly, the humidity sensor will check the area's humidity and send the information to the user via I2C.

### Main Loop
![Mainloo drawio](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/135275139/377efa94-8829-475b-a5a8-8ff1adc0b6ad)

Figure 2: Main Loop Section

For the main loop portion, after the system has been initiated and the interrupters have been enabled the program will start by checking the temperature and updating the robot for every change, if the temperature gets higher up to a certain point, the flag will rise to alert the user to be aware and be prepared for the high temperatures. After that, the device will receive the humidity data, send it to the user, and repeat the process.

### Initialize System
![InitializeSystem drawio](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/135275139/edebc4a4-112c-4141-aade-297281e9acce)

Figure 3: Initialization of the system

The system would start, set the hardware registers, reset the internal variables, and establish communication with the sensors, motor drivers, and the ESP 32 via I2C, SPI, and EUSART.

### Motor Driver
![MotorFlag drawio](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/135275139/f5ebc115-6e44-46be-94bc-e2a2ca45b4aa)

Figure 4: Motordriver System

Once the temperature sensor detects the temperature to be above a specific range the microcontroller will communicate to the motor driver via SPI to rotate in one direction for 2 seconds before it turns itself off. Similarly, when the microcontroller senses the temperature no longer being in the danger zone, it will change the direction of the motor and move for 2 seconds before turning the motor off.

### Temperature and Humidity Sensor 
![CheckTemp drawio](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/135275139/98f0abf3-a42e-4a3b-9dc5-5195966ce810) ![CheckHumidity drawio](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/135275139/7bdf33a3-adfe-436c-bae9-ae683fce7dc6)

Figure 5: Temperature and Humidity Sensors Systems

The temperature and humidity sensor works by using I2C communications to send the data to the microcontroller and interpret it to figure out if is necessary for the motor system to run or not. In addition to this the information would then also be sent via EUSART to the ESP32 and OLED so that it can be displayed in the device as well.
