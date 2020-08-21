# Autonomous aerial vehicle nanodegree (Udacity) #

This is a master repository, contains all the projects as submodules which I have completed in Sensor Fusion nanodegree 
program.

**Note: If you needed to check all the projects together then only clone the master repository else you can just visit 
the individual submodules and clone that repository for better use.**

## Setup for master repository and submodules ##
1. As always, first step is cloning the master repository. But this repositroy consist of submodules which are 
actually different repositories so to fetch all of them together you need to use little bit different command 
than usual for repository cloning, which will be:

    `git clone --recurse-submodules https://github.com/Ashutosh-Badave/sensor_fusion_nanodegree.git`

2. If you have directly cloned this without submoudle recursion then repository will be cloned with submodule folders 
in it but the submodule folders will be empty.Don't worry now you need to do two more commands to fetch the submodules:
    
    `git submodule init` which will initilize your local configuration file
    
    `git submodule update` to fetch all the data from that project. 

3. Now you will be having all the repositories cloned properly. I have added project specific **_README_** for every 
repository, in which I have provided detailed instructions for easy to setup, test and code structure.

4. All projects are written in C++, and are built using CMake, except for Udacity-Sensor-Fusion-Radar-Target-Gen-and-Detection,
 which requires the use of Matlab.
 

