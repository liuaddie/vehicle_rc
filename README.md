# vehicle_rc
Vehicle Remote Control
Work in Progress, please join me!
## Objective
Control a toy vehicle with a outdated driving wheel controller.
Save the Landfill, save the environment.
## Methods
This is a development project, there may be more than one method.
Let's start with Method 1 (M001).
### Method 1 (M001):
Hack both vehicle and controller completely.
Use MCU + Motor Drivers to control the vehicle.
Use MCU + Sensors to get input from the controller.
Build a wireless connection between vehicle and controller.
Vechicle will be server side.
Controller will be client side.
#### M001 Workflow
- Deisgn Electricity Power of the Toy Vehicle
  - Batteries Voltage (Power Source)
  - Toy Vehicle Motor/Servo Voltage
  - Microcontroller(MCU) Voltage
  - Wireless TX/RX Voltage
  - Up/Down DC Convertor(s)
- Deisgn Electricity Power of the Driving Wheel Controller
  - Batteries Voltage (Power Source)
  - Controller Voltage (TBC, Need to detach to check the sensors)
  - Microcontroller(MCU) Voltage
  - Wireless TX/RX Voltage
  - Up/Down DC Convertor(s)
- Wire the board of server side, Power + MCU + Wireless + Motor Driver(s)
- Put the board of server side into the Toy Vehicle
- Wire the board of client side, Power + MCU + Sensors
- Put the board of client side into the Controller
- Build Wirless Connection
- Code & Play
#### M001 Specifications
- Toy Vehicle
  - Unknown
- Outdated Driving Wheel Controller
  - Logitech GT FORCE Racing Wheel for GRAN TURISMO 3 (Playstation 2)
  - https://imgur.com/a/1aqwTfa
- Server & Client Side Microcontroller
  - Arduino mini pro 3.3v ATMega328
- Server Side Wireless Tx/Rx
  - NRF24L01+ Wireless Module
  - TMRh20 RF24 Library https://github.com/nRF24/RF24
- Server Side Motor/Servo Driver
  - TBC
- Client Side Motor/Servo Driver
  - TBC
## Test
Do some test before deciding hardware.
### Test1 (T001)
