# Component Selection

### Team 314: Absolute Zero

### “We’re Up to Snow Good”

### Raj Kodithyala, Jillian Brooke, Alex Gutierrez, Briana Wells

## Power Source

| **Solution** | **Pros** | **Cons** |
| ---------------------------------------- | --------- | --------- |
| BA-5800 Military Class Battery | -High Ah (7.5 Ah)<br/>-Durable | -Expensive ($49.99)<br/>-Heavy<br/>-Large |
| Rayovac 9V Battery | -Cheap ($2.25)<br/>-Popular<br/>-Small | -Low Ah (0.8 Ah)<br/>-Non-Rechargeable |
| 18650 Battery | -High Ah (2.2 Ah)<br/>-Popular<br/>-Rechargeable-Cheap ($2.40) | -Large<br/>-Requires Charger |

**Choice: Option 3 (18650 Battery)**

**Rationale:** Rechargeable with high amperage capable of delivering the appropriate voltage and current to all the components.



## Voltage Regulator
| **Solution** | **Pros** | **Cons** |
| ---------------------------------------- | --------- | --------- |
| NCP1532MUAATXG | -Outputs 3.3V<br/>-Adjustable Output voltage<br/>-Cheap ($1.52) | -Max input voltage is 5V<br/>-No exterior legs for easy soldering<br/>-No exterior legs for easy soldering |
| TPS62745DSST | -Max input is 10V<br/>-Max output is 3.3V<br/>-Variable voltage output from 1.8 to 3.3V-Cheap ($2.09) | -No exterior legs for easy soldering |
| LM2575D2T | -Outputs 3.3V<br/>-Adjustable Output voltage<br/>-High Input Voltage Range (up to 40V)<br/>-Easy to use | -Expensive ($2.39)<br/>|

**Choice: Option 3 (LM2575D2T)**

**Rationale:**  - Voltage regulator handles high voltage inputs while outputting the required 3.3V. It is the most expensive of the group but the easiest to solder and integrate. 



## Fuse
| **Solution** | **Pros** | **Cons** |
| ---------------------------------------- | --------- | --------- |
| MFU0603FF01000P500 Fuse | -Handles up to 32V<br/>-1 Amp Limiter <br/>-Low Cost ($0.24)<br/>-Small (0603 Package) | -Hard to Replace<br/>-Blows out Quickly |
| ERB-RE2R00V Fuse | -Handles up to 32V<br/>-2 Amp Limiter<br/>-Low Cost ($0.27)<br/>-Small (0603 Package) | -Hard to Replace<br/>-Blows out Quickly |
| 0215002.MXP Fuse| -Handles up to 250V<br/>-2 Amp Limiter<br/>-Easy To Replace<br/>-Large | -Large<br/>-Requires Holder<br/>-Expensive |

**Choice: Option 3**
**Rationale:** This option is a reliable component with all the capabilities the team is looking for in terms of current limiting and circuit protection. While more expensive than the non-holder style fuses, the ability to quickly and easily replace this component is worth the extra expense in the eyes of the team. 



## DC Motor
| **Solution** | **Pros** | **Cons** |
| ---------------------------------------- | --------- | --------- |
| ROB-12429 Small Gearmotor | -Light (17.69 g)<br/>-Includes a gearbox (reduction ratio: 50)<br/>-Low Cost ($13.95)<br/>-Small (26 x 12 x 10mm)<br/>-Easy to attach to shaft (dent in the shaft) | -Small shaft length<br/>-Small mounting holes<br/>-Import Tariff |
| Planetary Gear Motors | -High torque (160mNm)<br/>-Low voltage (6V)<br/>-Easy to attach to shaft (dent in the shaft)<br/>Small (dia 16mm)<br/>-Mounting holes (M2) | -Expensive ($37.05)<br/>-Small shaft length |
| Sparkfun Motor | -Super Cheap ($1.20)<br/>-Low Voltage (7.2 V)<br/>-Gearbox (1:48) | -Large (70 mm x 36 mm)<br/>-Inconvenient shape<br/>-Small Shaft size|

