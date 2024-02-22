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

The system would start, set the hardware registers, reset the internal variables, and establish communication with the SPI and I2C.

