![dove](https://github.com/coding-MJ-dev/Dove_public/assets/47417320/cc110999-ebd9-4410-9643-9c85b717eb73)


# Project Dove
: Rocket flight computer (Avionics)

: C++ / C project

: Hardware made by Felicity Rodricks

https://www.linkedin.com/in/felicity-rodricks-ab273320b/

: It had successful flight with Level2 high power Rocket made by Sam Cain

https://www.linkedin.com/in/samcain-copnall/

**It was a UTS Rocketry Team project, code can not be opened to public**


## Ejection Charge ##
: Electrical parachuate ejection 

: drogue parachute ejection condition - epogee detection

: Main parachute ejection condition - can be change by code

: sending real-time data to ground station


## LoRa radio Connection with Ground Station ##
: Get a real-time data 
: data includes
   - state(on pad> ascending> apogee...) 
   - pressure
   - raw Altitude
   - Altitude 
   - vertical velocity
   - gps


## State Machine ##
: state machine Based on collected flight data

: Using KalmanFilter to idealize the data

: it consisted of 5 state

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



