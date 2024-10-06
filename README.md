# QR Guardian 
(Work in Progress)

## Overview

QR Guardian is designed to display the status of alarms on a live map hosted on a web page. The status of these alarms is updated by IoT devices located in remote locations. The system includes an IoT simulator for testing purposes and triggers workflows for certain events, such as red alarms that require different actions. The solution is built with a focus on resilience, scalability, agility, and cost-effectiveness, leveraging cloud economics.

## Features

- **Live Map Display**: Real-time visualization of alarm statuses on a web-based map.
- **IoT Device Integration**: Remote IoT devices update the alarm statuses.
- **Event-Driven Workflows**: Specific workflows are triggered for certain alarm events (e.g., red alarms).
- **IoT Simulator**: A simulator to test the system without needing physical IoT devices.
- **DevOps Strategy**: Continuous Integration (CI) and Continuous Deployment (CD) pipelines for seamless updates.
- **Scalability**: Designed to scale based on demand.
- **Resilience**: Built to handle failures gracefully.
- **Cost-Effective**: Utilizes cloud resources efficiently to minimize costs.

## Architecture

1. **IoT Devices**: Remote devices that send alarm status updates.
2. **IoT Simulator**: Simulates IoT devices for testing purposes.
3. **Backend Services**: Processes incoming data from IoT devices and updates the live map.
4. **Frontend**: Web application displaying the live map with alarm statuses.
5. **Event Processing**: Triggers workflows based on specific alarm events.
6. **CI/CD Pipeline**: Automates the build, test, and deployment processes.
7. **Cloud Infrastructure**: Hosts the application and scales resources as needed.
