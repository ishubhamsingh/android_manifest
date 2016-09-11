Cosmic-OS Source
=========================

Getting Started
---------------

To get started with the Cosmic-OS sources, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/version-control.html).


Initialize the Repositories
---------------------------

    repo init -u https://github.com/Cosmic-OS/android_manifest.git -b COS-7.0 && repo sync

This will initialize the new repository and begin the initial sync.  This will take a while!


Building the System
---------------

Initialize the environment with the envsetup.sh script. 
Note: Replacing "source" with a single dot saves a few characters, and the short form is more commonly used in documentation.

    . build/envsetup.sh
    brunch <device>

Credits
---------------
Team Oct-OS for the base..

AOSIP 

Pure Nexus Project

CyanogenMod for Hals..
