# vehicleCAPTAIN - Hardware
You may use any hardware you already have. Most components of the [vehicleCAPTAIN](https://github.com/virtual-vehicle/vehicle_captain) toolbox can be fit independent of hardware.

## Recommendation
If you are interested in acquiring a development platform from [us](https://www.v2c2.at/), please contact our hardware expert [Peter Sammer](https://github.com/solderdev).

[Our](https://www.v2c2.at/) projects use the following hardware configurations.


### vehicleCAPTAIN - Development Kit v3
The **Development Kit v3** hosts a single mPCI-E/M.2 module. This module is intended to be a V2X module, with V2N communication done via the Ethernet port of the computing module.
![vehicleCAPTAIN - Open](res/hardware/vehicle_captain_dev_kit_gen3.png "vehicleCAPTAIN - Development Kit Gen3")

### vehicleCAPTAIN - QuadModule Development Kit
The **QuadModule development kit** hosts up to four mPCI-E/M.2 modules simultaneously.
![vehicleCAPTAIN - Closed](res/hardware/vehicle_captain_closed.jpeg "vehicleCAPTAIN - Closed")

![vehicleCAPTAIN - Open](res/hardware/vehicle_captain_open.png "vehicleCAPTAIN - Open")

### vehicleCAPTAIN - Demo Board
The demo board allows to host one mPCI-E or one M.2 module
![vehicleCAPTAIN Demo Board - Closed](res/hardware/vehicle_captain_demo_board_closed.jpeg "vehicleCAPTAIN Demo Board - Closed")

### Unex SOM301-E
[Unex](https://www.unex.com.tw/) provides system-on-modules (SOMs) for V2X communication.

Advantages:
- one software library for sending and receiving
- one software library for decoding and encoding of msgs
- cheap compared to fully implemented competitors
- access to most parts of the software stack

Disadvantages:
- limited amount of BTP ports 
