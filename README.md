# Cybersecurity : CSN150
Project: ESP32-CAM Setup and Wi-Fi Scanner

## Purpose
The purpose of this project is to set up the ESP32-CAM using Arduino IDE on my MacBook. I will use the Wi-Fi Scanner program to find nearby Wi-Fi networks and learn how the ESP32-CAM works.

## Equipment
## breadboard
## jumper wires
## MacBook with Arduino IDE installed
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Links to documentation and tools

##### Video 1: 

##### Other Links: 

- [Arduino IDE Download](https://www.arduino.cc/en/software/)

##### AI GPTs used

## Steps I followed
1. I opened GitHub and forked my professor's repository.
2. I edited the README file to document my ESP32-CAM project.
3. I opened Arduino IDE on my MacBook and updated it to version 2.3.11.
4. I installed the ESP32 board package by Espressif Systems.
5. I selected AI Thinker ESP32-CAM as my board.
6. I connected my ESP32-CAM to my MacBook using a USB cable.
7. I selected the USB serial port in Arduino IDE.
8. I uploaded a test sketch to the ESP32-CAM. The output ended with "Hard resetting via RTS pin.
9. uploaded the Blink sketch and saw hard resetting via RTS pin.
10. I changed the delay number in the code. Smaller numbers like 200 make it blink faster. Bigger          numbers like 2,000 make it blink slower.
## ESP32-CAM Camera Setup
### Project Description
In this lab, I installed the camera software on my ESP32-CAM using Arduino IDE. I connected the camera to my Wi-Fi network and opened the camera page in Safari. I tested the live video and successfully saw myself on the screen.

### Steps I Followed
1. I connected my ESP32-CAM to my MacBook using a USB cable.
2. I opened Arduino IDE and selected AI Thinker ESP32-CAM.
3. I opened the CameraWebServer example.
4. I selected the AI Thinker camera model in board_config.h.
5. I entered my Wi-Fi name and password in the code.
6. I uploaded the camera program to my ESP32-CAM.
7. I opened Serial Monitor and set the baud rate to 115200.
8. I copied the camera IP address and opened it in Safari.
9. I clicked Start Stream and tested the camera.
10. I successfully saw myself on the camera screen.
## Problems and Solutions
1. I could not find AI Thinker ESP32-CAM in the board list.
2. I opened Boards Manager, installed esp32      by Espressif Systems, and then the board appeared.

**Problem:** E (485) camera: Camera probe failed with error 0x105(ESP_ERR_NOT_FOUND)
Camera init failed with error 0x105
**Solution:**
### Results

I successfully installed the camera firmware on my ESP32-CAM. The camera connected to my Wi-Fi network, and I opened the CameraWebServer page in Safari. I clicked Start Stream and saw live video of myself. The camera worked successfully.
### Example Problem
**Problem:** Arduino code will not load on ESP32 Cam.
**Solution:** Camera drivers were incorrect I needed to install the driver: [https://www.wch-ic.com/downloads/CH341SER_ZIP.html](https://github.com/martin-ger/esp32_nat_router).  I used file, "CH341SER.ZIP" and it worked.

## Final Report
