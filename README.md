# CrossRoad LAB MEGA 1284P

![1](https://user-images.githubusercontent.com/83240004/116134702-7c139a80-a6d0-11eb-828c-61c4d66212f6.png)

## GENERAL INFORMATION 

#### MEGA 1284P is an open-source microcontroller based on the ATmega1284P. It features 24 digital input/output pins (of which 6 can be PWM outputs), 8 analog input pins, a 16 MHz crystal oscillator, an ICSP pin header, a reset button, and an LED is connected to pin 13. To power the microcontroller you can use the 5 volts of the serial or from 7 volts to 35 volts from the Vin pin (use one of the two methods, not both together).

## CORE SPECIFICATION

| Syntax      | Description | 
| :----:        |    :----:   |
| Memory type      | Flash       |
| Memory dimension (KB)   | 128        | 
| CPU Speed (MIPS/DMIPS)      | 20       |
| SRAM (B)   | 16384        | 
| EEPROM/HEF (bytes)      | 4096       |
| Communication Devices   | 2-UART, 3-SPI, 1-I2C        | 
| PWM      | 6 PWM pin       |
| Timer   | 2x8-bit, 2x16-bit        | 
| Number of comparators      | 1       |
| Operating temperature (°C)   | -40 to 85        | 
| Operating voltage   | 1.8 to 5.5        |

## PINOUT

![MEGA1284P_pinout](https://user-images.githubusercontent.com/83240004/118370481-2b44e280-b5a8-11eb-859b-e33b96628943.png)

## LIBRARIES INSTALLATION

For download and installing libraries visit:
https://github.com/MCUdude/MightyCore#manual-installation

## HOW TO UPLOAD SKETCHES USING SERIAL PORT (UART)

First of all you need a USB TTL FTDI (like this https://t.ly/cMAf or this https://t.ly/RZF8) that will allow the sketch to be written to the microcontroller. First, however, preliminary operation must be carried out: 

- Burning the bootloader (visit this link for more information: https://www.arduino.cc/en/Tutorial/BuiltInExamples/ArduinoToBreadboard)

Connection between FTDI and MEGA 1284P:

| FTDI        |       |    MEGA 1284P   |
| :----:        |    :----:   |    :----:   |
| Vcc        |    <------->   |    5v   |
| Gnd        |    <------->   |    Gnd   |
| Tx        |    <------->   |    Rx   |
| Rx        |    <------->   |    Tx   |
| RTS/DTR        |    <------->   |    DTR   |

## SITE WHERE TO BUY PCB

If you are interested in buying the PCB you can consider supporting the project by purchasing it on: 
https://www.pcbway.com/project/shareproject/CROSSROAD_LAB_MEGA_1284P_REV__1_5.html

## PROJECT SITE

https://www.crossroadlab.org/projects/MEGA1284P.html
