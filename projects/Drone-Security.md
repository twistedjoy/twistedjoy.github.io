---
layout: project
type: project
image: images/micromouse.jpg
title: Drone Security
permalink: projects/wireless-drone-security
# All dates must be YYYY-MM-DD format!
date: 2015-07-01
labels:
  - wireless penetration
  - drones
summary: My team conducted tests to capture and parse the wireless traffic of drones.
---

**SAMPLE (PROJECT TEMPLATE)**

<div class="ui small rounded images">
  <img class="ui image" src="../images/micromouse-robot.png">
  <img class="ui image" src="../images/micromouse-robot-2.jpg">
  <img class="ui image" src="../images/micromouse.jpg">
  <img class="ui image" src="../images/micromouse-circuit.png">
</div>

This project took place over multiple semesters, wherein we learned Kali Linux in the first semester, and then went on to learn about drone applications and security in the next semester. Along the way, we transitioned

For this project, 

Here is some code that illustrates how we read values from the line sensors:

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Cyber Security, Drone Applications and Security VIP (Vertically Integrated Project) Website](https://sites.google.com/a/hawaii.edu/uh-vip/teams/UAS).
You can also visit the Github repository of the project: (https://github.com/M5DroneSecurity/M5DS1)



