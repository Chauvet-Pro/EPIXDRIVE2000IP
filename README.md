# EPIXDRIVE2000IP

### Installation Notes:

- You must use the Chauvet PRO Uploader PC software to upload this firmware to the device. This is located on the Chauvet Website. 
- Detailed instructions are in the user manual for the device. However, an important note is that the B file must be uploaded first, then the A file.

[V1.8_02-29-24 – ÉPIX Drive 2000 IP](https://github.com/Chauvet-Pro/EPIXDRIVE2000IP/blob/d58b5a7e51ba959c2350620a41743c8931ec9e64/Firmware/V1.8_02-29-24.zip)
-	Improves Webserver Interface
    * Improved IP Address interface with dedicated page/tab
        + If you change the first IP address, subsequent IP’s will auto update in ascending order.
    * Implemented auto-forwarding when changing IP address away from current address.
- Improves Art-net Art-Poll reply on network
- Improves sACN IGMP subscription on network
    * Now sends multicast subscription every 15 seconds
-	Adds support to change IP addresses via Art-Net (DMX Workshop)
-	Adds firmware version for Port B (previously only showed Port A)
-	Adds dim curve options in menu and webserver
-	Bug fixes
  
[V1.7_01-30-24 – ÉPIX Drive 2000 IP](https://github.com/Chauvet-Pro/EPIXDRIVE2000IP/blob/d58b5a7e51ba959c2350620a41743c8931ec9e64/Firmware/V1_77_01-30-2024_Epix%20Drive%202000%20IP.zip)
-	Adds Web server improvements
  
[V1.6_05-30-23 – ÉPIX Drive 2000 IP](https://github.com/Chauvet-Pro/EPIXDRIVE2000IP/blob/d58b5a7e51ba959c2350620a41743c8931ec9e64/Firmware/Epix%20Drive%202000%20IP_V1.69.zip)
-	Updates error alert and white balance calibration
  
[V1.5_03-02-22 – ÉPIX Drive 2000 IP](https://github.com/Chauvet-Pro/EPIXDRIVE2000IP/blob/d58b5a7e51ba959c2350620a41743c8931ec9e64/Firmware/V1_5_3-2-2022.zip)
-	Fixes minor issues
  
[V1.4_09-25-19 – ÉPIX Drive 2000 IP](https://github.com/Chauvet-Pro/EPIXDRIVE2000IP/blob/d58b5a7e51ba959c2350620a41743c8931ec9e64/Firmware/V1_4_9-25-2019.zip)
-	Adds improvements to fix a universe offset bug on port A that required the user to Auto Address after changing the universe on Port A.
  
[V1.3_03-21-19 – ÉPIX Drive 2000 IP](https://github.com/Chauvet-Pro/EPIXDRIVE2000IP/blob/d58b5a7e51ba959c2350620a41743c8931ec9e64/Firmware/V1_3_3-21-2019.zip)
-	Adds support for forced upload on port B
  
[V1.2_05-15-18 – ÉPIX Drive 2000 IP](https://github.com/Chauvet-Pro/EPIXDRIVE2000IP/blob/d58b5a7e51ba959c2350620a41743c8931ec9e64/Firmware/V1_2_5-15-2018.zip)
-	Adds Auto Program improvement: increased master speed control
  
[V1.1_12-20-17 – ÉPIX Drive 2000 IP](https://github.com/Chauvet-Pro/EPIXDRIVE2000IP/blob/d58b5a7e51ba959c2350620a41743c8931ec9e64/Firmware/V1_1_1_12-20-2017.zip)
-	Release software version
-	Bug fixes
-	Added supports for new Epix subdevices. Support is added for all products released up until May 2018.
-	Improves stability when using Kling-net control protocol.
-	Personality changes: 7 channel mode renamed to "7CH-Drive" to make it clear that this mode controls the entire drive, with all subdevices mimicking one another. The 8-channel mode has been renamed to "8CH- fixture" to make it clear that each subdevice connected will work with 8 independent channels. 
-	Improves the 8CH-fixture mode to increase the maximum speed of the auto programs and to work
