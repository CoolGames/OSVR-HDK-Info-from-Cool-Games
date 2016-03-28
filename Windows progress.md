##Instructions

Followed link at [Using  OSVR Devices](https://osvrdevportal.atlassian.net/wiki/display/DD/Using+OSVR+Devices)

###Also did Firmware Upgrade.

####OSVR Control log

```
Turing display off
#?v
Version 1.81  Sep 25 2015
Tracker:1.8.4.415
#f1s
Toggle side by side
#?v
Version 1.81  Sep 25 2015
Tracker:1.8.4.415
>#?v
Version 1.85  Dec 16 2015
Tracker:1.8.4.415
#ei
```
###Updated Firmware version - March 28,2016

```
Version 1.91  Mar 11 2016
Tracker:1.8.4.415

```



###Below link states
At 'If you want to directly download the OSVR Services setup, go to` *TBD: need location*.
'''
If you are a developer and you wish to develop with the latest OSVR core, you need to uninstall OSVR Services and then manually download and install the core from the OSVR site.
'''

####I had already installed [OSVR Core / Server](http://osvr.github.io/using/)
Only the HMD was not detected to [install OSVR Services](https://osvrdevportal.atlassian.net/wiki/pages/viewpage.action?pageId=7962786).



```
[OSVR Server] Using default config file - pass a filename on the command line to use a different one.
[OSVR Server] Using config file 'osvr_server_config.json'
[OSVR Server] Constructing server as configured...
[OSVR Server] Loading auto-loadable plugins...
[OSVR Server] Loading plugins...
[OSVR Server]
[OSVR Server] Instantiating configured drivers...
[OSVR] Added device: org_osvr_filter_videoimufusion/HeadFusion
[OSVR] Client context initialized for org.osvr.analysisplugin
[OSVR] Interface initialized for /com_osvr_Multiserver/OSVRHackerDevKitPrediction0/semantic/hmd
[OSVR] Could not resolve source for /com_osvr_Multiserver/OSVRHackerDevKitPrediction0/semantic/hmd
[OSVR] Interface initialized for /com_osvr_VideoBasedHMDTracker/TrackedCamera0_0/semantic/hmd/front
[OSVR] Could not resolve source for /com_osvr_VideoBasedHMDTracker/TrackedCamera0_0/semantic/hmd/front
[OSVR Server] Successes:
[OSVR Server]  - com_osvr_VideoBasedHMDTracker/VideoBasedHMDTracker
[OSVR Server]  - org_osvr_filter_videoimufusion/VideoIMUFusion
[OSVR Server]
[OSVR Server]
[OSVR Server] Aliases found and parsed from config file.
[OSVR Server] Display descriptor found and parsed from config file.
[OSVR Server] RenderManager config found and parsed from the config file.
[OSVR Server] Triggering automatic hardware detection...
[OSVR Server] Registering shutdown handler...
[OSVR Server] Starting server mainloop: OSVR Server is ready to go!
[OSVR] Performing hardware auto-detection.
[OSVR] Added device: com_osvr_Multiserver/OSVRHackerDevKit0
[OSVR] Added device: com_osvr_Multiserver/OSVRHackerDevKitPrediction0
directx_camera_server: Using capture device 'USB Video Device' at path '\\?\usb#vid_0bda&pid_57e8&mi_00#7&314fc184&0&0000#{65e8773d-8f56-11d0-a3b9-00a0c9223196}\global'
Opening camera 0
[OSVR] Added device: com_osvr_VideoBasedHMDTracker/TrackedCamera0_0
Video-based tracker: NOTE: Beacon calibration filename videotrackerCombinedCalibrationFile13.json was specified, but not found or could not be loaded.
[OSVR] Path tree updated or connection detected
[OSVR] Sending path tree to clients.
[OSVR] Got updated path tree, processing
[OSVR] Constructed a TrackerHandler for com_osvr_Multiserver/OSVRHackerDevKitPrediction0@localhost sensor 0
[OSVR] Successfully produced handler for /com_osvr_Multiserver/OSVRHackerDevKitPrediction0/semantic/hmd
[OSVR] Constructed a TrackerHandler for com_osvr_VideoBasedHMDTracker/TrackedCamera0_0@localhost sensor 0
[OSVR] Successfully produced handler for /com_osvr_VideoBasedHMDTracker/TrackedCamera0_0/semantic/hmd/front
[OSVR] Connected 2 of 2 unconnected paths successfully
[OSVR] Performing hardware auto-detection.
[OSVR] Path tree updated or connection detected
[OSVR] Sending path tree to clients.
Video-IMU fusion: Hold still, measuring camera pose..


NOTE: For best results, during tracker/server startup, hold your head/HMD still closer than 0.3 meters from the tracking camera for a few seconds, then rotate slowly in all directions.


Video-IMU fusion: Hold still, measuring camera pose..........


Video-IMU fusion: Camera pose acquired, entering normal run mode!
Camera is located in the room at roughly -0.0146222 -0.0969587   0.527665

```
