---
title: "Cycling safety with PassBox"
excerpt: "Cycling safety research including the world's largest study on passing distance, and the world's first on-road assessment of minimum passing distance laws"
image: /images/passbox-map.png
collection: portfolio
permalink: /portfolio/passbox
publication_tag: passbox
---

![PassBox map](/images/passbox-map.png)


I started [PassBox](https://passbox.org) with Jonathan Nolan to help improve cycling and pedestrian safety with targeted research. I developed the PassBox device to measure how close cars pass cyclists on the road. This is an Arduino based device that uses ultrasonic sensors for measuring passing distance, while also collecting GPS data. I designed and fabricated the enclosures. We have fitted these devices to hundreds of volunteers' bicycles around Australia to collect data on how they are getting passed by other vehicles on the road. Collected data is reduced to passing events using purpose-built software I have developed that synchronises video footage to distance sensor readings and extracts passing events. These passing events are then coded according to infrastructure, the type of vehicle, etc. and are then used to build models assessing the impact of advertising campaigns, explore different cycling infrastructure, and assess the effect of passing distance laws. I have presented our findings at several international conferences, and we have had peer-reviewed journal articles published.

Check out the [PassBox map](https://passbox.org/map) to see all the passing events we have collected.

<!-- image of passbox device -->
![PassBox mounted to a rack](/images/passbox_rear.JPEG)
__PassBox device and action camera mounted to a rack__

We have also conducted pedestrian safety analysis using novel methods to estimate pedestrian counts at intersections using pedestrian operated signal data in combination with crash statistics.

<!-- reference to paper -->

<!--## Publication: Are bicycle lanes effective?

Please see the publications

[Are bicycle lanes effective? The relationship between passing distance and road characteristics](https://www.sciencedirect.com/science/article/pii/S0001457521002153), Accident Analysis and Prevention · Jun 14, 2021

By Jonathan Nolan, James Sinclair, Jim Savage

We have conducted the largest on-road study of passing distance to date, collecting data from 162 cyclists in Victoria and Western Australia, producing over 46,000 passing events. In this publication we found that protected bicycle lanes are 10 times more effective than painted bicycle lanes, and that painted bicycle lanes are better than no bicycle lane at all.-->

## Technology

- __Python:__ data reduction reduces synchronises video footage to distance sensor readings
  and produces passing event videos. Object detection via TensorFlow is used to reject false positive passing events. Pandas is also used for data exploration and analysis
- __Bash scripts:__ misc. utility scripts for managing data
- __Arduino:__ electrical prototyping and programming using Arduino devices
- __AWS:__ S3, EC2
- __Electronics:__ design and fabrication of custom electronics including PCB design
- __3D Printing:__ PassBox device enclosures designed for 3D printing