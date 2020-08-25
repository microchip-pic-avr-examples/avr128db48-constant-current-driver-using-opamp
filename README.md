
<a href="https://www.microchip.com" rel="nofollow"><img src="images/microchip.png" alt="MCHP" width="300"/></a>

# AVR128DB48 Constant-Current Driver Using the Analog Signal Conditioning (OPAMP) Peripheral
<p align="left">
  <img width=800px height=auto src="images/setup.png">
</p>

A new feature introduced in the AVR® DB MCU is the Analog Signal Conditioning (OPAMP) peripheral. In this example, the OPAMP is used as a constant-current driver using a single external resistor. It can be used to drive a load such as LEDs, with constant current and not constant voltage. The OPAMP peripheral also provides the ability to adjust the current setting under firmware control. The configuration for this example can be seen in the figure above. For more information about setup and code, see the [application note](https://microchip.com/DS00003632).

## Related Documentation

* [AN3632 - Constant-Current Driver Using the Analog Signal Conditioning (OPAMP) Peripheral](https://microchip.com/DS00003632)
* AVR128DB48 Curiosity Nano User Guide (link will be added once available)
* [AVR128DB48 Device Page](https://www.microchip.com/wwwproducts/en/AVR128DB48)

## Software Used

* [Atmel Studio](https://www.microchip.com/mplab/avr-support/atmel-studio-7) 7.0.2397 or later
* Atmel Studio AVR-Dx_DFP version 1.3.67 or later
* For the MPLAB X version of this project, please go to [this repository](https://github.com/microchip-pic-avr-examples/avr128db48-constant-current-driver-using-opamp-mplab)
  
## Hardware Used

* [AVR128DB48 Curiosity Nano](https://www.microchip.com/wwwproducts/en/AVR128DB48)
* One resistor (value dependent on desired current)
* Load (LED, etc)

## Setup

* Connect the hardware together as seen in the schematic of the application note

## Operation
* Connect the AVR128DB48 Curiosity Nano to a computer using a USB cable
* Download the zip file or clone the example to get the source code
* Open the .atsln file with Atmel Studio
* Press *Start Without Debugging* (CTRL+ALT+F5) to run the application

## Conclusion
After going through this example you should have a better understanding of how to set up the OPAMP peripheral as a constant current driver for a load.

