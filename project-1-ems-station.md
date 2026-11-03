---
layout: default
title: "Project 1: EMS Station"
---

# Project 1: EMS Station

## 1. Project Overview

We built an EMS station. A computer controls it. The traffic light flashes yellow. When there is an emergency, the cars stop. The garage door opens. The ambulance goes out. Then the door closes.

## 2. Planning and Design
**What the station is supposed to do:** The EMS station is on a busy highway. When there is an emergency, the traffic has to stop in both directions so the ambulance can get out safely. Most of the time, the traffic light just flashes yellow.

**Parts I planned to use:**
- Red, yellow, and green LEDs: These make the traffic light. Red is on top, yellow is in the middle, and green is on the bottom.
- Sound sensor: It hears the siren so the system knows there is an emergency.
- Position servo: It opens and closes the garage door.
- Light sensor: It sees when the ambulance leaves the station.
- micro:bit, breakout board, and battery pack: These run everything and connect to Snap!

**My plan:**
1. The light flashes yellow like normal.
2. A call comes in and the siren plays.
3. The sound sensor hears the siren. The garage door opens, and the light goes yellow, then red to stop the cars.
4. The ambulance drives out. The light sensor sees it leave.
5. The door closes. The light goes green for a short time, then goes back to flashing yellow.

**What I wanted my code to do first:** I wanted to get the traffic light working first. Then I added the siren and sound sensor, then the servo for the door, and last the light sensor.
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

[Click here to open my Snap! project](https://snap.berkeley.edu/snap/snap.html#present:Username=lvhs10&ProjectName=EMS%20Project%20-%20New%20Starter%20Code%204%2024)

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

## What I Finished and What I Learned

**What I finished:**

- The traffic light LED sequence
- The siren script
- The sound sensor moving the servo
- The Alonzo emergency script

**What I did not finish before time ran out:** The hands-on build of the EMS station.

**What I learned:** I learned that it is hard to put a servo on cardboard.

## 8. Final Product


<img width="1600" height="1200" alt="5200befd-1184-45f3-8061-68cc8cdc575e" src="https://github.com/user-attachments/assets/174669e5-054d-4bf1-b1a5-07eca28c7a5c"/>

*Picture 1: My Snap! program on the computer screen, with the traffic light, siren, and servo scripts.*

<img width="1600" height="1200" alt="aac89440-47e1-4eca-8d99-cf60e723b167" src="https://github.com/user-attachments/assets/34ea29f0-f940-4b33-bbe5-a64dc64be189"/> 

*Picture 2: The same program from farther away, with the city map stage on the right.*

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
