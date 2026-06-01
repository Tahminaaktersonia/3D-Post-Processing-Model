# 3D Post-Processing Model

## Overview
This repository contains Simulink models and supporting files for a 3D post-processing manufacturing simulation project.

The project focuses on modeling and simulating the workflow of post-processing operations in additive manufacturing, including process routing, batching, resource utilization, and MQTT-based data communication.

## Implemented Processes

- Blasting
- Manual Cleaning
- Surfacing
- Coloring
- Vapor Smoothing
- Finish Processing

## Features

- Simulink-based discrete event simulation
- Process routing and rebatching logic
- Batch tracking through multiple processing stages
- MQTT communication for machine data publishing
- FIWARE integration experiments
- Automated and manual post-processing workflows

## Main Files

| File | Description |
|--------|-------------|
| Design_5new_4weeks.slx | Main simulation model |
| Design_5new_4weeks_Automated_Q2.slx | Automated workflow version |
| Design_5new_4weeks_Q3.slx | Alternative simulation scenario |
| Design_5new_300000.slx | Extended simulation model |
| RouteDePowderingDES.m | Routing logic |
| ExtractBlastingAttributes.m | Blasting attribute extraction |
| mqtt_vapor.m | MQTT communication script |

## Technologies

- MATLAB R2026a
- Simulink
- SimEvents
- MQTT
- FIWARE NGSI-LD

## Project Purpose

The objective of this project is to study and simulate post-processing operations in additive manufacturing environments and evaluate machine workflow, process timing, batching strategies, and data integration through industrial IoT technologies.

## Author

Tahmina Akter
Project Trainee
Tampere University of Applied Sciences (TAMK)

Project Trainee

Tampere University of Applied Sciences (TAMK)
