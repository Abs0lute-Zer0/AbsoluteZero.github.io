# Microcontroller Selection

### Team 314: Absolute Zero

### “We’re Up to Snow Good”

#### Raj Kodithyala, Jillian Brooke, Alex Gutierrez, Briana Wells

## Preliminary Design Needs
| Design Considerations | PIC Option 1 | PIC Option 2 |PIC Option 3 |
| --------------------------------------- | --------- | --------- | --------- |
| How many GPIO Pins? | 35 | 35 | 25 |
| Built-in Analog to Digital Converter? How many? | Yes, 1 | Yes, 1 | Yes, 1 |
| Built-in Hardware PWM? How many? | Yes, 4 | Yes, 2 | Yes, 2 |
| Built-in I2C? SPI? How many? | Yes, 1 each | Yes, 1 each | Yes, 2 each |
| Built-in UART? How many? | Yes, 1 | Yes, 1 | Yes, 2 |

## Selection Table
| Microcontroller Considerations | PIC Option 1 | PIC Option 2 |PIC Option 3 |
| ---------------------------------------- | -------- | -------- | -------- |
| Part Number | PIC24FJ32MC104 | PIC24HJ16GP304 | PIC18F27Q10 |
| Link (URL) to the Product Page | [PIC24FJ32MC104](https://www.microchip.com/en-us/product/PIC24FJ32MC104#document-table) | [PIC24FJ32MC104](https://www.microchip.com/en-us/product/PIC24HJ16GP304) | [PIC18F27Q10](https://ww1.microchip.com/downloads/aemDocuments/documents/MCU08/ProductDocuments/DataSheets/PIC18F27-47Q10-Data-Sheet-40002043E.pdf) |
| Links (URL) to Data Sheets | [PIC24FJ32MC104](https://ww1.microchip.com/downloads/aemDocuments/documents/OTH/ProductDocuments/DataSheets/30009997e.pdf) | [PIC24FJ32MC104](https://ww1.microchip.com/downloads/aemDocuments/documents/OTH/ProductDocuments/DataSheets/70289J.pdf) | [PIC18F27Q10](https://ww1.microchip.com/downloads/aemDocuments/documents/MCU08/ProductDocuments/DataSheets/PIC18F27-47Q10-Data-Sheet-40002043E.pdf) |
| Links (URL) to Application Notes | [PIC24FJ32MC104](https://www.microchip.com/en-us/product/PIC24FJ32MC104#document-table) | [PIC24FJ32MC104](https://www.microchip.com/en-us/product/PIC24HJ16GP304) | [PIC18F27Q10](https://ww1.microchip.com/downloads/aemDocuments/documents/MCU08/ProductDocuments/DataSheets/PIC18F27-47Q10-Data-Sheet-40002043E.pdf) |
| Links (URL) to Code Examples | [PIC24FJ32MC104](https://www.microchip.com/en-us/product/PIC24FJ32MC104#document-table) | [PIC24FJ32MC104](https://www.microchip.com/en-us/product/PIC24HJ16GP304) | [PIC18F27Q10](https://ww1.microchip.com/downloads/aemDocuments/documents/MCU08/ProductDocuments/DataSheets/PIC18F27-47Q10-Data-Sheet-40002043E.pdf) |
| Links (URL) to External Resources | [PIC24FJ32MC104](https://www.microchip.com/en-us/product/PIC24FJ32MC104#document-table) | [PIC24FJ32MC104](https://www.microchip.com/en-us/product/PIC24HJ16GP304) | [PIC18F27Q10](https://ww1.microchip.com/downloads/aemDocuments/documents/MCU08/ProductDocuments/DataSheets/PIC18F27-47Q10-Data-Sheet-40002043E.pdf) |
| Production Unit Cost | $4.13 | $4.60 | $1.62 |
| Supply Voltage Range | 3.0 V - 3.6 V | 3.0 V - 3.6 V | 1.8 V - 5.5 V |
| Absolute Maximum Current for entire IC | 16 mA or 12 mA | 16 mA or 12 mA | 16 mA or 12 mA |
| Maximum GPIO Pin Current (Source/Sink) | 10 mA or 16 mA | 10 mA or 16 mA | 10 mA or 16 mA |
| 8-bit or 16-bit Architecture | 16-bit | 16-bit | 8-bit |
| Available IC Packages / Footprints | Surface Mount | Surface Mount | Surface Mount |
| Supports External Interrupts? | Yes | Yes | Yes |
| In-System Programming Capability and Type | Yes | Yes | Yes |
| Programming Hardware, Cost, and URL | MPLAB® PICkit™ 5 In-Circuit Debugger $94.99 | MPLAB® PICkit™ 5 In-Circuit Debugger $94.99 | MPLAB® PICkit™ 5 In-Circuit Debugger $94.99 |
| Works with MPLAB® X Integrated Development Environment (IDE)? | Yes | Yes | Yes |
| Works with Microchip Code Configurator? | Yes | Yes | Yes |

## Advantages & Disadvantages
| Category | PIC Option 1 | PIC Option 2 |PIC Option 3 |
| ---------------------------------------- | -------- | -------- | -------- |
| Overall Pros | -4 PWMs<br/>-16 Bit Chip<br/>-Big Size (1.0 cm x 1.0 cm)| -Handles high current on its pins (up to 16mA)<br/>-16 bit Chip| -Cheap ($<br/>-Easy to Program |
| Overall Cons | -Expensive programmer| -2 PWMs<br/>-Expensive programmer | -1 PWM<br/>-8-Bit Chip<br/>-Small Size (0.8 cm x 0.8 cm) |
| Ranking | 2 | 3 | 1 |

## Final Selection
### Final Microcontroller Choice: PIC18F27Q10T-I/SO
**Rationale:** We decided to choose the PIC24FJ32MC104 because it has at least one SPI, I2C, ADC, and PWM connections. Furthermore, it is also the cheapest microcontroller out of the three and easy to program. 
