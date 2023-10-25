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
[![TelloEngineeringEcosystem Badge](https://img.shields.io/badge/TEE-SwarmWebApp-blue.svg)]  a web app (Vue + Ionic) to guide a swarm of drones. Sends commands through the broker to the Tello Swarm Server.

* *Tello Swarm Server*:
[![TelloEngineeringEcosystem Badge](https://img.shields.io/badge/TEE-TelloSwarmServer-blue.svg)]  a server in Python that receives commands from the Swarm Web App and sends them to the swarm of drones. 

## 2.Compilation of TFG and TFM projects   


Title (and link)  | Author | Year 
--- | --- | --- 
[Manejo de un dron mediante poses (1)](https://upcommons.upc.edu/handle/2117/395268)| SÁNCHEZ COZAR, DAVID | 2023| 
Operaciones de enjambre en DEE | SÁNCHEZ ERASO, SERGIO | 2023| https://upcommons.upc.edu/handle/2117/395270
[Example](https://www.youtube.com/watch?v=kuyCd53AOtg)    | SINGH ATWAL, JASKIRAT |  2023| https://upcommons.upc.edu/handle/2117/395271
From Backend to DashMobile: Expanding the Horizons of the Drone Engineering Ecosystem | PINTO MORENO, ALEJANDRO SAMUEL |  2023| https://upcommons.upc.edu/handle/2117/394931  
Contribución al Drone Engineering Ecosystem con Android Nativo | NUEZ ZARAGOZA, LAURA |  2023| https://upcommons.upc.edu/handle/2117/393653  
Desenvolupament i integració de jocs i aplicacions web al Drone Engineering Ecosystem |  ORPELLA PALOMAR, JOANA |  2023| https://upcommons.upc.edu/handle/2117/393331 
