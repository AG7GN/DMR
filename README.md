Version AG7GN_20190713C_Anytone868-GENERIC  
# DMR Codeplug for Anytone D-868UV  
This codeplug was configured using Anytone DV868UVE Code Plug Software (CPS) version 1.34 and is intended for 868 radios.
 
It can also be used on Anytone 878 radios, but be advised that 878 code plugs generally will not work on 868 radios.

The latest CPS and firmware for this radio can be found at [BridgeComm Systems](https://www.bridgecomsystems.com/pages/anytone-at-d868uv-support-page) and the websites of other sellers of this radio. 

__ATTENTION 868 Owners:__  If you want to have a dark screen background like the cool kids with 878s, download and install firmware version 2.34.

## Changes since last Code Plug version:
1) Updated Talk Group (TG) lineup for Ferndale UHF repeater to include new full time Brandmeister talk groups WASH EMCOMM and WASH TAC
2) Updated Digital Contacts list.
3) Fixed Bradmeister Parrot talk group ID to use the GROUP CALL ID (31000) rather than the PRIVATE CALL ID (9990).

## Installation

- Click on the *AG7GN\*.rdt* file above.  
- Click the __Download__ button.  The file will download to your Downloads folder.  
- Run CPS software and load the file from your Downloads folder.  

*IMPORTANT:*  After loading this codeplug into your CPS software, change the Radio ID to your own DMR ID and callsign
before uploading it to your radio.  Select __Digital > Radio ID List__ in the CPS to change the DMR ID and callsign.

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
