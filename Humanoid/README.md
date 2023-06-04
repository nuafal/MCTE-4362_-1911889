# Humanoid Robots

[![Download as PDF](https://img.shields.io/badge/Download%20as%20PDF-EF3939?style=flat-square&logo=adobeacrobatreader&logoColor=white&color=black&labelColor=ec1c24)](https://mdtopdf.up.railway.app/convertPdf?url=https://github.com/iqfareez/MCTE-4362-Robotic-Hardware/blob/main/Week11/Humanoid.md)
![Assignment completion](https://img.shields.io/badge/Status-In%20progress-yellow?style=flat-square)

## Table of Contents

- [Introduction](#introduction)
- [History](#history)
- [Applications](#applications)
- [Main components of the robot](#main-components-of-the-robot)
  - [Body design](#body-design)
  - [Locomotion](#Locomotion)
  - [Navigation](#navigation)
  - [Data collection](#data-collection)
  - [Communication](#communication)
  - [Power management](#power-management)

## Introduction

Introduction to Humanoid Robots

Humanoid robots are robots that resemble the human body in shape and structure. They are designed to perform tasks that require human-like dexterity and mobility. Humanoid robots have been a subject of fascination for many years, and they have been featured in science fiction movies and books. However, in recent years, advances in robotics technology have made it possible to create humanoid robots that can perform a wide range of tasks in real-world settings.

Humanoid robots are used in a variety of applications, including manufacturing, healthcare, and entertainment. They are designed to work alongside humans, performing tasks that are too dangerous, difficult, or repetitive for humans to perform. Humanoid robots can also be used in research and development to study human behavior and cognition.

The design of humanoid robots presents many challenges, including the need for self-collision detection, path planning, and obstacle avoidance. Humanoid robots also require structures with variable flexibility to provide safety to the robot and people around it. Additionally, humanoid robots need redundancy of movements, i.e., more degrees of freedom, to perform a wide range of tasks.

In conclusion, humanoid robots are a fascinating and rapidly evolving field of robotics. They have the potential to revolutionize many industries and improve the quality of life for people around the world.


![humanoid robots](https://i.ytimg.com/vi/lqlyxg1-gE0/maxresdefault.jpg)

## History [^1]

**1495: Leonardo da Vinci** - designed a suit of armor that moved as if there was a real person inside. It was operated by a series of pulleys and cables and could stand, sit, move its arms, and even raise its visor to reveal nothing inside

**1774: The Jacquet-Droz Automata** - The Jaquet-Droz automata are three puppet automata created by Pierre Jaquet-Droz, his son Henri-Louis, and Jean-Frédéric Leschot between 1768 and 1774: the musician, the draughtsman, and the writer. In the 18th century, Pierre Jaquet-Droz, Henri-Louis Jaquet-Droz, and Jean-Frédéric Leschot designed and constructed automata as advertising and amusement toys to increase the sales of watches among the European nobility. 

**1970 - WABOT-1** - The WABOT-1 was the first fun-scale anthropomorphic robot developed in the world. It consisted of a limb-control system, a vision system and a conversation system. The WABOT-1 was able to communicate-with a person in Japanese and to measure distances and directions to the objects using external receptors, artificial ears and eyes, and an artificial mouth. The WABOT-1 walked with his lower limbs and was able to grip and transport objects with hands that used tactile-sensors. It was estimated that the WABOT-1 has the mental faculty of a one-and-half-year-old child. WABOT-1 consisted of the WAM-4 (as its artificial hands) and the WL-5 (Its artificial legs).

**2000 - Asimo** - ASIMO (Advanced Step in Innovative Mobility) is a humanoid robot created by Honda in 2000. It is displayed in the Miraikan museum in Tokyo, Japan. On 8 July 2018, Honda posted the last update of Asimo through their official page stating that it would be ceasing all development and production of Asimo robots in order to focus on more practical applications using the technology developed through Asimo's lifespan.

**2016 - Sophia** - Sophia is a social humanoid robot developed by the Hong Kong-based company Hanson Robotics.Sophia was activated on February 14, 2016, and made its first public appearance in mid-March 2016 at South by Southwest (SXSW) in Austin, Texas, United States.Sophia is marketed as a "social robot" that can mimic social behavior and induce feelings of love in humans. Sophia has been covered by media around the globe, and has participated in many high-profile interviews. In October 2017, Sophia was granted Saudi Arabian citizenship, becoming the first robot to receive legal personhood in any country. In November 2017, Sophia was named the United Nations Development Programme's first Innovation Champion, and is the first non-human to be given a United Nations title.

## Applications

Humanoid robots are becoming increasingly popular in various industries due to their ability to resemble and act like humans. Here is a more detailed elaboration on the applications of humanoid robots:


![Healthcare](https://live-production.wcms.abc-cdn.net.au/3a4c03ced49b8fe9ec6522c2043e1571?impolicy=wcms_crop_resize&cropH=1073&cropW=1615&xPos=0&yPos=0&width=862&height=575)

**Healthcare**: Humanoid robots are being used in healthcare to assist with tasks such as lifting and transferring patients, monitoring patient vitals, and providing emotional support to patients. They can also be used to provide companionship to older adults. For example, PARO is a robotic seal that has been found to be effective at providing emotional support to patients. Humanoid robots can also be used to provide more accurate diagnoses and help improve patient outcomes. They can analyze large amounts of data and provide insights that may not be immediately apparent to human healthcare professionals. Additionally, humanoid robots can be used to help train healthcare professionals and simulate medical procedures.

![Manufacturing](https://logisticstrendradar.metadeploy.com/images/subsection-images/robotics-and-automation-logistics/Stationary_Robotics_Automated_Shipment_Sorting.jpg)

**Manufacturing and Logistics**: Humanoid robots are being used in manufacturing and logistics to perform tasks such as assembly, packaging, and material handling. They can also be used in warehouses and distribution centers to move goods and perform inventory management tasks. For example, Amazon has been using Kiva robots to move products around their warehouses. Humanoid robots can help increase efficiency and productivity in these industries by performing repetitive tasks that would otherwise be done by humans.

![Hospitality](https://ars.els-cdn.com/content/image/1-s2.0-S0278431920303479-gr2.jpg)

**Hospitality**: Humanoid robots are being used in hospitality as bartenders, concierges, and receptionists. They can also be used as companions for older adults. For example, Pepper is a humanoid robot that has been used in hotels to provide information to guests. Humanoid robots can help improve customer service in the hospitality industry by providing quick and accurate responses to customer inquiries.

![R&D](https://www.frontiersin.org/files/MyHome%20Article%20Library/550644/550644_Thumb_400.jpg)

**Research and Development**: Humanoid robots are being used in research and development to demonstrate new technological advancements in motor skills, path planning, and obstacle avoidance. They are also being used for cognition research. For example, the iCub is a biped humanoid open source robot that has been used in cognition research. Humanoid robots can help researchers better understand human behavior and develop new technologies that can improve human lives.

![Education](https://research.qut.edu.au/stemerg/wp-content/uploads/sites/49/2017/03/humanoid-robots-513660331.jpg)

**Education**: Humanoid robots are being used in education to teach students about robotics and programming. They can also be used to assist teachers in the classroom. For example, NAO is a humanoid robot that has been used in schools to teach children about programming. Humanoid robots can help make learning more engaging and interactive for students, and can also help teachers better manage their classrooms.

![Entertainment](https://corporateentertainmentagency.com/wp-content/uploads/2015/07/NAODancing.jpg)

**Entertainment**: Humanoid robots are being used in entertainment as performers and attractions. They can also be used in theme parks and museums to provide interactive experiences for visitors. For example, Disney has been using animatronic humanoid robots in their theme parks for many years. Humanoid robots can help create immersive and engaging experiences for visitors, and can also help preserve cultural heritage by providing interactive exhibits in museums.

## Main Component of The Robots

### Body Design 

| Body Design     | Description                                   | Figures |
|-----------------|-----------------------------------------------| ------ |
| Bipedal         | A body design with two legs, resembling the human lower body. Bipedal robots are designed to walk and maintain balance on two legs, allowing them to navigate environments designed for humans. This design enables them to perform tasks such as walking, running, and climbing stairs, making them suitable for applications like personal assistance and humanoid research. Bipedal robots often incorporate dynamic stabilization mechanisms and advanced control algorithms to ensure stability and agility during locomotion. | ![Bipedal](https://blog.pal-robotics.com/wp-content/uploads/2022/06/biped-research-robot-TALOS-waving-hand.webp) *Talos*|
| Wheeled         | A body design with wheels as the primary mode of locomotion. Wheeled humanoid robots utilize one or more wheels for movement, providing stability and efficiency in navigation. This design is suitable for environments with smooth, flat surfaces and can be advantageous for tasks requiring fast and efficient transportation, such as logistics or warehouse operations. Wheeled robots may incorporate additional mechanisms for stabilization and obstacle avoidance, enabling them to navigate cluttered environments. | ![Wheeled](https://upload.wikimedia.org/wikipedia/commons/thumb/1/11/ReDSCF5983.JPG/1200px-ReDSCF5983.JPG) *Seropi* | 
| Quadruped       | A body design with four legs, resembling the lower body structure of animals like dogs or horses. Quadrupedal robots offer stability and maneuverability, making them suitable for rough terrains and outdoor environments. They can walk, trot, or crawl on all fours, enabling them to traverse challenging landscapes and perform tasks like search and rescue, exploration, and agricultural operations. Quadruped robots often employ sophisticated gait control algorithms and robust leg designs to maintain balance and adapt to varying terrains. | ![Swiss-Mile](https://assets.rbl.ms/28159639/origin.jpg) *Swiss-Mile*|
| Hexapod         | A body design with six legs, inspired by insects or spiders. Hexapod robots provide a higher degree of stability and flexibility in movement compared to bipedal or quadrupedal designs. They can traverse a wide range of terrains, including uneven surfaces and stairs. Hexapod robots use a variety of leg configurations and leg coordination techniques to achieve locomotion and perform tasks such as inspection, exploration, and disaster response in complex environments. | ![Hexapod](https://www.ez-robot.com/uploads/1/2/6/9/126941806/s237119158784252105_p9_i19_w1024.jpeg) *Spider Robot* | 
| Anthropomorphic | A body design that closely resembles the human body structure, including the torso, arms, and hands. Anthropomorphic humanoid robots aim to replicate human-like appearance and capabilities, allowing them to perform intricate tasks that require dexterity and manipulation. These robots often feature highly articulated joints and specialized grippers or hands to mimic human movements. Anthropomorphic humanoid robots are utilized in various applications such as research, human-robot interaction, entertainment, and healthcare. They enable studies on human-like behavior, natural language processing, and the development of assistive technologies. | ![Anthromorpic](https://d3i71xaburhd42.cloudfront.net/ac5ab6bbfb234c2f20d0af8a648d5c461b69c491/2-Figure1-1.png) *Anthromorphed robot*|


### Locomotion 

| Locomotion Type  | Description                                   | Figures | Electronics |
|------------------|-----------------------------------------------| ------- | ---- |
| Walking          | Walking is a common locomotion type for humanoid robots with bipedal or humanoid body designs. Walking involves coordinated movements of the legs to propel the robot forward, maintaining balance and stability. Walking gaits can vary, including normal walking, fast walking, and even dynamic running. Walking robots often employ sophisticated control algorithms and stabilization mechanisms to ensure smooth and stable locomotion on different surfaces. | ![Walking](https://i.pinimg.com/originals/00/5f/b1/005fb1bb914a7cd1d1e9cf3140e82a9b.gif) |  ![Actuator](https://d3i71xaburhd42.cloudfront.net/ca84148c8588083a79cbb8ffed4f8c5bf12e1669/2-Figure1-1.png) Actuators for controlling the movements of the legs, and control systems for coordinating the gait patterns and stability. |
| Running          | Running is a dynamic and high-speed locomotion type characterized by a periodic sequence of leaps or strides. Running requires more advanced control and stability compared to walking, as the robot must manage higher forces and maintain balance at greater speeds. Running robots often incorporate energy-efficient gait patterns, robust leg designs, and real-time control techniques to achieve efficient and stable running motions. Running capabilities are advantageous for tasks that require fast movement, such as search and rescue or sports activities. | ![Running](https://thumbs.gfycat.com/VainRichFireant-max-1mb.gif) *Boston Dynamics*| High-performance actuators capable of generating the required forces for rapid movement, precise sensor systems for feedback and control, and advanced control algorithms for gait optimization and stability. |
| Climbing         | Climbing locomotion involves the ability of humanoid robots to traverse vertical or inclined surfaces. Climbing robots employ specialized mechanisms, such as adhesive materials, gripping mechanisms, or climbing legs, to adhere to and move along the climbing surface. Climbing robots can be used in scenarios such as inspection and maintenance of structures, exploration of rough terrains, or disaster response in challenging environments. | ![Climbing](https://i.gifer.com/emy.gif) *Robot Tree Snake*| Actuators or mechanisms for gripping or climbing, and control systems for coordinating the climbing motions and maintaining stability. |
| Crawling         | Crawling locomotion refers to the movement of humanoid robots on all fours, similar to quadrupedal or animal-like crawling. Crawling can be useful for navigating through confined spaces, uneven terrains, or environments with low clearance. Crawling robots typically employ coordinated movements of their limbs to generate propulsion and maintain stability while moving in a crawling manner. These robots can be used in applications such as search and rescue, exploration of narrow spaces, or inspections in challenging environments. | ![crawling](https://www.gizmodo.com.au/wp-content/uploads/sites/2/2020/06/17/eqpspmnqs9hfm4na1pn1.gif) *Spot-Robot Dog Boston Dynamic*| ![Climb](https://ars.els-cdn.com/content/image/1-s2.0-S092188901100100X-gr1.jpg) Crawling locomotion include sensor systems for detecting limb position and movement, actuators for controlling the limb motions, and control systems for coordinating the crawling gait patterns. |
| Swimming         | Swimming locomotion refers to the ability of humanoid robots to move and propel themselves in water. Swimming robots employ various propulsion mechanisms, such as fin-like appendages, flippers, or propellers, to generate thrust and navigate through water. Swimming capabilities can be advantageous for tasks like underwater exploration, marine research, or underwater maintenance operations. | ![Swimming](https://www.ge.com/news/sites/default/files/Reports/2020-03/tumblr_inline_nsx7piHFlD1qzgziy_500.gif) *Stinger-The Swimming Robot* | ![swim](https://news.stanford.edu/wp-content/uploads/2022/07/20201204Ocean_One%5Ek_3D0A1936-e1658334147422.jpg) Motorized actuators or propellers for generating thrust, control systems for regulating the propulsion mechanisms, and sensor systems for monitoring water resistance, orientation, and navigation. |

### Navigation

Humanoid robot navigation focuses on enabling robots with human-like bodies to move and interact in their environment. It involves developing techniques for autonomous or remote control-based navigation, obstacle avoidance, and simultaneous mapping and localization. With advancements in perception, sensors, and algorithms, humanoid robots are becoming increasingly capable of autonomously navigating complex environments, contributing to various industries and applications.

![Teleoperation](https://ichef.bbci.co.uk/news/976/cpsprodpb/13416/production/_114507887_tele.man.robot.jpg.webp)
(*The T-Model*)

- Teleoperation:
  - Human operator controls the humanoid robot remotely.
  - Input devices such as joysticks or motion sensors are used.
  - Robot navigation is guided by operator inputs and sensory feedback.
  - Useful for hazardous environments or complex manipulation tasks.

![Spot](https://thumbs.gfycat.com/BronzeScaredHamster-size_restricted.gif)

*Spot Autonomous Navigation*
- Autonomous:
  - Humanoid robot navigates and makes decisions independently.
  - Utilizes sensors to perceive the environment.
  - Algorithms for mapping, localization, and path planning are employed.
  - Enables autonomous navigation and obstacle avoidance.

![SLAM](https://media.springernature.com/lw685/springer-static/image/chp%3A10.1007%2F978-94-007-6046-2_59/MediaObjects/307316_1_En_59_Fig3_HTML.png)
*Vision Based Humanoid and SLAM*
- SLAM (Simultaneous Localization and Mapping):
  - Combines mapping and localization for navigation in unknown environments.
  - Constructs a map of the surroundings while estimating the robot's position.
  - Enables autonomous exploration and mapping tasks.
  - Continuously updates the map and localization estimates.

![Hash](https://i.ytimg.com/vi/MIPN4V4Powk/maxresdefault.jpg)
*Obstacle Avoidance using Ultrasonic Sensor*
- Obstacle Avoidance:
  - Focuses on detecting and navigating around obstacles.
  - Sensors such as proximity sensors, vision systems, or depth sensors are used.
  - Control system calculates motions or path adjustments to avoid collisions.
  - Crucial for safe and efficient navigation in cluttered or dynamic environments.

### Data Collection

<table>
  <tr>
    <th>Data Collection Method</th>
    <th>Description</th>
    <th>Sensor Types and Versions</th>
  </tr>
  <tr>
    <td>Vision-based</td>
    <td>Vision-based data collection involves the use of cameras and visual sensors to capture images or video of the robot's surroundings. This method enables the robot to perceive and analyze visual information, including object recognition, scene understanding, and navigation. Vision-based data collection is essential for tasks such as object manipulation, environment mapping, and human-robot interaction.</td>
    <td>- RGB cameras (e.g., HD, 4K, or depth-sensing cameras)<br>
        - Time-of-Flight (ToF) cameras<br>
        - Stereo cameras<br>
        - LIDAR cameras</td>
  </tr>
  <tr>
    <td>LIDAR</td>
    <td>LIDAR (Light Detection and Ranging) utilizes laser beams to measure distances and create a detailed 3D map of the environment. LIDAR data collection enables the robot to perceive its surroundings in terms of depth and spatial structure. It is particularly useful for obstacle detection, mapping, and localization in both indoor and outdoor environments.</td>
    <td>- 2D LIDAR sensors<br>
        - 3D LIDAR sensors<br>
        - Solid-state LIDAR sensors</td>
  </tr>
  <tr>
    <td>Inertial Measurement</td>
    <td>Inertial measurement involves the use of sensors, such as accelerometers and gyroscopes, to measure the robot's linear and angular motion. This data collection method provides information about the robot's velocity, acceleration, and orientation. Inertial measurement is essential for tasks like balancing, gait control, and motion planning in humanoid robots.</td>
    <td>- Accelerometers<br>
        - Gyroscopes<br>
        - Inertial Measurement Units (IMUs)</td>
  </tr>
  <tr>
    <td>Force/Torque Sensing</td>
    <td>Force/torque sensing involves the use of sensors to measure the forces and torques applied to the robot's limbs or end-effectors. This method allows the robot to perceive and react to external forces during interactions with objects or humans. Force/torque sensing is crucial for tasks like manipulation, grasping, and collaborative tasks.</td>
    <td>- Force sensors<br>
        - Torque sensors<br>
        - Load cells</td>
  </tr>
  <tr>
    <td>Environmental Sensors</td>
    <td>Environmental sensors include various types of sensors, such as temperature sensors, humidity sensors, gas sensors, or pressure sensors. These sensors provide information about the physical properties of the environment, enabling the robot to monitor and adapt to changes in its surroundings. Environmental sensors are essential for tasks like environmental monitoring, safety assessment, and adaptive behavior in different contexts.</td>
    <td>- Temperature sensors<br>
        - Humidity sensors<br>
        - Gas sensors<br>
        - Pressure sensors</td>
  </tr>
  <tr>
    <td>Audio Sensors</td>
    <td>Audio sensors, such as microphones, enable the robot to capture and process sound signals from its environment. This data collection method allows the robot to perceive and analyze audio information, including speech recognition, sound localization, and acoustic scene understanding. Audio sensors are particularly useful for tasks involving human-robot interaction, voice commands, and auditory perception.</td>
    <td>- Microphones<br>
        - Array microphones<br>
        - Directional microphones</td>
  </tr>
</table>

### Data Transmission

<table>
  <tr>
    <th>Communication Method</th>
    <th>Description</th>
    <th>Applications</th>
  </tr>
  <tr>
    <td>Wi-Fi</td>
    <td>Wi-Fi communication allows humanoid robots to connect to wireless local area networks (WLANs) for data transfer and remote control. It provides high-speed and reliable communication, enabling robots to exchange information with other devices and access the internet.</td>
    <td>- Remote control and monitoring<br>
        - Cloud connectivity<br>
        - Data transfer and sharing</td>
  </tr>
  <tr>
    <td>Bluetooth</td>
    <td>Bluetooth communication is commonly used for short-range wireless data transmission between humanoid robots and other devices. It enables seamless connectivity and data exchange, making it suitable for applications requiring low-power consumption and secure connections.</td>
    <td>- Wireless sensor integration<br>
        - Human-robot interaction<br>
        - Mobile device synchronization</td>
  </tr>
  <tr>
    <td>Ethernet</td>
    <td>Ethernet communication involves using Ethernet cables or connections for high-speed wired data transfer. It provides a reliable and stable communication link, making it suitable for applications that require low latency and high bandwidth.</td>
    <td>- Real-time control and monitoring<br>
        - High-bandwidth data exchange<br>
        - Local network connectivity</td>
  </tr>
  <tr>
    <td>USB</td>
    <td>USB (Universal Serial Bus) communication allows humanoid robots to connect to other devices using USB cables. It provides a versatile and widely supported interface for data transfer, device control, and power supply.</td>
    <td>- Sensor integration<br>
        - Firmware updates<br>
        - Device configuration and control</td>
  </tr>
  <tr>
    <td>CAN (Controller Area Network)</td>
    <td>CAN communication is a robust and reliable protocol commonly used in industrial automation and robotics. It enables communication between different robot components and subsystems, facilitating coordinated control and data exchange.</td>
    <td>- Joint control and synchronization<br>
        - Sensor integration<br>
        - Inter-component communication</td>
  </tr>
  <tr>
    <td>Wireless LAN (Local Area Network)</td>
    <td>Wireless LAN communication allows humanoid robots to connect to local area networks wirelessly. It provides flexibility and mobility, enabling robots to access network resources, share data, and communicate with other devices within the same network.</td>
    <td>- Networked control and monitoring<br>
        - Data sharing and synchronization<br>
        - Collaborative robotics</td>
  </tr>
</table>
 

### Power Management

<table>
  <tr>
    <th>Power Management System</th>
    <th>Description</th>
    <th>Features</th>
  </tr>
  <tr>
    <td>Battery Pack</td>
    <td>A battery pack is a common power management system used in humanoid robots. It consists of rechargeable batteries that provide electrical energy to power the robot's components and systems.</td>
    <td>- High energy density<br>
        - Rechargeable<br>
        - Portable and compact<br>
        - Can be easily replaced or upgraded</td>
  </tr>
  <tr>
    <td>Power Distribution Board</td>
    <td>A power distribution board distributes power from the main power source, such as a battery, to various subsystems and components of the humanoid robot. It ensures proper power allocation and regulates voltage levels.</td>
    <td>- Efficient power distribution<br>
        - Overcurrent and overvoltage protection<br>
        - Regulated voltage output<br>
        - Connection points for different components</td>
  </tr>
  <tr>
    <td>Power Management IC</td>
    <td>A power management integrated circuit (IC) is responsible for managing and controlling the power supply within the humanoid robot. It regulates the voltage levels, manages power consumption, and protects the system from voltage spikes or irregularities.</td>
    <td>- Voltage regulation<br>
        - Power monitoring and control<br>
        - Battery charging and protection<br>
        - Thermal management</td>
  </tr>
  <tr>
    <td>Energy Harvesting</td>
    <td>Energy harvesting systems capture and convert ambient energy sources, such as solar power or kinetic energy, into electrical energy to power the humanoid robot. These systems aim to reduce reliance on external power sources and increase overall energy efficiency.</td>
    <td>- Solar panels for solar energy harvesting<br>
        - Piezoelectric or electromagnetic generators for kinetic energy harvesting<br>
        - Power conditioning and storage components</td>
  </tr>
  <tr>
    <td>Power Management Software</td>
    <td>Power management software controls and optimizes the power consumption of the humanoid robot's components and subsystems. It enables efficient power allocation, monitors energy usage, and implements power-saving strategies to extend the robot's operating time.</td>
    <td>- Power profiling and analysis<br>
        - Dynamic power allocation<br>
        - Sleep modes and power-saving algorithms<br>
        - User-configurable power settings</td>
  </tr>
</table>


[^1]: https://www.howwegettonext.com/a-history-of-humanoids
