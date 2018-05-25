# FMI-IOT-2018


## Main Idea
In our society the most common things that customers are giving their money are: 

* medicals (not excluding dr*g*) 
* pleasure (not excluding *** ) 
* security 

Because the first 2 are ilеgal I desided to create THE - "Security door".
Customers are giving a big amounts for secure doors and special locker.
The project is highly applicable for every home or office door. 
Everything is mostly done from web so the user will be able to unlock his door from web and also he can check the door status (OPEN / CLOSED) 


## Hardware 
The project can be implemented with different hardware but the things i choise are : 
1. Rasberry Pi ( model B+)
2. Magnet Sensor
3. Electromagnetic strike
4. Display ( not required ) 
5. Relay module (4 array) 
6. 12V DC PSU 
7. Wifi dongle (Edimax) 


##  Software 
I am a javascript entusiast so we will use Johny-Five as a libraly for the Raspberry.
NodeJS server will listen for the requests and will authenticate them with the help of JWT token. 
We need to provide to our clients some web interface and mobile app.(comming soon) 



## Wiring 
Follow up this tutorial to wire the raspberry Pi with the [Relay module](https://drive.google.com/file/d/0Bx5LQXY9Kwz_Wjh2RWVXZ3RINlE/view)
The magnetic sensor needs to be attached to PIN ... 
Display ...
Power pu the Electromagnetic strike with the 12V DC Power supply , then cut one of the cables and connect the both sides on the relay. (needs to be reworked) 

