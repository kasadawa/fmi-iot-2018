<<<<<<< HEAD
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=Z5J7ZSXG5XC8Q)
# HomeAutomation
App specially build for Raspberry Pi devices. 
It's easy to use it for controlling array relays. 
The project is based on: Angular 2 CLI project and node-js server for backend. Controlling the Raspberry is implemented with Johnny-Five library.  
## Wiring
The diagram below is showing how you need to wire you Raspbery with the 4 array relay module:
[Wiring](https://drive.google.com/open?id=0Bx5LQXY9Kwz_Wjh2RWVXZ3RINlE)
## Pre - requirements
* NodeJS installed 
* npm installed 

To install them run: 
```
sudo apt-get install nodejs npm node-semver
```
## Installation 
Run : 
```
git clone https://github.com/kasadawa/home_automation.git
```
Navigate to home_automation/server and  install the dependencies: 
```
npm install
```
Then start the server : 
```
node server
```
Open the browser and navigate to ```192.168.100.5:3000```.

*NOTE! your local IP should be 192.168.100.5 (check it with ifconfig).
If your IP is different you need to rebuild the project and restart the server.
For further information go to my [instructable](https://www.instructables.com/id/Cheap-Effective-and-Modern-Home-Automation/)*

The default usename and password are ```admin```.
When you login you can change them from the Advanced option tab. Also after the first login you need to provide your own database:

## Create MongoDB database
Register to [mlab](www.mlab.com), create new database, add collection with name: ```devices``` , include user, copy and paste the generated URI( it should look like ```mongodb://<user>:<password>n@ds117311.mlab.com:17311/mean_test``` ).  
Also Johnny-File requires [Raspi-io](https://github.com/nebrius/raspi-io) to be installed.

## Advanced Tab 
Can configure own username and password, to pass other Database URI and also to extend the pin selection.
=======
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

>>>>>>> f8a98407186b37438e8ab62243229cfc7315636c
