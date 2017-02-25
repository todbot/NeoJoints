<img src="./docs/neojoints-blink1-demo.jpg">

# NeoJoints
Neopixel Joints, millable on the Othermill

Table of Contents
=================

  * [What are these?](#what-are-these)
  * [Available NeoJoints](#available-neojoints)
  * [How to Solder](#how-to-solder)

## What are these?
NeoJoints make it easy to solder together pieces of WS2812 / NeoPixel-style
LED strip.

NeoJoints have the following features
* Available in multiple angles
* Solderable holes for adding additional power at joints
* Cuttable trace on data line for separating strips logically
* Mounting hole for 2-56 screw
* Single-sided millable on PCB mill like Othermill,
    with a single 1/32" endmill (though adding 1/8" to cleanup helps)

Originally from 5 Jun 2015 task for "Mill-a-Week": https://github.com/todbot/Mill-a-Week

![](https://c1.staticflickr.com/1/453/17888242663_c46d147722_n.jpg)



## Available NeoJoints

* **NeoJointV2-090**
    - 90-degree right angle

    <img src="./NeoJointsV2/NeoJointV2A-090.png" width=200>

* **NeoJointV2-000**
    - 0-degree straight joint

    <img src="./NeoJointsV2/NeoJointV2A-000.png" width=200>

* **NeoJointV2-082p43**
    - 82.43-degree right angle, for inner angle of segment display

    <img src="./NeoJointsV2/NeoJointV2A-082p43.png" width=200>

* **NeoJointV2-097p57**
    - 97.57-degree right angle, for outer angle of segment display

    <img src="./NeoJointsV2/NeoJointV2A-097p57.png" width=200>

* more coming...


## How to Solder

* Step 1: Get NeoJoint and LED strip pieces laid out correctly
  - Be sure to make sure data arrows are pointing correctly

  <img src="./docs/neojoint-solder-step1.jpg" width=650>


* Step 2: Turn over strips, put small solder blobs on *back* of each pad
  - Depending on the strip, you may need to scratch away adhesive layer or waterproofing

  <img src="./docs/neojoint-solder-step2.jpg" width=650>

* Step 3: Lay strip on top of NeoJoint, then heat up with soldering iron to melt solder blobs, one by one
  - Take care to keep strip aligned when melting first solder blob

  <img src="./docs/neojoint-solder-step3.jpg" width=650>


* Step 4: Continue until you've soldered down all points
  - You can look along the side of the strip to see if the solder has melted
  - And you can see if you have any solder bridges

  <img src="./docs/neojoint-solder-step4.jpg" width=650>
