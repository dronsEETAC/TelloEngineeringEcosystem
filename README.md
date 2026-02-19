# Tello Engineering Ecosystem   
![Esquema_v2](https://github.com/dronsEETAC/TelloEngineeringEcosystem/assets/100842082/04e39eff-d09c-4242-8869-4448f4da43c2)



## 1. General description

The Tello Engineering Ecosystem is a software tool that allows controlling the operation of a Tello drone in different ways and using different types of devices and applications. Look at the figure to see the software modules included in the ecosystem and the technologies and tools involved.
The modules are front-end applications and servers that allow the user to control the drone. There are different frameworks and tools to implement these modules, including Python + tkinter (for desktop application) and Vue + Ionic (for Webb Apps). Some of these modules are able to control a swarm of drones.
Some of the modules communicate among them through MQTT brokers, using a publish/subscribe protocol.
The modules of the ecosystem are in development. Each of them has a repo in GitHub with the code and detailed information. This is a brief description of each module:

* *Tello Drone Circus*:
[![TelloEngineeringEcosystem Badge](https://img.shields.io/badge/TEE-TelloDroneCircus-blue.svg)](https://github.com/dronsEETAC/TelloDroneCircus) a desktop application (Python + tkinter) that allows the user to interact with the drone in a fun way (for instance, guide the drone with body poses or with the voice

* *Your Own Poses*:
[![TelloEngineeringEcosystem Badge](https://img.shields.io/badge/TEE-YourOwnPoses-blue.svg)](https://github.com/dronsEETAC/YourOwnPoses)   a desktop application (Python + tkinter) that allows the user to define his own poses (hand and body) and guide the dron with these poses.

    
* *Tello Web App*:
[![TelloEngineeringEcosystem Badge](https://img.shields.io/badge/TEE-TelloWebApp-blue.svg)](https://github.com/dronsEETAC/TelloWebApp)  a web app (Vue + Ionic) to guide the drone, take pictures, videos, etc. Sends commands through the broker to the Tello Drone Server.

    
* *Tello Drone Server*:
[![TelloEngineeringEcosystem Badge](https://img.shields.io/badge/TEE-TelloDroneServer-blue.svg)](https://github.com/dronsEETAC/TelloDroneServer)  a server in Python that receives commands from the Tello Web App and sends them to the drone.

* *Swarm Web App*:
[![TelloEngineeringEcosystem Badge](https://img.shields.io/badge/TEE-SwarmWebApp-blue.svg)](https://github.com/dronsEETAC//WebApp_Tello_Swarm)  a web app (Vue + Ionic) to guide a swarm of drones.

* *WebApp para swarm con efectos de magia*:
[![TelloEngineeringEcosystem Badge](https://img.shields.io/badge/TEE-Another_SwarmWebApp-blue.svg)](https://github.com/dronsEETAC//telloSwarmMagia)  another web app (Vue + Ionic) to guide a swarm of drones.

* *Tello Link*:
[![TelloEngineeringEcosystem Badge](https://img.shields.io/badge/TEE-Tello_Link-blue.svg)](https://github.com/dronsEETAC/telloLink_David)  a library for Tello, build upon djitellopy, with the same programming model than dronLink.

* *Demo Tello Link*:
[![TelloEngineeringEcosystem Badge](https://img.shields.io/badge/TEE-Tello_Link_Demo-blue.svg)](https://github.com/dronsEETAC/demo_telloLink_David)  an applications that demonstrates the use of telloLink for a variety of funtionalities for dron control. 

## 2.Compilation of TFG and TFM projects   


Title (and link)  | Author | Year 
--- | --- | --- 
[Prototipado de visión por computadora para la detección de objetos en drones autónomos](https://upcommons.upc.edu/handle/2117/411614)|  	PÉREZ CALDERÓN, ANTHONY DEMOSTENES | 2024
[Aportación al Tello Engineering Ecosystem: enjambre de drones y efectos de magia](https://upcommons.upc.edu/handle/2117/414820)| MARTÍNEZ JIMÉNEZ, JUAN | 2024
[Contribución al desarrollo del Drone Engineering Ecosystem (28)](https://upcommons.upc.edu/handle/2117/414358)| GALLARDO SERRA, ÀDAM | 2024
[Implementación del Circo de las Imágenes y otras Contribuciones al 'Tello Engineering Ecosystem'](https://upcommons.upc.edu/handle/2117/403394)|  	ITURRALDE AGUILÓ, ANNA | 2024
[Manejo de un dron mediante poses (1)](https://upcommons.upc.edu/handle/2117/395268)| SÁNCHEZ COZAR, DAVID | 2023
[Manejo de un dron mediante poses (2)](https://upcommons.upc.edu/handle/2117/395263)| GONZÁLEZ MIÑARRO, VÍCTOR | 2023
[Aplicació Web pel control dels drons Tello](https://upcommons.upc.edu/handle/2117/394930)| MAS MARTÍNEZ, JAN  | 2023
[Object Detection with Drone (Tello and TelloEDU)](https://upcommons.upc.edu/handle/2117/392046)| ABID, ABDUL WASIF | 2023
[Guía para programar un circo de drones](https://upcommons.upc.edu/handle/2117/383485)| PALACIOS ACEVEDO, JONATAN GABRIEL  | 2023
[Drone Colour object Tracking](https://upcommons.upc.edu/handle/2117/376279)| BOROUMAND, MILAD | 2022
[Programación de un drone Tello EDU](https://upcommons.upc.edu/handle/2117/362149)| JAUME BUSQUETS, JAIME | 2022

