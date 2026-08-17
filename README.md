# AeroMetric Air Quality Monitor

<img width="256" height="256" alt="Copilot_20260710_201810" src="https://github.com/user-attachments/assets/ca75e92b-65b9-4b6c-96cf-9ca603d3a6a3" />


A compact DIY air quality monitor built around an ESP32 and a Sensirion SEN54 sensor. The project is designed to display air quality data locally on a small color display and provide a simple, affordable platform for indoor air monitoring.

## 📊Recommended HA cards 

<img src="https://raw.githubusercontent.com/danielmigueltejedor/nodalia-cards/main/docs/images/nodalia-cards-header.png" alt="Nodalia Cards" width="350">

## 🛠️Materials

    
ESP32 DevKitC

https://tinyurl.com/shoppinglistesp32dev
    
Sensirion SEN54

https://tinyurl.com/sen-54-sensor

4" ILI9488 SPI IPS Display  

https://tinyurl.com/Ili9488-Tft

Dupont Jumper Wires (Male/Female set)

https://tinyurl.com/dupont-jumper-wires

PerfBoard 5x7cm

https://tinyurl.com/perfboard-902348

Female Pin headers 1x5

https://tinyurl.com/femalepinheaders

Some Materials may not be available in your region.

## Price list
45.33 € amazon

43.75 € reichelt

15.04 € amazon

total price 104.12 € 

## Project Overview

This monitor combines environmental sensing with a lightweight embedded controller to show air quality information in a compact form factor. It is intended as a practical and budget-friendly DIY build for home use, experiments, or further customization.

## 🎨 UI Overview

<img width="546" height="802" alt="Bildschirmfoto vom 2026-08-17 13-27-56" src="https://github.com/user-attachments/assets/f8021d07-dbe8-47d6-a0a5-a18701e1369c" />



- Sleek Modern User Interface in the Look of Nodalia Cards
- Coded in YAML with LVGL for easy integration with ESPHome
- Easy identification of values

## Features

- Measures air quality parameters using the SEN54 sensor
- Displays readings on a color TFT screen
- Runs on an ESP32 for Wi-Fi and embedded processing
- Easy to expand with additional sensors or networking features

## Build Notes

- The ESP32 acts as the main controller.
- The SEN54 provides the environmental sensor data.
- The ILI9488 display is used for local visualization.
- ESP Home is used for Simple Smarthome integration.
- DIY PCB using a Perfboard keeps the Build tidy and durable.
