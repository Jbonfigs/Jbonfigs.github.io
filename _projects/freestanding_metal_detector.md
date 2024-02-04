---
title: "Free Standing Metal Detector"
excerpt: "An embedded system designed to detect the location of a metal washer.<br/><img src='https://youtube.com/shorts/tptHNiDqZCQ?feature=share'>"
collection: projects
---

This freestanding metal detector project emerged as the culmination of a collaborative effort within a university setting, specifically undertaken as part of a comprehensive course. The project was completed by a team of four individuals, consisting of two electrical engineers and two computer engineers. The electrical engineers took charge of the hardware aspects, developing schematic designs and circuit construction, while the computer engineers generated the firmware design and implementation. This university project not only showcased the team's technical proficiency but also underscored the importance of interdisciplinary collaboration in the pursuit large complex solutions. Through the amalgamation of hardware and software expertise, we successfully delivered a freestanding metal detector that stands as a testament to their dedication and the enriching educational experience provided by the university course.

In addition to the interdisciplinary collaboration and technical prowess demonstrated in the university project, specific project requirements were outlined to enhance the functionality of the freestanding metal detector. One key requirement involved the implementation of a counter system, where each detected washer would contribute to an incrementing count. This counter was designed to be displayed directly on the Basys 3 FPGA, providing a real-time visual representation of the number of washers detected during operation. Furthermore, the project incorporated a visual feedback mechanism by utilizing the LEDs on the FPGA. The strength of the metal signal, indicative of the proximity and size of the detected object, was translated into a corresponding display on the LEDs. 

![alt text](/images/block_diagram.png)

Central to the success of our freestanding metal detector project was the comprehensive design approach facilitated by a detailed block diagram, which served as a visual roadmap for the integration of various components. The block diagram not only encapsulated the hardware schematic and FPGA circuitry but also included the incorporation of the MicroBlaze softcore processor. Leveraging the MicroBlaze architecture provided a flexible and scalable foundation for implementing the detection algorithm, allowing for efficient communication between hardware and software elements.

![alt text](/images/detection_flowchart.png)

The detection algorithm, a pivotal component of our project, was crafted using embedded C practices, ensuring a balance between computational efficiency and algorithmic sophistication. Through memory mapping, we established a coherent framework for data exchange between the FPGA board and the algorithm, enabling swift and reliable processing of voltage variations captured through the JXADC ports. 

