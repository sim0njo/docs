---
description: Downloads
---

Here you find the recent downloads of my projects.

##ESP32
!!! warning 
    Users of v5.x.y should upgrade to at least v5.02.02 as this will solve a major bug of the web interface. 
    Users of v4.x.y.z are also advised to upgrade to the latest v5 but require to do this via 'ESP Web Installer'.

- [Phc2Mqtt v5.03.05 for ESP32 WROVER 4Mb/8Mb (partition v3)](https://sim0njo.github.io/install/e32Phc2Mqtt4Mb/e32P2M-4Mb-pV3-v5.03.05.bin)  
   Several Home Assistant MQTT Discovery improvements:  
   &nbsp; - entity_id's are now prefixed with <device-name> (ref Configure Device) allowing multiple P2M's connecting to the same HA  
   &nbsp; - shutter control now shows shutter as stopped or moving up/down  
   &nbsp; - removed HA Discovery Mode, now we always use 'Device' model  
   &nbsp;
   Updated CLI in Webconsole, press ? for more details  
   
- [Phc2Mqtt v5.02.08 for ESP32 WROVER 4Mb/8Mb (partition v3)](https://sim0njo.github.io/install/e32Phc2Mqtt4Mb/e32P2M-4Mb-pV3-v5.02.08.bin)  
   Add support for upcoming Home Assistant Core 2026.4
   
- [Phc2Mqtt v5.02.06 for ESP32 WROVER 4Mb/8Mb (partition v3)](https://sim0njo.github.io/install/e32Phc2Mqtt4Mb/e32P2M-4Mb-pV3-v5.02.06.bin)  
   Smaller updates for Home Assistant MQTT Discovery feature  
   
- [Phc2Mqtt v5.02.02 for ESP32 WROVER 4Mb/8Mb (partition v3)](https://sim0njo.github.io/install/e32Phc2Mqtt4Mb/e32P2M-4Mb-pV3-v5.02.02.bin)  
   Changed ESP32 Devkitc to Lilygo T-Eth Lite with support for Wifi and Ethernet  
   Changed Webconsole commands, press '?' to get list  
   Major update to Home Assistant MQTT Discovery feature  
   Fixed major bug of the Web interface
   
- [Phc2Mqtt v4.2.2.7 for ESP32 WROVER 4Mb/8Mb (partition v3)](https://sim0njo.github.io/install/e32Phc2Mqtt4Mb/e32P2M-4Mb-pV3-v4.2.2.7.bin)
   Introduced ActiveSTMv3 mode  
   Changed commands:
```
wait.<1-65535ms> -> stm.wait.<1-65535ms>  
```
   Added commands:  
```
stmd.state
stmd.mods
stmd.evts
```

##Windows

##Linux


