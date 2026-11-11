# Automatic Water Level Controller Using Arduino

## 1. Introduction

An Automatic Water Level Controller Using Arduino is an electronic system designed to automatically monitor and control the water level in a storage tank. The main purpose of this project is to prevent water overflow and reduce water wastage without requiring manual operation.

This system uses water level sensors to detect the water level in the tank and an Arduino microcontroller to control the water pump. When the water level drops below the minimum level, the Arduino automatically switches ON the motor. When the tank reaches its maximum water level, the Arduino switches OFF the motor.

The system provides an efficient, reliable, and cost-effective method of water management. It can be used in homes, apartments, industries, schools, and agricultural applications.

## 2. Objectives

- To design an automatic water level controlling system using Arduino.
- To monitor the water level in a tank automatically.
- To prevent water overflow and wastage.
- To control the water pump automatically based on the water level.
- To reduce human effort and manual monitoring.
- To save electricity by avoiding unnecessary pump operation.
- To develop a simple and low-cost water management system.

## 3. Components Required

1. Arduino Uno: Acts as the main controller and processes signals from the water level sensors.
2. Water Level Sensors: Detect the water level at different positions inside the tank.
3. Relay Module: Controls the switching of the water pump according to the Arduino output.
4. Water Pump (DC Motor): Pumps water into the storage tank.
5. Power Supply: Provides the required electrical power to the Arduino and other components.
6. Connecting Wires: Used to establish electrical connections between the components.
7. Water Storage Tank: Stores water and allows the sensors to monitor its level.

## 4. Working Theory

The Automatic Water Level Controller works on the principle of sensing the water level and controlling the water pump automatically with the help of an Arduino microcontroller.

In this system, water level sensors are placed at different heights inside the water tank to detect the minimum and maximum water levels. These sensors continuously monitor the presence of water and send signals to the Arduino Uno.

The Arduino receives the signals from the sensors and processes them according to the programmed instructions. When the water level falls below the minimum level, the Arduino activates the relay module, which switches ON the water pump. The pump starts supplying water to the tank.

As the water level gradually increases, the sensors continuously monitor the water level. When the water reaches the maximum level, the Arduino sends a signal to the relay module to switch OFF the water pump. This stops the water supply and prevents the tank from overflowing.

The same process repeats whenever the water level decreases. Thus, the system automatically maintains the required water level without human intervention.

The Arduino acts as the brain of the system, while the sensors detect the water level and the relay controls the pump operation. This makes the system simple, efficient, and reliable for automatic water management.
5. simulation link
https://wokwi.com/projects/480405437422417921
