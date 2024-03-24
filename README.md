![dove](https://github.com/coding-MJ-dev/Dove_public/assets/47417320/cc110999-ebd9-4410-9643-9c85b717eb73)


# Project Dove
: Rocket flight computer (Avionics)

: C++ / C project

**Part of the UTS Rocketry Team project; code is not open to the public**


## Ejection Charge ##
: Electrical parachute ejection system 

: Drogue parachute ejection condition: apogee detection

: Main parachute ejection condition: configurable via code

: Real-time data transmission to the ground station


## LoRa radio Connection with Ground Station ##
Provides real-time data, including: 
   - state(on pad> ascending> apogee...) 
   - pressure
   - raw Altitude
   - Altitude 
   - vertical velocity
   - GPS


## State Machine ##
: Based on collected flight data

: Uses Kalman Filter to refine the data

: Consists of 5 states:

0. idle
1. ascending
2. apogee
3. descending
4. landed

  
## Components ##
1. microcontroller(MCU) - ESP32

https://www.snapeda.com/parts/ESP32-WROOM-32E/Espressif%20Systems/view-part/?ref=search&t=ESP32

2. LoRa radio - RFM9XW

https://www.snapeda.com/parts/RFM95W-915S2/RF%20Solutions/view-part/?ref=search&t=Lora%20module

3. GPS -  l80-m39 

https://www.snapeda.com/parts/L80-M39/Quectel/view-part/?ref=quectel_in&t=l80-m39&con_ref=N

4. Altimeter(barometer) - MS5607

https://www.snapeda.com/parts/MS560702BA03-50/TE%20Connectivity/view-part/?ref=search&t=MS5607



## Tool ##
1. VS code
3. Platform IO



