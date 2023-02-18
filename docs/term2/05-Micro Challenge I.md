---
hide:
    - toc
---

#  M I C R O   C H A L L E N G E  · I




Cagsun Acemoglu · Josephine Bourghardt · Korbi Nida-Rumelin · Ramiro Arganaraz 


These are my personal reflection and notes from the first Micro Challenge. 

## PROJECT

How can we rethink the relationship we have with water? Can a first person perspective of using your own grey water act as behavioural change in our relationship with water?

![](https://i.imgur.com/FD3E49m.png)

Can a modular grey water collection system create respect for the resource that holds life? With water as the main substance it can provide isolation and allow life to flourish, housing plants and other species, allowing the transfer of materials, filtering them where needed, and optimising energy usage by decreasing water consumption of fresh resources and waste water collection and management, Can a simple ‘water brick’ create a future where a modular wall of water collection that adapts and transforms depending on needs become standard in homes? Can making vertical gardening, growing your own food, and water accessible to people in urban environments where it is typical that space is an issue?

WHAT
We are aiming to create an open source modular system for citizens to collect and reuse grey water in the living space where creating awareness of water systems and what you flush down the drain, knowledge of saving and reusing grey water can help conserve fresh water resources, reduce strain on municipal water treatment systems, as well as reduce the amount of wastewater released into the environment.

Integrating grey water storage systems in apartments has the potential to greatly impact urban water systems by improving water management, conserving resources, and making cities more sustainable. Grey water is the wastewater generated from sources such as sinks, showers, and washing machines. If collected and treated properly, grey water can be safely reused for non-potable purposes, such as flushing toilets, watering plants, and cleaning. 

HOW 

An artefact that monitor (and communicates) water quality for growing plants in an urban environment. It will be modular, with a system of water containers based on waste materials that is compatible with a larger water system project. In prototyping we will use Arduino’s together with sensors (that are readily available, cheap, simple, etc) and perhaps use a laser cut structure to hold the testing kit and basic water containers.

A kit that can be used in further research of grey water collection and reuse systems in urban environments. Testing to understand water quality after different filtering, what quality is needed / acceptable to be used for watering plants, what is the quality of the water after plant filtration. For citizen use.. understand water systems around you, making data/ information available


WHY

Allowing citizens to measure their own water quality could help to increase awareness and engagement with water conservation and management efforts. There are several benefits to allowing citizens to test their own water quality, including increased awareness, empowerment, cost savings, improved water management, and increased trust.

By testing their own water quality, citizens can learn about the quality of the water they are using and the presence of any contaminants. This increased awareness can lead to greater understanding of the importance of water conservation and the need to protect this precious resource.

It can also allow for citizens to take an active role in monitoring and improving the quality of their water supply. This sense of empowerment can lead to greater engagement and support for water management and conservation initiatives. It can potentially save money by identifying and addressing any water quality problems before they become more serious and costly to fix.
By testing your own water quality, citizens can provide valuable data to water management agencies, helping them to make more informed decisions about water treatment and distribution. This can lead to improved water management and better protection of public health, which could also result in an increased trust in water management agencies, as they can see that their water is being monitored and tested on a regular basis.

We wanted to understand what measuring water quality could actually mean and what measurements that are valuable in different situations. During this Micro Challenge we wanted to create an artefact that can be used as a resource throughout the term. We proceeded in looking into what to measure and what type of quality of water that matters to outcome. To start off we will be using sensors and Arduino to measure parameters in water quality that are important to plants, potted or for example in a hydroponic system. Some of the important parameters are PH Value, Temperature and Conductivity. How could these sensors become part of a system in our further process and interventions to measure water quality? 

SENSORS FOR MEASURING WATER QUALITY
![](https://i.imgur.com/ROmBF4V.jpg)
![](https://i.imgur.com/oci8blR.jpg)
One Wire Temperature Sensor - DS18B20
https://www.seeedstudio.com/One-Wire-Temperature-Sensor-p-1235.html 

Temperature testing is the process of measuring temperature levels in water. Temperature is a key factor in water chemistry. Temperature affects the dissolved oxygen levels in water, the rate of photosynthesis, metabolic rates of organisms, etc. Aquatic organisms depend on particular temperature ranges for their health. Each species thrives in a specific temperature range, and many animals use temperature as a signal for when to reproduce and when to migrate. If there is an abnormality in temperature this can disrupt the balance of aquatic ecosystems with devastating effect. Water temperature also impacts water density; differences in water temperature and density can cause stratification.

https://www.aquaread.com/sensors/temperature

PH SENSOR

![](https://i.imgur.com/wqdDUbr.jpg)
PH sensors play a very important role in water quality and water treatment. One of the most important indicators of water quality test is its pH. 

pH and conductivity are key parameters for measuring the pH of a substance while monitoring the level of nutrients, salts or impurities present. pH and conductivity measurements are used in a variety of applications, including industrial water and wastewater treatment, boiler maintenance and agriculture, as well as aquariums and aquaculture.

Hydrogen potential or “pH” is a measure of the concentration of hydrogen ions in a sample and is used to determine the acidity or alkalinity of a product. pH values range from 0-14, with 0 being acidic, 7 being neutral and 14 being basic. Water quality depends on the proper pH value. For example, in acidic water, toxic heavy metals dissolve easily and are more harmful to organisms. pH levels also affect the availability of essential 
plant nutrients, with many nutrients less available at pH levels above 7.


The pH electrode consists of a reference electrode, a reference solution, a reference fluid connection and a glass bulb with a hydrated gel layer. Once the electrode is immersed in the sample, a current is generated and the charge of the reference solution inside the bulb is measured compared to the solution on the outside of the gel layer. The result is a pH measurement.
 https://wiki.dfrobot.com/Gravity__Analog_pH_Sensor_Meter_Kit_V2_SKU_SEN0161-V2 
 
![](https://i.imgur.com/qNimjgE.jpg)

CONDUCTIVITY 
![](https://i.imgur.com/OvSegE9.jpg)
Conductivity is a measurement of the concentration of ions present in a sample. It is calculated by the ability of a substance to transmit an electric current in a defined area. Conductivity is measured in units called Siemens (S) (e.g. milliSiemens per centimetre mS/cm or microSiemens per centimetre μS/cm).

Conductivity is measured by conductance between two or four electrodes using the current method or potentiometric method. When the electrodes are immersed in the sample, the electrodes cause a current to pass through the sample solution. The relative concentration of ions in the solution will determine the conductivity or resistivity of the sample. The conductivity is expressed in Siemens units.

2 electrode probes (amperometers) – they work through two electrodes that are isolated from each other. Made of non-reactive materials and constructed so that both will be in contact with the sample at the same time. These two electrodes pass current through the sample at a specific frequency, the more ions present, the higher the EC reading.
4 Electrode Probe (Potentiometer) – The electrode body has four platinum rings. The top and bottom rings (on the outside) apply AC voltage to the sam planned and executed the project. (Explain personal contributions)
Integrated Design (How you designed it - relation between elements)
Honest Design (use of technology in a meaningful way, in relation to your interventions)
Explore design boundaries (based on your expertise)

We used these specific sensors as they were available in the FabLab. It took longer to calibrate the sensors than we expected. The project also quickly became very technical, where we from the start spoke about 'hacking' these sensors and making our own, mostly to play around with them and use the microchallenge to understand water quality from different sources and how different simple filters could effect the quality. 

When the project took this turn and became very technical it also played a roll in how the overall design and project proceeded within the water collection tool part. As the sensors became a central part of the design and the time it takes to calibrate, understand the software and code, it was hard to use them to also understand how they could be integrated into a system, or how to design something where they could be a part of a system. 

TOOL
How can we create a tool that holds the sensors we need in place and lets water pass through to measure the flow? We wanted to learn more about sensors, how they work and what they show and to create a system where we could use this information in different stages of a water system. During this term we are working with water in different ways, testing filters and modular systems to collect an reuse grey water. For this it was important that we could use the sensors in different places, size of container and that in the end it could be used to learn more about how it could be fit into a bigger system. 
![](https://i.imgur.com/lW8RyLo.jpg)
![](https://i.imgur.com/Nd4qMfU.jpg)

We therefor used part of a standard 63 mm PVC transparent pipe that could possibly in the future be used in a pipe system, or at least at this point illustrate what it could look like, even though eventually in a smaller scale. 

![](https://i.imgur.com/CiwIT3M.jpg)
![](https://i.imgur.com/PGqEi8V.jpg)
To hold the sensors in place to measure parameters in flowing water we used a standard PVC transparent 63mm pipe, and laser cut pieces to create caps holding water tubes and sensors in place. The caps can be removed and pieces can be changed to add other parts for future use of measuring different quality parameters of water or changing tubes of water flow. 

Each cap consists of 5 laser cut 5 mm acrylic pieces that hold a rubber ring to water seal and are held together with a screw.
![](https://i.imgur.com/mbVvI6O.jpg)
![](https://i.imgur.com/u0edMkH.jpg)
The tubes that will supply and release the pipe with water are fastened through the pre-cut holes and with hot silicone glue. The same is for the cap with sensors.
![](https://i.imgur.com/3us3xjN.jpg)

SYSTEM


![](https://i.imgur.com/OOe2AMR.jpg)
This measurement tool is then connected to a water resource where water is pushed into the tool with a pump until it is full, where it can stay to be measured before it it released from an output tube under. By using this method we can measure quality of flowing water from different places in a modular setting, as well as part of a bigger flowing system.

For the full documentation of how it was made and what materials and resources that were used follow the link to our main page where Korbi and I worked mainly on the manufacturing part. https://hackmd.io/@Kgea_wTSQ1i-eiGs2APlag/HJ5MJ6sTj

REFLECTION

The measurement tool that we created during the first Micro Challenge became a more technical project than I had expected and I think that I would have preferred engaging more with making or hacking these sensors in a DIY version to then also spend time on understanding how and where they could be used to be useful for the process of this terms projects. Aside from this it was an interesting learning process and a good re introduction to using the machines in the lab, here specifically the Laser cutter. It was also a good insight to how existing sensors work and a reminder of the time it takes to calibrate and function them together with each other and systems. The project was also for me a good reminder of that I have to keep my roll in the project, which was during this project product development where Korbi and I worked on the artefact, how it could be assembled and used and specifically how it could be water tight. The part of creating a watertight piece was for me the most interesting part, as it will be important further on on the project I’m working on. We learned how Fab Lab has worked on a 3D Paste Printer for Bio materials and worked from the same method of using rubber rings in a custom cap for a tube. This knowledge can be very useful for further parts of this term. 

I realised, that I, during the progress of the artefact lost track of what it was for and how we wanted to use it, when all the existing sensors that we could use from the Fab Lab and electronics became a part of it. In the process of trying to understand this and how all the electronics and sensors worked, it slowed down my creative process and making decisions take longer than needed, which will be something I’m going to remember for next time. 