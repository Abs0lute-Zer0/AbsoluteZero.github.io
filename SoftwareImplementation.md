# Software Implementation
### Team 314: Absolute Zero

### “We’re Up to Snow Good”

#### Raj Kodithyala, Jillian Brooke, Alex Gutierrez, Briana Wells

![Team304_SoftwareProposal_ drawio](https://github.com/Abs0lute-Zer0/AbsoluteZero.github.io/assets/156485138/a343fc5c-d782-4aae-ade5-c1c747d78305)
Figure 7: Software Proposal

For the software of this project, the team decided to set up the code in a way that after the system is initialized and interrupts are enabled, the program will check on the temperature of the area, using the respective sensor via I2C communication, and update the user on the current temperature. After that, if the temperature is above a certain margin, the microcontroller will send a signal to the motor via SPI for it to raise a flag to alert the user about the higher temperatures, this flag will stay up until the temperature has decreased to below the alert margin. Lastly, the humidity sensor will check the humidity of the area and send the information to the user via I2C. Additionally, there is a timer that increments by 1 second, every 10 seconds an interrupt (Blink) is sent. This interruption turns off the eye LEDs for 1 second, making the appearance of a blink.

The team decided to organize the process this way to optimize the functionality of the device and to ensure that the order of actions would be executed in a way that would optimize the mechanisms of the device. Additionally, organizing the functions in such a way, ensures that systems/functions do not over-lap and disrupt other actions of the device. 

### Top 5 Changes

Over the semester and subsequently the project, changes were taken to; ensure simple user input, the performance of the device, and the functionality of the code. In doing so 5 major changes were put in place to ensure such:

* Additional of an Interrupt: 
  * To ensure that the device followed the project guidelines and met all required sections, the team found that the inclusion of an interrupt was required. Initially, the team tried implementing an interrupt to the printing of the data, however, when this failed the team looked for other systems/functions to change. In doing so the team decided to implement an interrupt for every 10 seconds the LED eyes would "Blink", as described in the above diagram in the "Blink section". 
* Print via ESP32
  * When starting this project the team originally was going to have the information collected from the data be sent to the user via an OLED, however, the team quickly found issues with the OLED when doing an associated assignment. Additionally, the team then worked on an activity that worked to send information via wifi over the ESP32, such a function is described in the diagram above.
* Added a Timer Function:
  * As part of the interrupt the team needed to create a timer function that would increment according to the desired result. As such a time was created using the in-program functions and syntax.
* Separate the Sensor Functions:
  * To get the system to run with as few complications as possible the team worked to separate the sensor code, as in separating the two purposes into two separate in-code functions.
* Correct/Layout Function for Motor Driver
  * One of the biggest challenges for this project was the prospect of getting the motor driver function working. The final iteration of the software saw the use of counters and a separate function to successfully run the code, as seen in the above diagram.


### Areas of Improvement

One of the most important components of this project was the software which was used to execute the functions that the team desired for the project to execute. To formulate the code that was used in the final device, the team pulled from all of the in-class assignments and code practice that was required throughout the semester. Such as the temperature sensor code being pulled from the Advance Serial Communication ICC, along with the basis of the motor driver code. However, just pulling from the in-class work wasn’t enough, the team also had to branch out and look for information in other ways, such as through networking and Microchip resources. If the team was presented with another opportunity to create the software design, there are a few improvements that the group could implement. One of the biggest improvements would have been to have started by improving the flow of the program. While the current iteration of the code is well written and works the flow of the user-defined functions may not be in an order that would be well understood by an external reviewer. Additionally, the code should’ve included more notes on the function of each line and their relevance to the actions of the device. In future iterations, it would be desirable to see a function that prints the values exported to wifi via the ESP32 in a more visually appealing format. As for the organization of the code, it would follow a structure more similar to the flow of the software diagram. To improve the debuggability of the team’s current code, more notes should be included in the main while loop, in which the individual user-defined functions are called, to better label which functions to snooze when debugging others. If there was a way to have better controlled the motor’s speed that would have been an improvement over the current model. Overall, throughout this project, the team has all grown in their understanding of software in PIC and are satisfied with the final product that was presented.

For more information about the specifics of the code/set up click here: [Appendix K: FinalCode&Settup](FinalCode&Settup.md)

To See the original design, the Hardware Proposal: [Appendix I: Software Proposal](SoftwareProposal.md)

