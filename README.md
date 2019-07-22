Version AG7GN_20190714A_Anytone868-GENERIC  
# DMR Code Plug for Anytone D-868UV  
This code plug was configured using Anytone DV868UVE Code Plug Software (CPS) version 1.34 and is intended for 868 radios.  It will also work with Anytone DV868UVE CPS version 1.35.
 
It can also be used on Anytone 878 radios, but be advised that 878 code plugs generally will not work on 868 radios.

The latest CPS is called __D868UVE_1.35.exe__. The latest firmware updater software is called __QXCodePro_Update_dpinst_1.02.exe__.  You probably already have the latest firmware updater software installed - it hasn't been updated for quite some time.

The latest CPS and firmware for the 868 radio can be found at [BridgeComm Systems](https://www.bridgecomsystems.com/pages/anytone-at-d868uv-support-page) and the websites of other sellers of this radio. 
Download the ZIP file and then unzip it to view all the files.  
The ZIP file you'll download contains the CPS, the radio firmware, the firmware installer program, and instructions on how to update the firmware. The "CPS-Tool" referred to in the "Firmware updating.pdf" file is the __QXCodePro_Update_dpinst_1.02.exe__ application.  There's also a video at that website that shows how to update the firmware.  

__ATTENTION 868 Owners:__  If you want to have a dark screen background like the cool kids with 878s, download and install firmware version 2.34 or later.  Firmware version 2.35 adds storage for another 40,000 digital contacts, bringing the total number of digital contacts to 200,000.

## Changes since last Code Plug version:
1) Updated Talk Group (TG) lineup for Ferndale UHF repeater to include new full time Brandmeister talk groups WASH EMCOMM and WASH TAC.  I also added some other nationwide and worldwide part time TGs that might be of interest.
2) Updated Digital Contacts list.
3) Fixed Bradmeister Parrot talk group ID 9990 to be PRIVATE CALL.
4) Added PNW Reg 2 (PNWR), WASH 1, WASH EMCOMM and WASH TAC and a few others to BM simplex (Hspot) and BM Duplex (Hspot2) Hotspot zones.

## Code Plug Installation

- Click on the *AG7GN\*.rdt* file above.  
- Click the __Download__ button.  The file will download to your Downloads folder.  
- Run CPS software and load the file from your Downloads folder.  
- *IMPORTANT:*  After loading this codeplug into your CPS software, change the Radio ID to your own DMR ID and callsign
before uploading it to your radio.  Select __Digital > Radio ID List__ in the CPS to change the DMR ID and callsign.
- Connect your radio to your PC with the programming cable.
- Turn on the radio.
- Click __Set > Set COM__ and select the highest numbered COM port listed.  Click __OK__.
- Click __Program > Write To Radio__.  Click __OK__ when asked "Do you wish to contnue?".
- Check both __Digital Contact List__ and __Other Data__ and click __OK__.  Loading the code plug with contacts will take a few minutes.
- Click __OK__ when done, and disconnect the radio from the PC.

Change the boot up screen by selecting Optional Setting and then the Power-on tab, and then change the Power-on
interface setting and Power-on display as desired.

### Button configuration is unchanged.  It is as follows:

   P1 short press: Cycle through digital monitor settings (OFF/Current Time slot/Both Time slots)  
   P1 long press: Toggle scan mode on/off  
   P2 short press: Toggle between main and subchannels  
   P2 long press: Toggle subchannel display on/off  
   PF1 (below PTT switch) short press: Cycle through power settings (Low, Medium, High, Turbo)  
   PF1 long press: Toggle between VFO and memory mode  
   PF2 (below PF1): Analog monitor mode (as long as button is depressed)  
   PF3 (orange/blue\* button) short press: Scan channel lockout (only works in scan mode)  
   PF3 long press: Toggle recorder on/off  

\* Button is orange on the 868 and blue on the 878.  
