# ESP32 Predictive Maintenance System

## Introduction

A multi-sensor-based predictive maintenance system built using ESP32. This project monitors machine conditions such as temperature, vibration, load, and environmental conditions to identify potential failures before they become critical.

## Features

* Real-time sensor monitoring
* Multi-sensor data fusion
* Condition-based predictive logic
* Serial output with system health status
* Modular sensor integration

## Sensors Used

* DS18B20 (Temperature Sensor)
* MPU6050 (Vibration Sensor)
* Potentiometer (Load Simulation)
* LDR (Light/Environment Monitoring)

## Hardware

* ESP32 Development Board
* Breadboard
* Jumper Wires

## Working Logic

* High temperature + high load + high vibration → Critical Condition
* Moderate sensor values → Warning Condition
* Normal sensor values → Safe Condition

## Software

* Arduino IDE
* ESP32 Board Package
* Embedded C/C++

## Simulation

This project is simulated using Wokwi.

## Output

The system continuously monitors sensor data and displays:

* Temperature Status
* Vibration Status
* Load Status
* Environment Status
* Overall System Health

## Concepts Used

* Sensor Interfacing
* Data Acquisition
* Condition Monitoring
* Embedded Decision Making
* Predictive Maintenance Fundamentals
* Multi-Sensor Systems

## Future Improvements

* IoT Dashboard Integration
* MQTT Communication
* Cloud Data Logging
* Real-Time Data Visualization
* TinyML-Based Anomaly Detection
* Predictive Analytics

## Learning Objectives

* Working with multiple sensors on ESP32
* Embedded condition monitoring
* Decision-based fault detection
* Predictive maintenance concepts
* Industrial IoT fundamentals

## Target Platform

ESP32

## Author

Virbhushan

