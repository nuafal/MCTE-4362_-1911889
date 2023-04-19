# AGV ( Automated Guided Vehicle ) vs AMR ( Autonomous Mobile Robot )

## Contents

- [Introduction to AGV vs AMR](#introduction---agv-vs-amr)
- [History of AGV and AMR](#history-of-agvamr)
- [Applications of AGV/AMR](#applications-of-agvamr)
- [Main components of the AGV/AMR](#main-components-of-the-vehicle)
  - [Body design](#body-design)
  - [Locomotion](#Locomotion)
  - [Navigation](#navigation)
  - [Data collection](#data-collection)
  - [Data transmission](#data-transmission)
  - [Power management](#power-management)

## Introduction to AGV vs AMR

**Automated Guided Vehicle (AGV)**, is a robotic system that is designed to operate autonomously and is used for material handling and transportation in various industries such as manufacturing, logistics, and healthcare. designed for simple tasks in controlled environments, AMRs are capable of operating in more complex and dynamic environments.

**Autonomous Mobile Robots (AMR)**, is a robotic system that is designed to operate autonomously and is similar to AGV but is capable of operating in more complex environments. They are capable of performing complex tasks such as transporting goods in warehouses, delivering packages in urban areas, and assisting with medical procedures in hospitals. AMRs are also used in research and development to test new technologies and applications


![amr vs agv image](https://v8d2f4g2.rocketcdn.me/wp-content/uploads/2022/10/AMR-vs-AGV-Routes.jpg)

**[⬆ Back to top](#automated-guided-vehicle-agv--autonomous-mobile-robot-amr)**

### History of AGV:

- The first AGVs were developed in the 1950s and were used in the automotive industry to transport materials and parts.
- In the 1960s, AGVs were introduced to other industries such as food and beverage, pharmaceuticals, and electronics.
- In the 1970s, AGVs became more advanced with the introduction of computer control systems and laser guidance technology.
- In the 1980s and 1990s, AGVs continued to evolve with the introduction of more advanced sensors and navigation systems.
- The first AGV (Automated Guided Vehicle) was developed in the 1950s by Barrett Electronics Corporation, a company that was later acquired by FMC Corporation. 

  ![first agv](https://media.springernature.com/lw685/springer-static/image/chp%3A10.1007%2F978-3-662-44814-4_1/MediaObjects/290934_1_En_1_Fig4_HTML.jpg)

### History of AMR:

 - The first *AMRs* were developed in the 1990s and were used in the military for reconnaissance and surveillance.
- In the early 2000s, AMRs were introduced to other industries such as manufacturing, warehousing, and healthcare.
- In the mid-2000s, AMRs became more advanced with the introduction of more advanced sensors and navigation systems, such as lidar and simultaneous localization and mapping (SLAM) technology.
- William Grey Walter developed the first AMR in the late 1940s and early 1950s. 
- He developed Elmer and Elsie, ELectro MEchanical Robots, Light Sensitive, with Internal and External stability.

![Elmer and Elsie](https://www.theoldrobots.com/images48/Elmer_Elsie3.JPG)

**[⬆ Back to top](#automated-guided-vehicle-agv--autonomous-mobile-robot-amr)**

Some key differences of AGV & AMR:
| Features | AGV | AMR |
| --- | --- | --- |
| **Environment** | Designed to operate in controlled environments | Capable of operating in more complex and dynamic environments |
| **Navigation** | Typically follow pre-determined paths or routes | Use advanced sensors and cameras to navigate through dynamic environments and avoid obstacles |
| **Flexibility** | Less flexible than AMRs and may require reprogramming for new tasks | More flexible than AGVs and can adapt to changing environments and tasks more easily |
| **Complexity** | Capable of performing simple tasks such as transporting materials and supplies | Capable of performing more complex tasks such as interacting with humans and other machines, and performing tasks that require more advanced decision-making capabilities |
| **Cost** | Generally less expensive than AMRs due to their simpler design and capabilities | Generally more expensive than AGVs due to their advanced sensors and capabilities |

## Applications of AGV and AMR 

<table>
  <thead>
    <tr>
      <th>Applications</th>
      <th>Description</th>
      <th>Examples</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Manufacturing</td>
      <td>Automated vehicles can transport raw materials and finished products throughout the manufacturing process. They can be used to move materials between workstations, assembly lines, or conveyors.
      </td>
      <td>
      <p>Kiva System's robotic system is used by Amazon to transport shelves of products to workers for order fulfillment.</p>
      <a href="https://spectrum.ieee.org/three-engineers-hundreds-of-robots-one-warehouse">
      <img src="https://assets.rbl.ms/25561265/origin.jpg"
      alt = "Kiva Systems: Next generation robot" width = 300 height = 175>
      </td>
    </tr>
    <tr>
      <td>Warehousing and distribution</td>
      <td>Autonomous robots can be used to move goods around a warehouse or distribution center, such as carrying pallets or boxes from one location to another.</td>
      <td>
      <p>Fetch Robotics provides autonomous mobile robots to help DHL supply chain with picking and packing processes, material movement, and sortitions.</p>
      <a href="https://www.freightwaves.com/news/fetch-robotics-grabs-46m-in-series-c">
      <img src="https://www.dcvelocity.com/ext/resources/images/articles/2017/201712/20171206news_fetch.jpg?t=1576511406&width=600">
      </a>
      </td>
    </tr>
    <tr>
      <td>Healthcare</td>
      <td>Mobile robots can be used to transport medical supplies, meals, and waste throughout a hospital, reducing the need for manual transportation and minimizing the risk of infection.</td>
      <td>
      <p>
      <li>
      A group of Malaysian scientists have developed a <strong>Medibot
      </strong> robot that is barrel-shaped and equipped with wheels. The scientists aim for this robot to move around hospital wards and check on patients with coronavirus. The purpose of this invention is to minimize the risk of infection for healthcare workers.</li>
      </p>
      <a href="https://www.iium.edu.my/news/medibot-to-do-rounds-on-malaysian-virus-wards">
      <img src="https://cute.iium.edu.my/images/2020/09/10/WhatsApp%20Image%202020-09-10%20at%2012.14.03%20PM.jpeg" height = 200>
      </td>
    </tr>
    <tr>
      <td>Agriculture</td>
      <td>Robotics can assist in harvesting, planting, and transporting crops in a farm or greenhouse environment. They can be used to perform tasks like seeding, spraying, and harvesting crops.</td>
      <td>
      <p><li>Iron Ox designs and operates autonomous greenhouses that use robots for plant transportation, transplanting, and harvesting</li></p>
      <img src="https://image.cnbcfm.com/api/v1/image/107047765-1650292653535-still-for-iron-ox.jpg?v=1650294317" width = 200><br/>
      <a href="https://www.malaysiakini.com/announcement/631279">Iron OX</a>
      </td>
    </tr>
  </tbody>
<table>

**[⬆ Back to top](#automated-guided-vehicle-agv--autonomous-mobile-robot-amr)**

## Main components of the robot

### Body design

**AGVs** have several usages depending on what type of action that needs to used:

| Main types | Description | Examples |
| ---------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| Forklift     | AGVs with a forklift attachment are used to transport pallets and other materials to and from high shelves. They may be designed to operate in narrow aisles or other confined spaces.       | ![Forklift AGV](https://media-live2.prod.scw.jungheinrichcloud.com/resource/image/904076/landscape_ratio19x9/2400/1137/20b9895f0ec2142298db21aac86500db/2B6DF1A716C0579F859B69E8054341D8/agv.png)                            |
| Tugger     | Tugger AGVs are designed to tow a train of carts or pallets behind them. They are often used for in-plant transportation of goods or parts.                                                                                                      | ![Tugger AGV](https://www.dematic.com/content/dam/dematic/images/products/agv/1-Compact_Tugger_AER_5-1.jpg) |
| Flatbed   | These AGVs have a platform that is flat and can transport large items like pallets, boxes, and other bulky goods. They may have side walls or other attachments to secure the load during transport.         | ![Flatbed AGV](https://img.directindustry.com/images_di/photo-g/63866-15648146.jpg)                                                                  |
| Unit-load  | AGVs with a unit load configuration are designed to transport individual units like cartons or totes from one location to another. They may have side conveyors or lift tables to transfer the load onto the vehicle.                                                                                                 | ![Unit-load AGV](https://www.mhi.org/images/learning/fundamentals/agvs1.jpg)                           |
| Assembly Line | 	These AGVs are designed to move materials between different stations on a production line. They may have customized attachments or fixtures to hold the parts or products during transport. | ![Assembly Line AGV](https://www.indevagroup.com/wp-content/uploads/2020/09/Aetna-Robopac-stabilimento-Smart-Factory-02-800x450.jpg)                         |

**AMRs** have lots of similarities with AGVs but there are some variations depending on the usage:
These robots are smaller and more versatile than AGVs and can be used in a wide variety of applications. They often have a compact body and a flat surface for transporting items.


| Main types | Description | Examples |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Swarm         | Swarm robots, a type of AMR, are designed to work together as a team to perform tasks such as material handling, inspection, or maintenance. They typically have a small, simple body and are controlled by a central system. | ![Swarm amr](https://static.wixstatic.com/media/13a3cb_5a699944a0e7420ca9ec28af84c94d82~mv2.jpg/v1/crop/x_0,y_0,w_1654,h_1139/fill/w_554,h_340,al_c,q_80,usm_0.66_1.00_0.01,enc_auto/0420_Datasheet_SMR_v0_1_250Lines_JW-RGB-1.jpg)                                                                               |
|Crawler | These robots, also known as mobile robots, are designed to move on tracks or wheels and can be used in rugged or uneven environments. They often have a simple, sturdy body with a low center of gravity. | ![Crawler amr](https://assets.rbl.ms/26144902/origin.jpg) |

**[⬆ Back to top](#automated-guided-vehicle-agv--autonomous-mobile-robot-amr)**

### Locomotion

~ refers to their ability to move from one location to another. Below are the types of locomotion used in AGVs/AMRs. All of the robots moves using electrical motors.

<table>
  <tr>
    <th>Motion type</th>
    <th>Description</th>
    <th>Usage</th>
    <th>Example</th>
  </tr>
  <tr>
    <td>Tracks</td>
    <td>	AGVs and AMRs with tracks are designed for all-terrain mobility, including on rough or uneven surfaces. Tracks can provide increased traction and stability, but may also require more maintenance than other locomotion types.</td>
    <td>Mining, construction, search and rescue</td>
    <td>
    <p>Wheel track</p>
    <img src="https://robots-blog.com/wp-content/uploads/image-20-1024x512.png"/>
    </td>
  </tr>
    <tr>
    <td>Wheel</td>
    <td>This is the most common form of locomotion for AGVs and AMRs. These robots have wheels that allow them to move in a straight line or turn. They may have different types of wheels, such as caster, drive, or omnidirectional, depending on the application.</td>
    <td>Manufacturing, warehousing, hospitals, hotels</td>
    <td>
    <p>AGV wheel</p>
    <img src="https://www.ketterer-drives.com/media/ketterer-fts-system-ket-rob-antriebsrad.jpg"/>
    </td>
  </tr>
  <tr>
    <td>Magnetic</td>
    <td>Some AGVs and AMRs use magnetic or electromagnetic technology to move around. These robots can move smoothly and precisely, and can be highly effective in applications where accuracy is critical. However, they may also require specialized infrastructure to operate.</td>
    <td>Automotive manufacturing, clean room environments, high-precision assembly</td>
    <td>
    <p>Magnetic locomotion</p>
    <img src="https://d3i71xaburhd42.cloudfront.net/f56e14e987996b4c960afcb8832cb1b109307313/2-Figure1-1.png"/>
    </td>
  </tr>
  <tr>
    <td>Propeller</td>
    <td>Some AMRs are designed to fly or hover using propellers, similar to drones. This allows them to move quickly and easily over obstacles or difficult terrain. However, they may also be more limited in terms of payload capacity and flight time.</td>
    <td>Agriculture, infrastructure inspection, surveillance</td>
    <td>
    <p>DJI Agras T20</p>
    <img src="https://cdn.store-assets.com/s/603108/f/5616781.png"/>
    </td>
  </tr>
</table>

**[⬆ Back to top](#automated-guided-vehicle-agv--autonomous-mobile-robot-amr)**

### Navigation

*AGVs* and *AMRs* utilize diverse navigation systems to navigate their respective paths. Typically, the selection of a navigation system is determined by the operational environment and the mission at hand.

**Magnetic tape** navigation is a prevalent navigation system utilized by AGVs and AMRs. This entails laying down magnetic tapes in a specific pattern that the robot can follow. The robot is equipped with magnetic sensors that use the magnetic field produced by the tape to navigate along a predetermined path.

Another navigation system utilized by *AMRs* is **laser navigation**. This system uses lasers and sensors to create a map of the robot's environment, which the robot can use to avoid obstacles and reach its destination.

Some *AMRs* also utilize **vision-based** navigation, in which cameras and sensors are used to identify visual cues in the robot's environment and construct a map that the robot can follow.

**Inertial navigation** is an additional navigation system utilized by some AGVs and AMRs. Using gyroscopes and accelerometers, this system measures the robot's movement and determines its position and orientation in space.

### AGV-Navigation types

<table>
  <tr>
    <th>Navigation type</th>
    <th>Description</th>
    <th>Examples</th>
  </tr>
  <tr>
    <td>Magnetic Tape Navigation</td>
    <td>The robot follows a magnetic tape that is laid out along a predetermined path. This method is commonly used in manufacturing facilities or warehouses where the robot needs to move along a fixed route.</td>
    <td> <a href= "https://www.roboteq.com/applications/all-blogs/18-building-a-magnetic-track-guided-agv">Roboteq</a>  
    <img src = "https://www.agvnetwork.com/images/technology/navigation-systems/200x137_Magnetic.jpg" height = 150 width = 700>
    </td>
  </tr>
    <td>Laser Navigation</td>
    <td>The robot uses laser sensors to create a map of its surroundings and navigate through a space. This method is commonly used in dynamic environments such as hospitals or airports, where the robot needs to adapt to changing obstacles or traffic patterns.</td>
    <td><a href="https://aethon.com/">aethon</a> <img src ="https://www.agvnetwork.com/images/technology/navigation-systems/laser_navogation_calculation.jpg"></td>
  <tr>
    <td>Vision-Based Navigation</td>
    <td>
    The robot uses cameras or other visual sensors to navigate through a space. This method is commonly used in outdoor environments or environments with complex layouts, such as parks or museums.</td>
    <td>
    <a href="https://www.youtube.com/watch?v=N0wa04ZPZN0">Boston Dynamic Spot</a>
    <img src="https://eu-images.contentstack.com/v3/assets/blt31d6b0704ba96e9d/blt762668bd0db301a9/63abe9a71f477123c43d2b4a/boston-dynamics-spot.jpg">
    </td>
  </tr>
  <tr>
    <td>Natural Feature Navigation</td>
    <td>
    The robot uses sensors to detect and navigate around natural features such as walls, columns, or trees. This method is commonly used in outdoor environments or environments with irregular shapes or layouts, such as amusement parks or zoos.
    </td>
    <td>
    <a href= "https://www.youtube.com/watch?v=Gac5UBkLHAk">Follow-Me AGV</a>
    <img src="https://www.agvnetwork.com/images/technology/navigation-systems/200x137_Natural.jpg">
    </td>
  </tr>
  <tr>
    <td>Inertial Navigation</td>
    <td>
    The robot uses inertial sensors to track its movement through a space. This method is commonly used in environments where GPS is not available, such as underground mines or warehouses with metal roofs.
    </td>
    <td>
    <a href = "http://www.dbhrobot.com/AGV-system/Inertial-navigation-AGV.html">DANBACH robot</a>
    </td>
  </tr>
  <tr>
    <td>Hybrid Navigation</td>
    <td>
    The robot uses a combination of different navigation methods to optimize its performance in a given environment. For example, a robot may use magnetic tape navigation in a factory, but switch to laser navigation when it enters a busy loading dock.
    </td>
    <td>
    <a href = "https://www.researchgate.net/publication/296693077_An_accurate_and_efficient_navigation_system_for_omnidirectional_robots_in_industrial_environments/figures?lo=1">Kuka</a>
    <img src = "https://www.researchgate.net/publication/296693077/figure/fig11/AS:961324616003608@1606209057682/The-KUKA-Moiros-robot-using-our-system-for-accurate-omnidirectional-navigation-during-a.jpg">
    </td>
  </tr>
</table>

### AMR-Navigation types

<table>
  <tr>
    <th>Navigation type</th>
    <th>Description</th>
    <th>Examples</th>
  </tr>
  <tr>
    <td>Laser Navigation</td>
    <td>AMRs use lasers to create a map of their environment and navigate autonomously. This type of navigation is particularly effective in settings where there are static obstacles, such as warehouses or hospitals.</td>
    <td>
    <a href="https://www.mobile-industrial-robots.com/solutions/robots/mir500/">MiR500</a>
    <img src="https://quantumrobotics.com.au/wp-content/uploads/2020/06/mir500.jpg" height = 150 width = 1300>
    </td>
  </tr>
  <tr>
    <td>Vision-based Navigation</td>
    <td>This type of navigation uses cameras and sensors to allow AMRs to interpret their surroundings and navigate around obstacles. It can be effective in environments where there are changing obstacles or objects with unpredictable movements, such as in retail settings.</td>
    <td>
    <a href="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DTc-BIoNOfk8&psig=AOvVaw2oi_U6f3Xhrc6PTA--9Bie&ust=1681957095870000&source=images&cd=vfe&ved=0CAQQjB1qFwoTCPDB8s7wtP4CFQAAAAAdAAAAABAE">Seegrid</a>
    <img src="https://i.ytimg.com/vi/Tc-BIoNOfk8/maxresdefault.jpg"></td>
  </tr>
  <tr>
    <td>Natural Feature Navigation</td>
    <td>AMRs use cameras and sensors to recognize and navigate based on natural features in their environment, such as walls and doors. This type of navigation is useful in settings where there are few or no artificial landmarks or obstacles.</td>
    <td>
    <a href="https://aethon.com/aethon-announces-new-t4-robot/">Aethon T4</a>
    <img src="https://aethon.com/wp-content/uploads/2018/10/T4-Front2.png">
    </td>
  </tr>
  <tr>
    <td>Inertial Navigation</td>
    <td>AMRs use internal sensors to measure their movement and orientation as they navigate. This type of navigation is often used in outdoor environments where GPS signals may be weak or unavailable.</td>
    <td>
    <a href="https://clearpathrobotics.com/jackal-small-unmanned-ground-vehicle/">Jackal</a>
    <img src="https://s3.amazonaws.com/assets.clearpathrobotics.com/wp-content/uploads/2016/08/24132105/Jackal_Vision_Sensor_Package.png"></td>
  </tr>
  <tr>
    <td>Hybrid Navigation</td>
    <td>AMRs combine multiple navigation types, such as laser and vision-based navigation, to provide robust and adaptable navigation in complex industrial or commercial settings. This type of navigation allows AMRs to navigate through dynamic environments with changing obstacles and conditions.</td>
    <td>
    <a href="https://spectrum.ieee.org/adept-introduces-lynx-autonomous-mobile-platform#:~:text=Meet%20Adept's%20newest%20mobile%20robot&text=This%20is%20Lynx%2C%20a%20brand,things%20may%20be%20in%20between.">The Adept Lynx with magnetic and laser navigation</a>
    <img src="https://www.castec.com.tw/upload/en/product/30_img_1.jpg"></td>
  </tr>
</table>

**[⬆ Back to top](#automated-guided-vehicle-agv--autonomous-mobile-robot-amr)**

### Data Collection

| Data Collection Method | Description | Examples |
| ---------------------- | --------------------------------------------------------------------- | ----------- |
| Lidar | Uses laser topology to scan the environment and create a 3D map | ![Velodyne Lidar](https://github.com/nuafal/MCTE-4362_-1911889/blob/main/AGV%20vs%20AMR/Sources/smart-city-privacy-2.gif)

  
