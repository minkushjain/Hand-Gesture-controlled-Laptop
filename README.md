# Hand-Gesture-controlled-Laptop
Hand Gestured controlled laptop using Arduino

## Description

In this project, I have implemented a simple Arduino based hand gesture control where you can control some functions of your web browser like switching between tabs, scrolling up and down in web pages, shift between tasks (applications), play or pause a video and increase or decrease the volume (in VLC Player) with the help of hand gestures.

It uses 'PySerial' and 'PyAutoGUI' libraries in Python to control the input ports and mimic the actions of mouse and keyboard.

<img src="https://github.com/minkushjain/Hand-Gesture-controlled-Laptop/blob/master/img/IMG_5204.jpg" width="48" height="70">

## Getting Started
For controlling the web browser and windows, run 'webpage_gesture.ino' in Arduino IDE and 'webpage_gesture.ino' in Python IDLE.

For video gestures, run 'vlc_gesture.ino' and 'vlc_gesture.py' in Arudino IDE and Python IDLE respectively.

Install 'pyserial' and 'pyautogui' in python using pip command

## Components Required
-Arduino UNO board

-Ultrasonic Sensor x 2

-Jumper Wires

-Laptop

## Gestures

### VLC MEDIA PLAYER GESTURES:
Action 1: When both the hands are placed up before the sensor at a particular far distance then the video in VLC player should Play/Pause.

Action 2: When right hand is placed up before the sensor at a particular far distance then the video should Fast Forward one step.

Action 3: When left hand is placed up before the sensor at a particular far distance then the video should Rewind one step.

Action 4: When right hand is placed up before the sensor at a particular near distance and then if moved towards the sensor the video should fast forward and if moved away the video should Rewind.

Action 5: When left hand is placed up before the sensor at a particular near distance and then if moved towards the sensor the volume of video should increase and if moved away the volume should Decrease.

### LAPTOP INTERFACE GESTURES:
Gesture 1: Place your hand in front of the Right Ultrasonic Sensor at a distance (between 15CM to 35CM) for a small duration and move your hand away from the sensor. This gesture will Scroll Down the Web Page or Decrease the Volume.

Gesture 2: Place your hand in front of the Right Ultrasonic Sensor at a distance (between 15CM to 35CM) for a small duration and move your hand towards the sensor. This gesture will Scroll up the Web Page or Increase the Volume.

Gesture 3: Swipe your hand in front of the Right Ultrasonic Sensor. This gesture will move to the Next Tab.

Gesture 4: Swipe your hand in front of the Left Ultrasonic Sensor. This gesture will move to the Previous Tab or Play/Pause the Video.

Gesture 5: Swipe your hand across both the sensors (Left Sensor first). This action will Switch between Tasks.


