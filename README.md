# Portable-Object-Detection
Object Detection Using ESP32 and YOLOv3

Introduction
This project implements object detection using YOLOv3 (You Only Look Once version 3) on an ESP32 microcontroller. The ESP32 captures images from a camera module and runs real-time object detection using YOLOv3, making it an embedded and portable solution for detecting objects in various environments.

Requirements
ESP32 microcontroller
Camera module compatible with ESP32
YOLOv3 model files
Arduino IDE
Setup
Hardware Setup:
I would advise to watch any youtube video or go to an online site for understanding wired connections of esp32 cam with your modules which you may use to connecty with your  device through which you will dump code. Here is a video reccomendation:https://www.youtube.com/watch?v=npJsmbFZiMg
Connect the camera module to the ESP32 microcontroller.
Install ESP32 Support in Arduino IDE:

Follow the instructions in the ESP32 Arduino Core GitHub to install ESP32 support in the Arduino IDE.
Download YOLOv3 Model:

Download the YOLOv3 model weights and configuration file from the official YOLO website.
Convert YOLOv3 Model for ESP32:

Open the Arduino IDE, load the esp32_webcamserver sketch and upload the file. After it check your serial monitor after pressing reset on your esp32 module cam and it will provide you with IP address through which you can wirelessly transmit video data between your esp module and system you are operating on.

Power on the ESP32 with the connected camera module.
Real-time Object Detection:

The ESP32 will capture images from the camera module and perform real-time object detection using YOLOv3.
View Results:
You caan view your result on screen at which esp32 cam is sending its transmisson with obj detection algorithm YOLO running in it.

