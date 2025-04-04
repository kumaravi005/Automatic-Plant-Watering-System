## Automatic Plant Watering System using Arduino

This project is a simple and smart solution to keep your plants healthy – even when you're not around!  
Built using **Arduino Uno**, **soil moisture sensor**, and a **small DC water pump**, this system **automatically waters the plant** when the soil gets dry.

## Components Used
Arduino Uno - Microcontroller that controls the system 
Soil Moisture Sensor - Detects how wet or dry the soil is 
Relay Module - Switches the pump ON/OFF based on signal from Arduino
Water Pump (DC) - Pumps water to the plant when needed
16x2 LCD Display (I2C) - Shows soil moisture(in %) and pump status
Battery / Power Supply - Powers the whole system
Jumper Wires - Circuit connections

## How It Works

1. The **moisture sensor** checks the soil's moisture level.
2. Arduino reads the analog value from the sensor.
3. If the soil is **too dry**, Arduino triggers the **relay**, which turns ON the **water pump**.
4. Water is pumped into the soil until the moisture is sufficient(moist>30%) based on the plant required.
5. The **LCD display** shows whether the soil moisture level(in %) and the status of the pump.
   
 ## Future Improvements

- Add Wi-Fi module (NodeMCU) for IoT control 
- Add mobile app or notification system 
- Use solar panel for green power
- Add Sprinklers for uniform farming field

## Created By

**Avinash Kumar**  
B.Tech CSE(1st Year)
avinash922472@gmail.com  

   ![Image](https://github.com/user-attachments/assets/1f71aeee-27e9-45a7-b198-2e1b91591740)

   https://github.com/user-attachments/assets/be382368-14d6-45b9-904b-d69a33771761
   
