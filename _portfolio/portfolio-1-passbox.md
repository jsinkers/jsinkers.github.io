---
title: "Cycling safety with PassBox"
excerpt: "Cycling safety research including the world's largest study on passing distance, and the world's first on-road assessment of minimum passing distance laws"
image: /images/passbox-map.png
collection: portfolio
---

![PassBox map](/images/passbox-map.png)


I started [PassBox](https://passbox.org) with Jonathan Nolan to conduct research on cycling and pedestrian safety. I developed the PassBox device to measure how close cars pass cyclists on the road. We fit these devices to volunteers' bicycles around Australia and collect data on how close they are passed by other vehicles. Collected data is reduced to passing events using software I have implemented that synchronises video footage to distance sensor readings and extracts passing events. Datasets are used to build models assessing the impact of advertising campaigns, explore different cycling infrastructure, and assess the effect of passing distance laws. I have presented our findings at several international conferences. See our data on the [PassBox map](https://passbox.org/map).

<!-- image of passbox device -->
![PassBox mounted to a rack](/images/passbox_rear.JPEG)
__PassBox device and action camera mounted to a rack__

We have also explored pedestrian safety using novel analysis methods to estimate pedestrian counts at intersections using pedestrian operated signal data.

<!-- reference to paper -->

## Publication: Are bicycle lanes effective?

[Are bicycle lanes effective? The relationship between passing distance and road characteristics](https://www.sciencedirect.com/science/article/pii/S0001457521002153), Accident Analysis and Prevention · Jun 14, 2021

By Jonathan Nolan, James Sinclair, Jim Savage

We have conducted the largest on-road study of passing distance to date, collecting data from 162 cyclists in Victoria and Western Australia, producing over 46,000 passing events. In this publication we found that protected bicycle lanes are 10 times more effective than painted bicycle lanes, and that painted bicycle lanes are better than no bicycle lane at all.

## Technology

- Arduino: electrical prototyping and programming using Arduino devices
- 3D Printing: PassBox device enclosures designed for 3D printing
- Python: data reduction reduces synchronises video footage to distance sensor readings
  and produces passing event videos. Object detection via TensorFlow is used to reject false positive passing events. Pandas is also used for data exploration and analysis
- Bash scripts: utility scripts
- AWS: S3, EC2