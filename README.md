
# FMI-IOT-2018


## Main Idea
In our society the most common things that customers are giving their money are: 

* medicals
* pleasure
* security

Because the first 2 are ilеgal I desided to create THE - "Security door".
Customers are giving a big amounts for secure doors and special locker.
The project is highly applicable for every home or office door. 
Everything is mostly done from web so the user will be able to unlock his door from web and also he can check the door status (OPEN / CLOSED) 

## Features
From the web interface you can do manipulation on your raspberry: 
 - add new devices to the relay ( add more than one door lock or some onther switches)
 - turn on/off device
 - timer switch 
 - add more gpio pins to the software
 - receive custom email notifications when the door change its position
 - other features 

## Hardware 
The project can be implemented with different hardware but the things i choise are : 
1. Rasberry Pi ( model B+)
2. Magnet Sensor
3. Electromagnetic strike
4. Relay module (4 array) 
5. 12V DC PSU 
6. Wifi dongle (Edimax) 


##  Software 
I am a javascript entusiast so we will use Johny-Five as a libraly for the Raspberry.
NodeJS server will listen for the requests and will authenticate them with the help of JWT token. 
We need to provide to our clients some web interface and mobile app.(comming soon) 



## Wiring 
Follow up this tutorial to wire the raspberry Pi with the [Relay module](https://drive.google.com/file/d/0Bx5LQXY9Kwz_Wjh2RWVXZ3RINlE/view)
The magnetic sensor needs to be attached to PIN P1-40 ( physical pin number)
Power the Electromagnetic strike with the 12V DC Power supply , then cut one of the cables and connect the both sides on the relay. 

![](src/assets/images/fritzing.png?raw=true)
Thanks to Fritzing.org

## Note! 
The project is a part of [Home automation](https://github.com/kasadawa/home_automation)


## Executing the project 
In order to run the project you need to follow the instructions on the Home automation page.

## What needs to be improved ? 
* There is a problem with not fixed IP address and it can be solved easyly just with asking on what IP operate, on the first screen when you the web app. 
* Timer is not showing the duration correctly
* All of the Angular code needs to be improved ( cleanup )
* Door status is not showed on the screen, but it's passed on the console.

