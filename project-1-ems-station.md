---
layout: default
title: "Project 1: EMS Station"
---

# Project 1: EMS Station

## 1. Project Overview

We built an EMS station. A computer controls it. The traffic light flashes yellow. When there is an emergency, the cars stop. The garage door opens. The ambulance goes out. Then the door closes.

## 2. Planning and Design

## 3. Build Process

### Step 1: Hooking up the board


This is the Hummingbird board with the micro:bit plugged into the computer. I started with this so I could connect it to Snap! later.

### Step 2: Testing a sensor

I hooked up a distance sensor to the board with a wire. I tested it to see how the sensors plug in.

### Step 3: Getting the wires and LEDs ready

Here I got the sensor and LED wires ready. The sensor wire goes into the blue sensor port, and the LEDs go in the yellow and green ports.

## 4. Code

### First scripts


This is my first Snap! code. It has the Alonzo sprite scripts, the sound sensor, and the servo block. The city map on the right is the stage.

### Sound sensor and servo


Here I used the sound sensor to move the servo. If the sound is low it goes one way, and if it's loud it goes the other way. I also tested the LED blinking.

### Traffic light LEDs and siren


I made the LED sequence for the traffic light, with waits in between each color. I also made the siren script that plays notes when the emergency message is sent.

### Starting the emergency


This script waits until Alonzo touches the EMS station. Then it broadcasts "emergency" and changes Alonzo to the EMT costume.

## 5. Snap! Project Link

[Click here to open my Snap! project](WT2565067.github.io)

## 6. How the System Works

**Inputs:** The sound sensor hears the siren. The light sensor sees the ambulance.

**Processing:** My code checks the sensors. It decides what to do.

**Outputs:** The lights turn on and off. The servo opens the door. The sounds play.

**Steps:**
1. The light flashes yellow.
2. The sensor hears the siren.
3. The cars stop.
4. The door opens.
5. The ambulance goes out.
6. The sensor sees it.
7. The door closes.
8. The light flashes yellow again.

## 7. Testing and Debugging

**Problem 1: An LED did not turn on or was in the wrong order**
- What happened: One of my LEDs did not turn on, or the lights were in the wrong order.
- What I thought caused it: I thought the wire was in the wrong port, or the LED number in my code was wrong.
- What I changed: I checked the wires and I checked the LED numbers in my code.
- What happened after: The LEDs worked in the right order.
- What I learned: The LED number in the code has to match the port the wire is plugged into.

**Problem 2: My code did not do what I expected**
- What happened: I ran my code, and it did not do what I wanted.
- What I thought caused it: I thought a block was in the wrong place, or a number was wrong.
- What I changed: I looked at my blocks one at a time and fixed the ones that were wrong. Then I ran it again.
- What happened after: The code worked better.
- What I learned: When code does not work, I should test it in small parts and fix one thing at a time.

## 8. Final Product


<img width="1600" height="1200" alt="5200befd-1184-45f3-8061-68cc8cdc575e" src="https://github.com/user-attachments/assets/174669e5-054d-4bf1-b1a5-07eca28c7a5c" />
<img width="1600" height="1200" alt="aac89440-47e1-4eca-8d99-cf60e723b167" src="https://github.com/user-attachments/assets/34ea29f0-f940-4b33-bbe5-a64dc64be189" />

## 9. Reflection

**1. What am I most proud of?**
I am most proud of my Snap! code. It controls the sensors, the lights, and the sounds.

**2. What was the hardest part?**
The hardest part was getting my code to do what I wanted. I had to fix it a few times.

**3. What did I learn about inputs and outputs?**
Sensors are inputs. They give the computer numbers. The code uses the numbers to control the outputs, like the LEDs and the servo.

**4. What would I improve?**
If I had more time, I would make the code and the build work even smoother.

**5. What did I do?**
I worked alone. I built the project and wrote all of the code myself.
