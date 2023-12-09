# Mile-High-MyRio
ME/AE6705 Mechatronics Final Project (Mile-High-MyRio) - Will Sherman &amp; Stef Crum

# Introduction
In the pursuit of pushing the boundaries of innovation and technology, the "Mile High MyRio" project emerged as a pioneering venture in the realm of high altitude weather balloon missions. This endeavor sought to elevate a MyRio microcontroller—a versatile and programmable embedded system—to the remarkable altitude of 100,000 feet, exposing it to the harsh conditions of the stratosphere. The primary objective of this project was not only to navigate the challenging environment at such altitudes but also to orchestrate a controlled descent, involving a ballistic phase followed by parachute deployment, ensuring the safe return of the MyRio microcontroller to the Earth's surface. 

As the stratosphere presents a unique set of challenges, including extreme temperatures and low atmospheric pressure, the Mile High MyRio project aimed to demonstrate the resilience and adaptability of the MyRio microcontroller in the face of these adversities. By orchestrating a demonstration mission, this project aimed to contribute valuable insights into the capabilities of the acquired knowledge in our mechatronics class. 

This paper provides a comprehensive overview of the Mile High MyRio project, detailing the design, implementation, and outcomes of the mission. From the initial conceptualization to the attempted execution of the high altitude weather balloon launch, ballistic descent, and parachute-assisted recovery, each phase is examined to shed light on the challenges encountered and the lessons learned.  
# Requierments
| Category                    | No. | Threshold/Objective\*                                                          | Requirement                                                                           | Value | Unit                                      | Comment                             |
| --------------------------- | --- | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------- | ----- | ----------------------------------------- | ----------------------------------- |
|                             | 1   | O                                                                              | Prototype is locatable base on GPS location                                           | T/F   |                                           |                                     |
| Data Capturing              | 2   | O                                                                              | System receives and record GPS position and velocity data                             | T/F   |                                           |                                     |
|                             | 3   | O   | System records  video                                                          | T/F                                                                                   |       |                                           |
|  | 4                           | O   | System records IMU acceleration and angular rate data                          | T/F                                                                                   |       |                                           |
| Weight/Dimensions           | 5   | T                                                                              | Prototype shall not exceed  the weight limit                                          | 4     | lbs                                       | (In accordance with FAA regulation) |
| Power                       | 6   | T                                                                              | Prototype shall operate for full flight profile (ascent & drop) on one battery charge | \> 5  | hour                                      |                                     |
| Quality Control (mandatory) | 7   | T                                                                              | Number of system bugs detected upon prototype demonstration                           | < 5   | bugs                                      |                                     |
|                             | 8  | O                                                                              | Number of system bugs detected upon prototype demonstration                           | 0     | bugs  |                                   |
| | 9                          | O   | prototype should be professional but not entirely manecured                    | ≥ 7 out of 10                                                                         |       | (1 to 10 with 10 being most professional) |
| | 10                          | O   | Number of operational bugs during modelled flight data                         | 5                                                                                     | bugs  |                                           |
| | 11                          | T   | Equillibrium speed w/ main chute deployed                                      | < 8                                                                                   | m/s   |                                           |
| | 12                          | O   | No Observed Damage to structure with components after crash test at 6 [m/s]    | T/F                                                                                   |       |                                           |
| Operations                 | 13  | O   | Prototype disconnects from Weather Balloon upon detection of sustained falling | T/F   |                                           |                                     |
| | 14                          | T   | Prototype is lifted to at least 80,000ft AGL  w/ high altitude weather balloon | 80,000                                                                                | ft    |                                           |
| | 15                          | O   | Prototype displays a radio-reflector during ascend                             | T/F                                                                                   |       |                                           |
| | 16                          | O   | Prototype deploys drogue and main chute at predetermined altitude              | T/F                                                                                   |       |                                           |

Our team meticulously selected the engineering requirements for the Mile High MyRio project to address the unique demands imposed by stratospheric conditions. The chosen specifications were tailored to ensure the MyRio microcontroller's robust performance amidst loss of GPS signal or a lack of ballon burst. Our focus on ballistic descent and parachute deployment was driven by the necessity to orchestrate a controlled return, safeguarding the microcontroller throughout its journey to the edge of space and back to Earth. By carefully aligning our engineering requirements with the challenges of high-altitude environments, we aimed to demonstrate the adaptability and resilience of the MyRio microcontroller while pushing the boundaries of technological exploration in the stratosphere.  

# Discussion of Challenges Encountered
While there were several challenges that we encountered during this project, I shall list the ones that we felt were most significant to us.  

## Interfacing the IMU to the MyRio 

Interfacing with the parts that we had bought specifically for this project proved to be much more challenging than expected. Due to LabView not being a standard language for these types of hardware, there was no documentation available. As a result we had to break down the communication protocols all the way to its binary form. Due to the combination of lack of documentation as well as unreliable documentation this proved to be impossible at times.  

## Actuating the burns 

The aggressive pull of current from our burn-resistors proved to be a challenging hurdle to overcome. On several occasions we had to iterate on our system, as the aggressive current pull from the resistors would take away power from our critical systems.  

## Geopolitical Climate 

The American sanctions on Russia caused a helium shortage, and as a result we were unable to obtain helium of a sufficient purity.  

# Hardware Implementation

# Demonstration

# Conclusion
