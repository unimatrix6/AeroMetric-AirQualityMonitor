# 🔌️Wiring
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

# 🔧Building the PCB
I am very sorry for not including a wiring diagram. I am not skilled enough for that. Hopefully the tables and the following pictures are enough 


<p align="left">
  <img src="https://github.com/user-attachments/assets/27a71363-d9c9-42eb-b477-6109597c1e4b" alt="Alt text" width="330">
</p>
<p align="left">
  <img src="https://github.com/user-attachments/assets/0ec88f09-ffcd-4f96-9706-148b13416ba7" alt="Alt text" width="330">
</p>


# 🖨3D printing your Enclosure


# Setting up your Device
### 1.Option via Homeassistant (recommended)
1. Installing ESPHome Device Builder

To install the ESPHome Device Builder, click the following button:

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/_change/?redirect=supervisor_addon%2F%3Faddon%3D5c53de3b_esphome%26repository_url%3Dhttps%253A%252F%252Fgithub.com%252Fesphome%252Fhome-assistant-addon)


This should open the ESPHome app page; once you’re there, just click the INSTALL button:
Installation may take a moment. Once done, click “Start” and then click “Open Web UI”.

2. Adding a new Device
Click on the + New Device Button in the Bottom Left Corner
Then Click on "Advanced set up options" and choose "import from File"
Choose the file "AeroMetric-AQM-firmware" located in the Firmware folder

3. Uploading to your ESP32
Connect your ESP8266 or ESP32 microcontroller directly to your computer or Home Assistant host using a data-transfer USB cable.
Click Install on the device card.
Choose Plug into this computer (uses your web browser's WebUSB feature) or Plug into the server (if connected directly to your Home Assistant machine).
Select the correct COM port and wait for ESPHome to compile and flash the firmware. (Compiling for the first time can take longer than 30 minutes)

Note: Once this initial USB flash is complete, future updates can be sent wirelessly over-the-air (OTA) by selecting the Wirelessly installation option.
Remember to configure WIFI either by setting a Wifi secret via ESPHome Device Builder before doing the first installation or by configuring the Wifi on https://web.esphome.io

For More Information Visit https://esphome.io/guides/getting_started_hassio/

### 2. Option via Desktop app

1. Go to https://esphome.io/install/
2. install the version that you need for your operating System
3. When you first launch the ESPHome Device Builder on macOS, Windows, or Linux, it automatically configures its built-in Python environment in the background and opens the dashboard in your default browser. For quick access, the ESPHome icon nests into your macOS menu bar, Windows notification area, or Linux system tray. From this icon, you can instantly open the dashboard, check for updates, or close the app. NOTE: Some Linux desktops (notably GNOME without a tray extension) don’t show tray icons at all. The app still runs; use the dashboard in your browser.
4. then just set up your device just like described in Option 1


