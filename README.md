# Tello Engineering Ecosystem   
![DEE_software_architecture](https://user-images.githubusercontent.com/100842082/210042172-30ad75ee-cb05-49e4-8ceb-e1b33bb1b6ea.png)

## 1. General description

The Tello Engineering Ecosystem is a software tool that allows controlling the operation of a Tello drone in different ways and using different types of devices and applications. Look at the figure to see the software modules included in the ecosystem and the technologies and tools involved.
The modules are front-end applications and servers that allow the user to control the drone. There are different frameworks and tools to implement these modules, including Python + tkinter (for desktop application) and Vue + Ionic (for Webb Apps). Some of these modules are able to control a swarm of drones.
Some of the modules communicate among them through MQTT brokers, using a publish/subscribe protocol.
The modules of the ecosystem are in development. Each of them has a repo in GitHub with the code and detailed information. This is a brief description of each module:

* *Tello Drone Circus*:
[![TelloEngineeringEcosystem Badge](https://img.shields.io/badge/TelloDroneCircus-blue.svg)](https://github.com/dronsEETAC/DashboardDEE) a desktop application (Python + tkinter) that allows the user to interact with the drone in a fun way (for instance, guide the drone with body poses or with the voice).

* *DashApp*:
[![DroneEngineeringEcosystem Badge](https://img.shields.io/badge/DEE-DashApp-brightgreen.svg)](https://github.com/dronsEETAC/DashboardVueDEE) a web app (Vue) with similar functionalities that the Dashboard, but that can be operated from a laptop connected to internet.