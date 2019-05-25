Version 20190518A_Anytone868-GENERIC  
# DMR Codeplug for Anytone D-868UV  
This codeplug was configured using Anytone DV868UVE Code Plug Software (CPS) version 1.33 and is intended for 868 radios.  

It can also be used on Anytone 878 radios, but be advised that 878 code plugs generally will not work on 868 radios.

Changes since last version:

1) Updated TG lineup for Ferndale UHF repeater to reflect that it's on Brandmeister now instead of the PNW DMR network. 
2) Updated Digital Contacts list.
3) Adjusted TG line-up on zones to match the latest line-ups at pnwdigital.net.
4) Tried to name the zones so that they align to repeater names in the PNW DMR web pages, although they don't seem 
   be named consistently there.  I did the best I could. ;)

IMPORTANT:  After loading this codeplug into your CPS software, change the Radio ID to your own DMR ID and callsign
before uploading it to your radio.  Select __Digital > Radio ID List__ in the CPS to change the DMR ID and callsign.

Change the boot up screen by selecting Optional Setting and then the Power-on tab, and then change the Power-on
interface setting and Power-on display as desired.

Button configuration is unchanged.  It is as follows:

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
