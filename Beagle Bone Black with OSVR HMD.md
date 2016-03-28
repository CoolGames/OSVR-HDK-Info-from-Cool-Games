# Using the Beagle Bone Black with the OSVR Head Mounted Display

Objective is to get a 3D application on portable battery powered system.

Beagle Bone Black or Wifi Bluetooth Razer Forge TV should be able to meet this objective.

Interaction is using currently undefined but may be Leap Motion or hand held game controller.
Results require currently available systems but OUYA may be used during the development cycle.

## Tested with Debian containing machinekit 3D printing software distribution

Began by dowloading, zcat and configuring as per instructions at
<http://elinux.org/Beagleboard:BeagleBoneBlack_Debian#BBW.2FBBB_.28All_Revs.29_Machinekit_2>

```
2016-03-20
BBW/BBB (All Revs) Machinekit
microSD/Standalone: (machinekit)

wget https://rcn-ee.com/rootfs/bb.org/testing/2016-03-20/machinekit/bone-debian-7.9-machinekit-armhf-2016-03-20-4gb.img.xz
sha256sum: 31db4813c6df102818be324b308c24ba36533cf29e2b1a3b8fb589eaa7bec544
Jessie Snapshot lxqt
2016-03-20 notes

* U-Boot: v2016.03
* Kernel: 4.1.18-ti-r53

```
## Connect OSVR HMD belt box to BBB HDMI cable

### OSVR HMD did not crash as with Forge TV so next step is to find out what BBB is connected to.

From previous testing to standard HDTV when the display times out then this command 
(code is user displaying the contents ResetHDMI)

```
# cat ResetHDMI 
echo 0 > /sys/class/graphics/fb0/blank

```

After connecting wire to eth0 the first step is to get xRDP setup
and login to the Beagle Bone Black on a high speed connection.

**Power at this point is provided by the OSVR HMD belt box.**

## Use xRDP to login

First check the date in lower right to verify it is getting internet connection.
Next do apt-get update followed by apt-get install synaptic package manager.
Next start synaptic and do upgrades available to machinekit and any others.





This is all I have done but am glad to be making progress.

