# GAS_SENSOR_I2C
The Gas Sensor Modular is a highly adaptable gas detection module designed for seamless integration into various applications. Built around the MQ series sensors, this module allows users to replace the gas sensor with any compatible MQ sensor, making it versatile for detecting different gases such as CO, CO₂, NH₃, CH₄, LPG, and more.




This Gas Sensor Modular is an ideal solution for engineers, developers, and researchers looking to implement gas sensing capabilities into their projects efficiently.


## Table of Content

* [Product Specsification](#product-specsification)
* [Technical Spesification](#technical-spesification)
* [Applications](#applications)
* [Advantages](#advantages)
* [Priview Hardware](#priview-hardware)
* [Documentation](#documentation)
  * [Pinout Diagram](#pinout-diagram)
  * [Dimension](#dimension)
  * [BOM](#bom)
  * [Schematic](#schematic0)
  * [Example Program](#examples-program)
* [FAQ](#FAQ)

## Product Specsification
- Interchangeable MQ Series Sensor: Easily swap out the MQ sensor to detect different gases without modifying the PCB.
- I2C Communication Output: Simplifies integration into microcontroller-based systems, reducing the need for multiple analog input pins.
- Built-in Microcontroller: Reads the analog output of the MQ sensor and processes the data.
- Analog-to-Digital Converter (ADC): Converts the analog signal from the MQ sensor into a digital value for precise readings.
- Potentiometer-Adjustable Trigger Threshold: Users can set a specific threshold value, allowing the module to provide a binary digital output based on gas concentration.
- Dual Data Output via I2C:
- Analog Value: Represents the raw sensor reading.
- Digital Value: Indicates whether the gas concentration exceeds the set threshold.

## Technical Spesification

| Features                           | Value                |  
| ---------------------------------- | -------------------- |
| Microcontroller                    | LGT8F328P            |
| Communication                      | I2C                  |
| PSU                                | 5V                   |

- Sensor Compatibility: MQ series gas sensors (MQ-2, MQ-3, MQ-4, MQ-5, MQ-7, etc.).
- Microcontroller: Integrated for analog signal processing.
- Interface: I2C protocol for easy data communication.
- Power Supply: 5V DC.
- Adjustable Sensitivity: Using an onboard potentiometer.
- Dimensions: Compact and modular for easy integration.

## Applications
- Air quality monitoring
- Industrial gas detection
- Smart home automation
- IoT-based environmental sensing
- Safety and hazard detection systems

# Advantages
- Modular Design – Easily replace MQ sensors for different gas detection needs.
- I2C Communication – Simplifies connection to microcontrollers and embedded systems.
- Dual Output – Provides both analog and digital values for versatile applications.
- User Adjustable Threshold – Allows customization based on required sensitivity levels.

## Preview Hardware
<p align="center">
  <img src="DOC/gas_sensor_i2c_1.png" width="75%" height="75%">
  <img src="DOC/gas_sensor_i2c_2.png" width="75%" height="75%">
</p>


## Documentation
### PINOUT


### Dimension
- [Dimension]()
### BOM
- [BOM]()
### Schematic
- Not Available
### Example Program
- [Example Program]()

