[![L3G4200D](L3G4200D_I2CS.png)](https://www.controleverything.com/content/Gyro?sku=L3G4200D_I2CS)
# L3G4200D
L3G4200D 3 Axis Gyroscope Sensor

The L3G4200D provides 3-Axis ultra stable Digital Gyrometer output using I²C communications.

This Device is available from ControlEverything.com [SKU: L3G4200D_I2CS]

https://www.controleverything.com/content/Gyro?sku=L3G4200D_I2CS

This Sample code can be used with Raspberry Pi, Arduino, Particle Photon, Beaglebone Black and Onion Omega.

## Java
Download and install pi4j library on Raspberry pi. Steps to install pi4j are provided at:

http://pi4j.com/install.html

Download (or git pull) the code in pi.

Compile the java program.
```cpp
$> pi4j L3G4200D.java
```

Run the java program.
```cpp
$> pi4j L3G4200D
```

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python L3G4200D.py
```

## Arduino
Download and install Arduino Software (IDE) on your machine. Steps to install Arduino are provided at:

https://www.arduino.cc/en/Main/Software

Download (or git pull) the code and double click the file to run the program.

Compile and upload the code on Arduino IDE and see the output on Serial Monitor.


## Particle Photon

Login to your Photon and setup your device according to steps provided at:

https://docs.particle.io/guide/getting-started/connect/photon/

Download (or git pull) the code. Go to online IDE and copy the code.

https://build.particle.io/build/

Verify and flash the code on your Photon. Code output is shown in logs at dashboard:

https://dashboard.particle.io/user/logs


## C

Setup your BeagleBone Black according to steps provided at:

https://beagleboard.org/getting-started

Download (or git pull) the code in Beaglebone Black.

Compile the c program.
```cpp
$>gcc L3G4200D.c -o L3G4200D
```
Run the c program.
```cpp
$>./L3G4200D
```

## Onion Omega

Get Started and setting up the Onion Omega according to steps provided at :

https://wiki.onion.io/Get-Started

To install the Python module, run the following commands:
```cpp
opkg update
```
```cpp
opkg install python-light pyOnionI2C
```

Download (or git pull) the code in Onion Omega. Run the program.

```cpp
$> python L3G4200D.py
```
## Windows 10 IoT Core
 
To download Windows 10 IoT Core, visit Get Started page
 
https://developer.microsoft.com/en-us/windows/iot/GetStarted
 
Download (or git pull) the sample, make a copy on your disk and open the project from Visual Studio.

Note: Your IoT Core device and development PC should be connected to same local Network.
#####The code output is the raw values of angular acceleration in X, Y and Z axis.
