# Getting RPi to work with RoboRIO

First, connect pi to OpenMesh Radio on the open ethernet port. 
Then, go to Advanced IP Scanner on the driver's station. Change the range of IP's at the top bar to `10.45.16.1-10.45.16.254`. Run the scan and find your hostname set previously. I don't know how to connect to the hostname just yet, so find the ip next to the name and use PuTTY to connect. You should be able to use SSH normally on the pi on the driver's station to get it work.  
Check out the [wpilib network docs](https://docs.wpilib.org/en/stable/docs/networking/networking-introduction/index.html?highlight=networking) for more information