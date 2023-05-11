# Swarming Robots

## Table of Contents

- [Introduction](#introduction)
- [History](#history)
- [Applications](#applications)
- [Main components of the robot](#main-components-of-the-vehicle)
  - [Body design](#body-design)
  - [Locomotion](#Locomotion)
  - [Navigation](#navigation)
  - [Data collection](#data-collection)
  - [Communication](#communication)
  - [Power management](#power-management)

## Introduction

- The subfield of robotics known as **swarm robotics** examines the collective behaviour of large groups of relatively basic robots.

- Inspired by social organisms like ants, bees, and termites, swarm robotics seeks to develop robotic systems that can collaborate to complete tasks more efficiently and effectively.

- **Swarm robotics** is characterised by a decentralised approach in which individual robots interact with their neighbours to accomplish collective behaviour by adhering to simple rules.

- In robotic systems, swarm robotics aims to attain a high level of fault tolerance, scalability, flexibility, and adaptability.

- There are numerous applications for **swarm robotics**, such as environmental monitoring, search and rescue operations, manufacturing, and agriculture.

- Despite being in its infancy, swarm robotics has shown promising results and has the potential to revolutionise the field of robotics.


![Swarm robotics domain](https://www.frontiersin.org/files/Articles/512421/frobt-07-00036-HTML-r1/image_m/frobt-07-00036-g001.jpg)

## History[^1]

- G. Beni and Fukuda first used the term "swarm" in robotics in **1988**.
- In **1989**, the concept of "swarm intelligence" was first introduced.
- In **1993**, C. Ronald Kube and Hong Zohng created a system of multiple robots inspired by natural swarming.
- Earlier **swarm robotic** systems investigated the swarming behaviours of insects, animals, and fish.
- Different inspirations, such as the migration of birds or ant colonies, drove research.
- Emulation of swarming behaviours such as foraging, aggregating, sorting, stigmergy, and cooperation
- In **2004**, G. Beni made a new endeavour to provide a more precise description of a swarm.
- Swarm autonomous systems are characterised by their simplicity, self-organisation, scalability, and local communication.
- Numerous additional definitions of swarms have been proposed, all of which concur on the central concept of natural swarming and simple rules for coordination and cooperation.

## Main components of the robot

### Body design

Usually small in size and simple in design, and low in cost. The body design is inspired by insects. Take a look at some examples below:

![swarm robotics insects example](https://imgur.com/a/tHUvUU8)

In swarm robotics, quantity is more important than quality. The more robots you have, the more tasks you can perform. The optimal size de  pends on the task/mission.

| Body Type | Description      |
| ------------------- | ---------------------- |
| Wheeled robots        | These robots move using wheels and are useful for flat surfaces. They can be simple or sophisticated, depending on the required task.              |
| Legged robots         |	These robots have legs and can walk or crawl over rough terrain. They can have a higher degree of mobility than wheeled robots but are often more complex. |
| Flying robots         | These robots can fly and can be useful for surveying large areas or hard-to-reach locations. They can vary in size and complexity, from small quadcopters to larger drones.             |
| Aquatic robots        | These robots can swim or move through water and can be useful for tasks such as ocean exploration or monitoring water quality. They can be shaped like fish or have propellers for movement.              |
| Hybrid robots         | These robots combine multiple body types to increase their versatility. For example, a wheeled robot may have legs to traverse rough terrain, or a flying robot may have wheels for landing and takeoff. |


### Locomotion

Several locomotion systems are being used. Some examples:

| Locomotion System  | Description | Examples |
| ------------------- | ----------- | ---------------------- |
| Wheeled        | Wheeled          | e-puck, Khepera         |
| Legged         | Quadrupel, Bipedal, single pedal  | RHex   |
| Flying         | Rotors or Wings                   | Parrot AR.Drone, Aeroquad         |
| Swimming        |  Fins or Propellers             | AquaJelly, RoboTuna         |
| Crawling        | crawling and climbing            | RiSE           |
| Rolling         |  Move by rolling, which can improve stability on uneven terrain           | MorpHex              |

So, extracting from the table above, there are six (6) locomotion strategies that are used in swarm robotics which are **Wheeled**, **Legged**, **Flying**, **Swimming**, **Crawling** and **Rolling**.

<table>
  <tr>
    <th>Locomotion</th>
    <th>Description</th>
    <th>Example</th>
  </tr>
    <td>Wheeled</td>
    <td>Moves using wheels and operates as part of a group, or swarm, to accomplish tasks.</td>
    <td><img src="https://wevolver-project-images.s3.amazonaws.com/0.artepjrrns20190218_090238%20-%20Matt%20N.jpg"/></td>
  <tr>
    <td>Legged</td>
    <td>Robot that uses multiple legs to move and coordinate with other robots to achieve a common goal</td>
    <td><img src="https://i.ytimg.com/vi/ISznqY3kESI/maxresdefault.jpg"/></td>
  </tr>
  <tr>
    <td>Flying</td>
    <td>Swarming robot that uses flight motion and communicate with other robots for coordination</td>
    <td><img src="https://www.science.org/cms/10.1126/scirobotics.abm5954/asset/a7054ab7-7464-4ae9-9b5f-1ee92e4de798/assets/images/large/scirobotics.abm5954-f1.jpg"/></td>
  </tr>
  <tr>
    <td>Swimming</td>
    <td>Autonomous underwater vehicles designed to work collectively, resembling schools of fish or other aquatic organisms</td>
    <td><img src="https://www.designworldonline.com/uploads/ImageGallery/FESTO_AquaJelly_2.gif"/></td>
  </tr>
  <tr>
    <td>Crawling</td>
    <td>Mimics the behavior of insects or animals that move on the ground.</td>
    <td><img src="https://i.guim.co.uk/img/static/sys-images/Guardian/Pix/pictures/2014/2/6/1391710094405/A-swarm-of-Kilobots-009.jpg?width=465&quality=85&dpr=1&s=none"/></td>
  </tr>
  <tr>
    <td>Rolling</td>
    <td>Robot that move using wheels or tracks and work together in groups.</td>
    <td><img src="https://i.ytimg.com/vi/OI4OiKNEixc/maxresdefault.jpg"/></td>

   </tr>
</table>

Depending on their design and intended application, swarming robots may employ a variety of **propulsion systems**. Bidirectional motors, piezoelectric polymers, stepper motors, and planar coils may also be included in these propulsion systems. Each form of **propulsion system** has its own benefits and drawbacks, and the choice of propulsion system depends on the robot's design requirements and constraints.

Sure, here are some additional examples of propulsion systems used in swarming robots, along with reliable sources:

| Propulsion System  | Description                                                                                                                        | Example                                                                                                                                                  | Reference                                                                                                            |
|-------------------|------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|
| Differential Drive | Consists of two independently driven wheels or tracks, allowing the robot to move forward, backward, turn, and pivot in place.    | Kilobot                                                                                                                                                  | [Science Robotics](https://robotics.sciencemag.org/content/2/9/eaan6426)                                           |
| Magnetic Wheels    | Use magnetic attraction and repulsion to move the robot. This system can provide high accuracy and low noise levels.               | AMBER                                                                                                                                                   | [IEEE Xplore](https://ieeexplore.ieee.org/document/9053978)                                                         |
| Shape Memory Alloy | A material that can change shape when heated. This can be used to create actuator wires that can move the robot's legs or wings.     | RoboBees                                                                                                                                               | [Harvard University](https://www.seas.harvard.edu/news/2016/11/robo-bees-now-fly-under-their-own-power)                 |
| Ionic Polymer      | A material that can contract and expand in response to a small electrical current. This can be used to create soft robotic actuators. | Octobot                                                                                                                                                 | [Nature](https://www.nature.com/articles/nature19100)                                                               |
| Pneumatic Actuator | An actuator that uses compressed air to create movement. This can be used to create soft robotic grippers or legs.                  | Soft Robotics Gripper                                                                                                                                   | [Soft Robotics](https://softroboticsinc.com/solutions/grasping-and-manipulation/grasping/soft-robotics-gripper/)     |

Note: The examples provided are just a small sample of the different propulsion systems used in swarming robots, and there are many other types of propulsion systems that can be used.

## Navigation

### Sensors

- **Accelerometer**: to determine the angle of inclination, detect collisions, measure free-fall, and track changes in acceleration, among other things.
- **Magnetometer**: Measures the Earth's magnetic field for positioning.
- **IR Sensors**: Uses infrared light to measure distance to objects.
- **Ultrasonic Sensor**: Uses sound waves to measure distance to objects.
- **Radio Transceiver**: Communicates with other robots or base stations for localization and navigation.
- **Wheel encoder**: Measures the rotation of wheels or joints for position estimation.
- **Torque sensor**: For controlling the robot's movement and ensuring that it is operating within safe limits.
- **Gyroscope**: 	Measures angular velocity and orientation.
- **Inclinometer**: To measure the angles of slope, elevation, or depression of an object with respect to gravity's direction.
- etc.

#### Behaviors

| Behavior          | Description                                                                                                                          | Example                                                |
|-------------------|--------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------|
| Aggregation       | Move towards a central point, gathering in a cluster.  |  Robots collecting at the source of a signal, forming a swarm of robots around the charging station or a group of robots congregating around an object of interest.                |
| Dispersion        | Disperse away from each other, spreading out over an area.       | Drones covering a large search area to find a missing person or robots spreading out to cover a crop field.  |
| Coordination      | Move in a coordinated manner to accomplish a task             | Robots cooperating to assemble a structure, multiple drones working together to survey an area, or robots forming a circle to surround and contain a threat.  |
| Pattern formation | Robots form specific patterns or shapes, | Robots moving in a line formation to explore a narrow space, robots in a square pattern to search an area, or robots arranging themselves in a V-shape to fly more efficiently.             |
| Object transport  | The robots work together to transport objects from one location to another.          | Drones delivering medical supplies or packages, or robots carrying a heavy object together to a specific location.            |
| Exploration       | Explore an environment, gathering information and sharing it with each other.                                         | A swarm of robots used for disaster area mapping.       |
| Communication     | Robots communicate with each other to share information and coordinate their actions                        | Rrones sharing information about their position and status to fly in formation, or robots using a common language to coordinate their actions.|
| Swarm defense     | Robots work together to defend against threats, such as predators or other robots.                           | Drones using swarm tactics to defend against other drones or robots working together to protect a specific area from a threat.|  
                               
### Data Collection

Examples of data collected by swarm robots[^3]:

> Khepera and Khepera IV robots use optical sensors to collect data about the environment around them. They are able to detect and process light to identify objects and obstacles.

> Khepera, Khepera IV, E-puck, E-puck 2, and Pheeno robots use microphones to collect sound data and identify sources of sound.

> S-bot and Colias robots use a camera to capture images and videos of the environment around them.

> Alice, Kobot, Jasmine, and Kilobot robots use infrared sensors to detect the presence and distance of objects around them.

### Communication

The most common technologies for sending messages from robot to robot in swarms are Bluetooth, wireless LAN or infrared.

#### Control Architectures

Decentralized control architecture, where each robot operates independently and communicates with its neighbors to coordinate their actions. [^4]
| Control Architecture  | Description | Picture |
| ------------- | ------------- | --------- |
| Leader-Follower  | A small number of robots are designated as leaders and the rest of the robots follow their movement. The leaders can be pre-programmed or chosen based on their sensing or communication capabilities. | ![swarm robotics insects example](https://imgur.com/QLH9JlW) |
| Stigmergy  | This architecture relies on indirect communication among robots through the environment. Each robot modifies the environment in some way (e.g., leaving a trail of pheromones) and other robots can detect and respond to these modifications. | ![swarm robotics insects example](https://ars.els-cdn.com/content/image/1-s2.0-S0921889019301538-gr11.jpg)| 
| Distributed Consensus  | Robots communicate with their neighbors to reach a consensus on a particular behavior or decision. This can be done through direct communication or by observing the behavior of neighboring robots. | ![swarm robotics insects example](https://imgur.com/ia2FkEf)|
| Self-Organization  | This architecture involves the emergence of a collective behavior from the interactions among individual robots without any centralized control. This can be achieved through simple rules or algorithms that govern the behavior of each robot, such as the famous "Boids" algorithm for simulating flocking behavior. | ![swarm robotics insects example](https://imgur.com/RAA1bvR)|


## Swarming Robot Power Management

Swarming robots require a robust and automated method of charging and reprogramming. There are different ways to charge a large swarm of robots, including:

### Charging Station

- Simple, low-cost charging station for recharging functionality.
- Allows robot to autodock and recharge.
- Provides a regulated voltage source.
- Has two contacts to bot for power and ground.
- Interconnects with other charging and maintenance stations.

### Maintenance Station

- Provides recharging, reprogramming, and communication functions.
- Allows the robot to autodock, recharge, reprogram, and communicate with a host.
- Provides a simple regulated voltage source for recharging and powering the bot.
- Has four contacts to bot for power, ground, clock, and data.
- Uses I2C communication with the bot.
- Features a microcontroller to handle I2C communications.
- Uses USB or RS-232 communication with the host computer.

### Charging Robot

- Portable charging station with docking stations for a large swarm of robots.
- Uses metal contacts for connecting to the charging robot's metal strip.
- Uses comparable data packets as the swarm robots, but incessantly transmits a message.
- Mobile robots send request messages to the charging robot when their battery level falls below a specific threshold and they cannot relocate themselves.

![Docking Station](https://thumbs.dreamstime.com/z/autonomous-mobile-robots-charging-modern-warehouse-autonomous-mobile-robots-charging-modern-warehouse-warehouse-automation-161315328.jpg)

### Charging via Automatic Docking

- Lithium Polymer (LiPoly) battery chemistry is ideal for small robots because of its high energy density and output current capabilities.
- A smart power module should be designed to enable easy contact engagement with the mating contacts for the charging station.
- The power module should also have another set of contacts for bi-directional high-speed communication with the charger host computer for proper and safe charging.

![swarm robotics insects example](https://d3i71xaburhd42.cloudfront.net/b6afc53242432ff2e5589ce01f37d31881126134/2-Figure3-1.png)

[^1]: https://roboticsbiz.com/advantages-and-history-of-swarm-robotics-sr-explained/
[^2]: https://www.frontiersin.org/articles/10.3389/frobt.2017.00055/full
[^3]: https://www.mdpi.com/1424-8220/21/6/2062
[^4]: https://www.tandfonline.com/doi/abs/10.1080/01969722.2018.1552843?journalCode=ucbs20
[^5]: http://www.swarmrobot.org/Communication.html
[^6]: http://www.swarmrobot.org/PowerDockingStation.html
[^7]: https://ieeexplore.ieee.org/document/5189756
