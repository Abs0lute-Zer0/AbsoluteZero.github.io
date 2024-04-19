# Software Implementation
### Team 314: Absolute Zero

### “We’re Up to Snow Good”

#### Raj Kodithyala, Jillian Brooke, Alex Gutierrez, Briana Wells

![Team304_SoftwareProposal_ drawio](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156485138/a343fc5c-d782-4aae-ade5-c1c747d78305)
Figure 7: Software Proposal

For the software of this project, the team decided to set up the code in a way that after the system is initialized and interrupts are enabled, the program will check on the temperature of the area, using the respective sensor via I2C communication, and update the user on the current temperature. After that, if the temperature is above a certain margin, the microcontroller will send a signal to the motor via SPI for it to raise a flag to alert the user about the higher temperatures, this flag will stay up until the temperature has decreased to below the alert margin. Lastly, the humidity sensor will check the humidity of the area and send the information to the user via I2C. Additionally, there is a timer that increments by 1 second, every 10 seconds an interrupt (Blink) is sent. This interrupt turns off the eye LEDs for 1 second, making the appearance of a blink.

The team decided to organize the process this way to optimize the functionality of the device and to ensure that the order of actions would be executed in a way that would optimize the mechanisms of the device. Additionally, by organizing the functions in such a way, ensures that systems/functions do not over-lap and disrupt other actions of the device. 

### Top 5 Changes

Over the semester and subsequently the project, changes were taken to; ensure simple user input, the performance of the device, and the functionality of the code. In doing so 5 major changes were put in place to ensure such:

* Additional of an Interrupt: 
  * To ensure that the device followed the project guidelines and met all required sections, the team found that the inclusion of an interrupt was required. Initially, the team tried implementing an interrupt to the printing of the data, however, when this failed the team looked for other systems/functions to change. In doing so the team decided to implement an interrupt for every 10 seconds the LED eyes would "Blink", as described in the above diagram in the "Blink section". 
* Print via ESP32
  * When starting this project the team originally was going to have the information collected from the data be sent to the user via an OLED, however, the team quickly found issues with the OLED when doing an associated assignment. Additionally, the team then worked on an activity that worked to send information via wifi over the ESP32, such a function is described int he diagram above.
* Added a Timer Function:
  * 
* Separate the Sensor Functions:
  *
* Correct/Layout Function for Motor Driver
  *


_If you were to create a "Version 2.0" of your software design, discuss what could be improved in the software design and why it should be improved. Use the UML diagrams above to support the discussion. Consider using a graphical representation of the flow that your updated software would take. What functions would you create? How would you divide up your code? How would you improve its debuggability? What peripherals or system features would you like to use or set up to make your system more reliable, stable, functional, or robust? How would you simplify, improve, or update your protocol design to support this in software? (½ page minimum)_

_Final MQTT topic table and all C/C++ code that your team has written or modified, and screenshots of your MCC configuration. (in appendix)_

_CHANGE THE LINK TO APPENDIX/NEW APPENDIX_
