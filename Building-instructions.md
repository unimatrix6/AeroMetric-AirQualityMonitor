# Wiring
### Display

| Display Pin | ESP32 Pin |
| :--- | :---: |
| VCC | 5V |
| GND | GND |
| CS | GPIO5 |
| Reset | GPIO17 |
| DC/RS | GPIO16 |
| SDI(MOSI) | GPIO23 |
| SCK | GPIO18 |
| LED | GPIO33 |
| SDO(MISO) | GPIO19|

### Sensor
| Pin | Name | ESP32 Pin |
| :--- | :---: | ---: |
| 1 | VDD | 5V |
| 2 | GND | GND |
| 3 | SDA | GPIO21 |
| 4 | SCL | GPIO22 |
| 5 | SEL | Short to Ground |

# Setting up your Device
### 1.Option via Homeassistant (recommended)
1. Installing ESPHome Device Builder

To install the ESPHome Device Builder, click the following button:

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/_change/?redirect=supervisor_addon%2F%3Faddon%3D5c53de3b_esphome%26repository_url%3Dhttps%253A%252F%252Fgithub.com%252Fesphome%252Fhome-assistant-addon)


This should open the ESPHome app page; once you’re there, just click the INSTALL button:
Installation may take a moment. Once done, click “Start” and then click “Open Web UI”.

2. Adding a new Device
Click on the + New Device Button in the Bottom Left Corner
Then Click on "Advanced set up options" and choose import from File



