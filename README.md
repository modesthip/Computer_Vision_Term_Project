# Object Detection and Surveillance using Arduino

This repository contains the term project for the Computer Vision class. This project focuses on identify or count objects using Arduino Uno board and ESP32 camera module. It can used as a smart DIY home surveillance system

# Project Overview
The aim of this term project is to explore and apply computer vision concepts to real-world scenarios. It involves implementing and experimenting with different algorithms and techniques learned throughout the course. The project serves as an opportunity to showcase practical skills in computer vision. This project uses libraries such as openCV and mediapipe. 

# Getting Started
To get started with the project, follow the instructions below:
1. Install required libraries on your python IDE, as well as Arduino IDE
 - [OpenCV for python] (https://github.com/opencv/opencv-python)
 - [cvzone] (https://github.com/cvzone/cvzone)
 - [mediapipe] (https://github.com/google/mediapipe)
 - [pyserial] (https://github.com/pyserial/pyserial)
 - [serial] (A framework for serializing/deserializing JSON/YAML/XML into python class instances and vice versa)

2. Connect the hardwares following this scheme ![Screenshot 2023-05-27 at 21 56 46](https://github.com/modesthip/Computer_Vision_Term_Project/assets/49462641/6b8e471d-81b2-4cd4-bdd1-78cd380a158a)
3. Run the program and test it

Before uploading the code to ESP32-CAM module, please check the following setting:

Update the Preferences –> Aditional boards Manager URLs: https://dl.espressif.com/dl/package_esp32_index.json, http://arduino.esp8266.com/stable/package_esp8266com_index.json

Board Settings:
 - Board: “ESP32 Wrover Module”
 - Flash Mode: “QIO”
 - Partition Scheme: “Hue APP (3MB No OTA/1MB SPIFFS)”
 - Flash Frequency: “40MHz”
 - Upload Speed: “115200”
 - Core Debug Level: “None”
 - Programmer: “AVR ISP”
Port: Depends On Your System
GPIO 0 must be connected to GND pin while uploading the sketch
After connecting GPIO 0 to GND pin, press ESP32 CAM on-board RESET button to put the board in the flashing mode
After uploading the code disconnect the GPIO-0 pin from GND pin.


# Contribution

Contributions are welcome! If you would like to contribute to this project, please follow the guidelines below:

1. Fork the repository and clone it to your local machine.
2. Create a new branch for your contribution: `git checkout -b your-branch-name`.
3. Make your changes and additions to the project.
4. Test your changes to ensure they work as intended.
5. Commit your changes: `git commit -m "Your commit message"`.
6. Push your branch to your forked repository: `git push origin your-branch-name`.
7. Open a pull request in this repository, comparing your branch with the `main` branch.
8. Provide a clear and descriptive title for your pull request.
9. Include a detailed description of your changes, including any relevant information that may assist the maintainers in reviewing your contribution.
10. Wait for the project maintainers to review your pull request and provide any feedback or suggestions for improvement.
11. Make any necessary updates or modifications to your pull request based on the feedback received.
12. Once your pull request is approved and merged, your contribution will become part of the project.

Please ensure that your contribution adheres to the project's code of conduct and follows any guidelines or conventions specified by the project maintainers.

### Issue Tracking

If you would like to work on a specific issue, please check the issue tracker to see if it has been assigned or claimed by someone else. If not, feel free to leave a comment on the issue expressing your interest in working on it. This helps to avoid duplication of efforts and promotes efficient collaboration.

### Recognition

We value and appreciate all contributions to this project. As a token of our gratitude, we will acknowledge contributors in the project's `CONTRIBUTORS.md` file


# License


# Contact Information
For any inquiries or questions regarding the project, please contact:

dashnyam0105@gmail.com