**Choice: Option 1**

**Rationale:** We decided to go with the ROB-12429 DC Motor because it had a healthy balance between its size, weight, cost, and adaptability. It wasn’t too pricey for a quality DC motor, while still being small and lightweight. Its shaft design makes it easy to attach 3D-printed wheels and other 3D-printed components.



## Motor Driver
| **Solution** | **Pros** | **Cons** |
| ---------------------------------------- | --------- | --------- |
| IFX9201SGAUMA1 | -Cheap ($4.00)<br/>-High voltages (40 V)<br/>-Dual Motor Driver (2 half h-bridges)<br/>-Small (7.8 mm x 10mm)<br/>-Easy to use | -Lots of extra pins (5/12 are used) |
| TC642EOA713 | -Cheap ($2.23)<br/>-Easy to use<br/>-No wasted pins | -Can only drive single motor |
| UC2638DW | -Advanced functionality<br/>-Dual motor driver | -Expensive ($10.75)<br/>-Large (20mm x 6.6mm)<br/>-Lots of extra pins |

**Choice: Option 1 (IFX9201SGAUMA1)**

**Rationale:** We chose this dual-motor driver because of its cost-effectiveness and ease of use. Utilizing a dual half-H-bridge motor driver, this component lets us drive two motors with ease while not taking up a lot of PCB space. 



## Temperature Sensor
| **Solution** | **Pros** | **Cons** |
| ---------------------------------------- | --------- | --------- |
| TC74A0-3.3VCTTR | -3.3 Operating Voltage<br/>-Digital Signals<br/>-Cheap ($1.15)<br/>-Easy to use | -Tiny (1.9 x 1.2 mm) |
| TC74A0-5.0VCTTR | -5.0 Operating Voltage<br/>-Digital Signals<br/>-Cheap ($1.15)<br/>-Easy to use | -Tiny (1.9 x 1.2 mm)<br/>-Low Temperature Accuracy |
| TC74A0-3.3VAT | -3.3 Operating Voltage<br/>-Digital Signals<br/>-Easy to use | -Not I2C Viable<br/>-Not Surface Mount |

**Choice: Option 1 (TC74A0-3.3VCTTR)**

**Rationale:**  Option one is the most affordable, which works the best with the limited budget that the team is working in. Additionally, this component is the same one that the team will have worked with in class.



## Humidity Sensor
| **Solution** | **Pros** | **Cons** |
| ---------------------------------------- | --------- | --------- |
| HDC3022DEJR | -I2C Compatible<br/>-Humidity operating range from 0 to 100%<br/>-Low input voltage required (5.5Vmax)<br/>-High Accuracy (+-0.5%) | -Expensive ($5.61)<br/>-No exterior legs for easy soldering |
| HDC2080DMBR | -I2C Compatible<br/>-Humidity operating range from 0 to 100%<br/>-Low input voltage required (3.6Vmax) | -Expensive ($3.99)<br/>-No exterior legs for easy soldering |
| HTU31DI.C31DRH/T | -I2C Compatible<br/>-Humidity operating range from 0 to 100%<br/>-Low input voltage required (5.5Vmax) | -Expensive ($3.73)<br/>-No exterior legs for easy soldering |

**Choice: Option 3 (HTU31DI.C31DRH/T)**

**Rationale:**  Option three is the cheapest and has the same functionality as the rest of the sensors.

# Power Budget

| **Component Name** | **Part Number** | **Supply** | **#** | **Absolute** | **Total** |**Unit** |
| ------------------- | --------- | --------- |-------| --------- | --------- | --------- |
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
| 18650 Batteries | USE-18650 | 3.7V | 4 | 2200 | **2200** |  **mA**|

| **Component Name** | **Part Number** | **Supply** | **#** | **Absolute** | **Total** |**Unit** |
| ------------------- | --------- | --------- |-------| --------- | --------- | --------- |
