# AeroMetric Air Quality Monitor

<img width="256" height="256" alt="Copilot_20260710_201810" src="https://github.com/user-attachments/assets/ca75e92b-65b9-4b6c-96cf-9ca603d3a6a3" />


A compact DIY air quality monitor built around an ESP32 and a Sensirion SEN54 sensor. The project is designed to display air quality data locally on a small color display and provide a simple, affordable platform for indoor air monitoring.

## 📊Recommended HA cards 



<a href="https://github.com/danielmigueltejedor/nodalia-cards">
  <img src="https://raw.githubusercontent.com/danielmigueltejedor/nodalia-cards/main/docs/images/nodalia-cards-header.png" alt="Nodalia Cards" width="350">
</a>




## 🛠️Materials

    
ESP-Wroom-32 DevKit

    
Sensirion SEN54 + Cables (needs to be bought extra)


3.5" ILI9488 SPI IPS Display  


Dupont Jumper Wires (Female/Female)


PerfBoard 5x7cm


(Female/Male) Pin header Set


Some Materials may not be available in your region.

Estimated Cost: 110€

## Building your device
Click the link for building instruction
https://github.com/unimatrix6/AeroMetric-AirQualityMonitor/blob/main/Building-instructions.md



## Project Overview

This monitor combines environmental sensing with a lightweight embedded controller to show air quality information in a compact form factor. It is intended as a practical and budget-friendly DIY build for home use, experiments, or further customization. It features a sleek and modern UI.

## 🎨 UI Overview

<img width="546" height="802" alt="Bildschirmfoto vom 2026-08-17 13-27-56" src="https://github.com/user-attachments/assets/f8021d07-dbe8-47d6-a0a5-a18701e1369c" />



- Sleek Modern User Interface
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
