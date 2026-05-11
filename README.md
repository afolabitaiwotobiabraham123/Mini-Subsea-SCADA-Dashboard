# Mini Subsea SCADA System (3 Wells + Manifold)

## Project Overview

This project is a Mini Subsea SCADA System simulation built using Node-RED and Dashboard 2.0.
The system simulates a simplified offshore subsea production environment where multiple wells send operational data into a shared manifold while operators monitor live conditions through a SCADA dashboard. The goal of this project is to understand how subsea monitoring, industrial automation, and SCADA logic work in real-world offshore operations.

## Features
### Subsea Well Simulation

The project simulates 3 subsea wells generating operational data such as:
* Pressure values
* Flow rate values
* Well production status
Each well continuously sends live data into the SCADA environment for monitoring and processing.

### Manifold Production Logic
A manifold logic function combines production data coming from the simulated wells into a shared production system.
This simulates how real offshore manifolds gather and route production flow from multiple subsea wells efficiently.

### Alarm Monitoring System
The project includes an alarm logic system that monitors pressure and flow conditions.
The alarm system triggers warnings whenever operational values exceed safe operating limits, helping simulate how industrial SCADA systems detect abnormal field conditions.

### Real-Time Dashboard Visualization
The system uses Node-RED Dashboard 2.0 to display:
* Live pressure gauges
* Flow rate indicators
* Dynamic production updates
* Alarm status monitoring
The dashboard updates in real-time to simulate a live SCADA monitoring environment.

## Technologies Used
* Node-RED
* Node-RED Dashboard 2.0
* JavaScript Function Nodes
* SCADA Simulation Logic
* Industrial Automation Concepts

## Project Objectives
This project was built to:
* Learn SCADA system fundamentals
* Understand subsea production monitoring
* Simulate industrial automation workflows
* Practice real-time dashboard visualization
* Explore digital twin concepts for offshore systems

## Future Improvements
Planned upgrades include:
* Advanced alarm trigger logic
* Production vs test header switching
* Well shutdown/isolation logic
* Realistic pressure trend simulation
* MQTT integration
* MySQL data logging
* Grafana visualization
* Full subsea digital twin architecture

## Live Simulation
A live dashboard demo was created to show:
* Real-time gauge updates
* Dynamic pressure/flow simulation
* Alarm response behavior
* Subsea production visualization

## Author
Afolabi Taiwo Abraham

Learning journey focused on:
* Subsea Control Systems
* SCADA Engineering
* Industrial Automation
* Digital Twins
* Offshore Production Monitoring
