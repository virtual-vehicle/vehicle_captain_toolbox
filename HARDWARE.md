# vehicleCAPTAIN - Hardware
You may use any hardware you already have. Most components of the [vehicleCAPTAIN](https://github.com/virtual-vehicle/vehicle_captain) can be fit independent of hardware.

## Recommendation
For our projects we were successful with the following setups

### vehicleCAPTAIN - mPCI-E/M.2 Quad Expander
We designed a platform that can host up to four mPCI-E/M.2 modules simultaneously via a USB hub.
- TODO Figure Quad Expander

The Quad Expander is controlled by a Raspberry Pi 4, which is running the [routing core](https://github.com/virtual-vehicle/vehicle_captain_routing_core).
- TODO Figure complete vehicleCAPTAIN

If you are interested, please contact <contact_info>.

### vehicleCAPTAIN - Demo Board
The demo board allows to host one mPCI-E or one M.2 module
- TODO Figure demo board
- 
If you are interested, please contact <contact_info>.

### Unex SOM301-E
[https://www.unex.com.tw/](Unex) provides system-on-modules (SOMs) for V2X communication.

Advantages:
- one software library for sending and receiving
- one software library for decoding and encoding of msgs
- cheap compared to fully implemented competitors
- access to most parts of the software stack

Disadvantages:
- precompiled libraries only (no 64bit support)
- limited amount of BTP ports 
- propretary standard for power (small mPCI-E adapter needed)
