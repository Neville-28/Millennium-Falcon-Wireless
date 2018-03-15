# Millennium-Falcon-Wireless

This is a report for my individual project. This individual project is related to my final group project. My part so far is to send data from my ardunio to another arduino. In order to realize the remote control system. 

We use Autodesk design the drone. 
We use 3-D printer to print our drone. 

## Prerequisites
### HardWare
For this remote system we should prepare :

1.one uno

2.one wireless shield  

3.one Xbee. 
### SoftWare
1.Arduino
## Installation
First I plug in the Xbee modules into the wireless shield. Thus the device can be a receiver or a sender.
Be sure that module's pointy end is lined up with the edge of the board. Otherwise the device will not work.

## Progress
When we first to test whether the device can send data. The test goes well. However, when we try to send sample data to another arduino. We wil always receive some strange symbols. 

After we figure out the problems,we turn into the next stage. WE will use buttom to control the speed. What I will do is to send the data read from the program and send to another arduino. 

`` digitalRead(pinMode)
``

and 

`` digitalWrite(data)
``


For example


`` if(digitalRead(u) == HIGH) {
``   
`` Serial.write('u');
``
``}
``
  
  
  
  This is when one of the button is pressed. The receiver arduino will receive the signal and the speed of motor will be add automatically. 

Before we try to use potentiometer use change the speed, however we found the data transimitting is not static. So we finally decide to use button to change the speed. 

The power supply we use for the motor is Tenergy 11.1V 1200mAh. Unfortunately, when we try to use the power to demo the motors. We connect the wires reversely/ The power supply is destroyed. So, for the midterm demo, we can only demo part of the project. 

In the future we plan to use the proper battery foe the final and try to test the whole drone when every component arrived. 

We also plan to add more functions for our drone.

## Conclusion
Overall we spend a lot of time dealing with the wires and models. 

The 3-D printer took us a lot of time. Overall, we finish most of our goal.

## Author
Jingyu Liu
2018/3/14






