# VANET Tutorials
This repository will hold the code used in this VANET YouTube Series (OMNET++, INET, Veins, and SUMO) : https://www.youtube.com/watch?v=tCs-K9AkDrQ&list=PLaBPUIXZ8s4AwAk5EelikvvyG4EzX2hpx&pp=iAQB

## What you need

In order to run this project you need :
* Ubuntu OS version 16.04 LTS
* omnetpp version 5.5.1 
    
* INET (https://github.com/inet-framework/inet) -Latest on master as of 8/25/2020
* Veins (https://github.com/sommer/veins) -Latest on master as of 8/25/2020
* SUMO (http://sumo.sourceforge.net/) - Latest (v1.6.0)
* download VANETTutorials-master from : https://drive.google.com/file/d/1ABEAfqGlJSmycKzsrlk0UJsu9qmMz58Y/view?usp=sharing
## run project
- open new terminal and run:      '/home/user/Documents/veins-master/sumo-launchd.py'  -vv -c /home/user/Downloads/sumo-0.32.0/bin/sumo-gui

 - run omnetpp.ini from simulations/routing/  
## Custom your project configurations
* change mobility map from :
  
-Square.launched.xml

-modify these files : .net.xml, .rou.xml, .sum.cfg (you can use files from script folder)

* change routing mode : Gpsr or Aodv (you can also choose different one from inet/src/routing )
                     
* change number of source and destinations vehicles:
modify simulations/routing/omnetpp.ini for example:

node[2..8].app[0].starttime=205s

node[2..8].app[0].endtime=230s

## Have a question?

Have any questions about OMNET++, INET, Veins, or these tutorials. Join the VANET Tutorials discord server: https://discord.gg/zBmwCYa

## Videos in Series

### Introduction to VANETs

This video will give you a short introduction to VANETs (vehicular ad-hoc networks). You will learn what are VANETs, VANET architecture, potential applications, and research needs. 

You can watch the video here: https://youtu.be/tCs-K9AkDrQ

### Getting Started with OMNET++, INET, Veins, and SUMO

In this video, you will learn how to set up your OMNET++ environment, create your own workspace, and learn how to run INET, VEINs, and SUMO. 

You can watch the video here: https://youtu.be/PfAWhrmoYgM

### How to Create a new OMNET++ Project that references INET and Veins

This video will show you how to create a new OMNET++ project that works with both INET and Veins.

You can watch the video here: https://youtu.be/mGvhbrw05sQ

### An Overview of OMNET++

In this video, we are going to review OMNET++. Specifically, we will learn how OMNET++ works and how .ned files and .ini work together.

You can watch the video here: https://youtu.be/Ez8tTS9iXe4

### How to Make Mobile Hosts Communicate Wirelessly in OMNET++

In this video, we are going to learn how to set up a simulation where the mobile hosts communicate with each other wirelessly. This will be done using INET's standard host in OMNET++. You will learn how to make two hosts communicate with each other wirelessly, use INET's visualizer, and make your host move.

You can watch the video here: https://youtu.be/9xDqjRd1DpA

### How To Create a Network and Simulation in SUMO

In this video, you will learn about SUMO networks, how to create a SUMO network (by hand and using NETGENERATE), and how to create a simulation in SUMO.

You can watch the video here: https://youtu.be/eXW4D32ePpE

### How to Simulate a V2V Network using OMNET++, INET, and Veins

In this video, we are going to learn how to use INET and VEINs together to simulate a V2V network. This video will review the veins_inet subproject and also show you how to use AODV in your simulation. AODV is a manet routing protocol available in INET.

You can watch the video here: https://youtu.be/6GG1rPvfagU

### How to Create a Network and Simulation in SUMO Using OpenStreetMap

In this video, we will learn how to take a map from OpenStreetMap and turn in into a SUMO simulation (which we then can use in our VANET simulations).

You can watch the video here: https://youtu.be/wZycufsTEGU


