# ESP32 FreeRTOS DHT22 OLED Monitor

## Introduction

This project demonstrates multitasking on the ESP32 using FreeRTOS. It reads environmental data from a DHT22 sensor and updates an SSD1306 OLED display in real-time using queues for safe inter-task communication.

## Features

* FreeRTOS-based multitasking
* Inter-task communication using queues
* DHT22 temperature and humidity sensing
* Button press detection with software debouncing
* Real-time OLED display updates using SSD1306
* Modular task-based architecture

## Hardware Used

* ESP32 Development Board
* DHT22 Temperature and Humidity Sensor
* SSD1306 OLED Display (I2C)
* Push Button

## Task Breakdown

| Task         | Function                                        |
| ------------ | ----------------------------------------------- |
| Sensor Task  | Reads temperature and humidity every 2 seconds  |
| Button Task  | Detects button presses with debounce handling   |
| Display Task | Updates OLED with latest sensor and button data |

## Concepts Used

* FreeRTOS Tasks
* FreeRTOS Queues
* Multitasking
* Inter-Task Communication
* Embedded User Interface Design
* Sensor Data Acquisition

## Output

The OLED display shows:

* Temperature
* Humidity
* Button Press Count

## Future Improvements

* Wi-Fi Connectivity
* Cloud Data Upload
* Data Logging to SD Card
* Mobile Dashboard Integration
* MQTT Support

## Learning Objectives

* Understanding FreeRTOS task scheduling
* Queue-based communication between tasks
* Sensor integration on ESP32
* OLED display interfacing
* Real-time embedded systems development

## Target Platform

ESP32

## Author

Virbhushan
