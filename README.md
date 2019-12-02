# Instructions for using an Anytone 878 code plug on your 868 Radio and still retain your personal settings ("Optional Setting" in the CPS)

Version 20191202

## Background

I'm no longer maintaining an Anytone 868 code plug.  Bryce, N7BTS, and others are maintaining a [code plug for the Anytone 878](https://github.com/KI7UIN/DMR) for Whatcom County DMR users.  Read on if you'd like to use that code plug on your 868.

As of this writing, code plugs made for the Anytone 878 DMR radio will work on the 868 radio provided the 878 code plug file is in __Data Conversion File (DCF)__ format.  Anytone 878 code plug files in the __Data File (RDT)__ will not load into the 868 Code Plug Software (CPS).  Fortunately, the maintainers of a popular 878 code plug for Whatcom County save their code plug in both DCF and RDT formats.

The following instructions are for 868 users who want to use the an 878 code plug DCF file in their 868 radios, and still retain their personal settings.

## Install the Latest Firmware on your Radio and Code Plug Software (CPS) on your PC

Several web sites have instructions for doing this.  For example:

[Bridgecom Systems](https://www.bridgecomsystems.com/pages/anytone-at-d868uv-support-page) 

[Connect Systems](http://www.connectsystems.com/software/top/D868UV.htm)
## Backup your Current Code Plug

1) Connect your radio to your PC with the programming cable.
1) Run the 868 Code Plug Software (CPS)
1) Transfer your radio's programmed data to your PC.

	- Set the COM port as needed
	- Click __Program > Read From Radio__
	- Click __OK__ in the "Read Data Completed." window
1) If your radio's personal settings (called "Optional Setting" in the CPS) are to your liking, save this code plug to your PC.  Otherwise, modify your personal settings ("Optional Setting") and then save.

	- Click __File > Save__
	- Set File Type to "Data File (*.rdt)"
	- Specify the location and name the file, then click __Save__
	- Click __OK__ in the "Save File OK" window
	
## Download the 878 DCF File

1) Open a web browser and go to [N7BTS' GitHub DMR page](https://github.com/KI7UIN/DMR) and download the most recent __DCF__ file.  __*DO NOT*__ download the __RDT__ file!

	- Click the newest __*.dcf__ file name
	- Click the __Download__ button
	- Follow your browser's prompts to save the file.

## Load the 878 DCF File into your 868 CPS

1) Start your 868 CPS if it's not already running

	- Click __File > Open__
	- Select __Data Conversion File (*.dcf)__ as the __File Type__ in the lower right corner
	- Go to where you downloaded the 878 DCF file in the previous step and select the DCF file
	- Click __Open__
	- Click __OK__ in the the "Load File OK" window
	
1) Change the DMR ID and Call Sign

	- In the left pane, click __Digital > Radio ID List__
	- In the right pane, double-click the Radio ID to edit it
	- Replace the Radio ID with your own DMR ID and change the Call Sign to your own
	- Click __OK__

1) Export the Data to a List (LST Archive)

	This step will export all of the code plug data EXCEPT for your personal settings ("Optional Setting")

	- Click __Tool > Export__
	- Click the __Export All (Default CSV File Name)__ button at the top of the window
	- Give your export a name.  The CPS will append ".LST" to the name you provide.
	- Click __Save__
	- Click __Yes__ in the "Export &All(Default CSV File Name)" window.  This will take a minute or so to complete.  A window saying "Export Complete!" will pop up indicating the export is finished.
	- Click __OK__
	
## Re-load your 868 Code Plug
1) Locate the file you saved from the "Backup your Current Code Plug" step previously.

	- Click __File > Open__.  You can click __No__ if it prompts you with a "File has been modify, save it now?" window since you've alread exported the data you need as an LST.
	- Change the File Type in the lower right corner to "Data File (*.rdt)"
	- Select your 868 Code Plug RDT file, click __Open__ to load it.  It will take a few seconds to load.
	- Click __OK__ in the "Load file OK" window.
## Import the 878 Data (LST Archive)
1) This step will import the 878 data, but will retain your 868's personal settings

	- Click __Tool > Import__
	- Click the __Import from File List__ button at the top of the window
	- Locate and select the 878 __.LST__ file you saved earlier.
	- Click __Open__
	- Click __Yes__ in the "Import from File List" window.  This will take a couple of minutes to complete.
	- Click __OK__ in the "Import Complete!" window

## (Optional) Download and Install the Latest Digital Contact List
1) Open a web browser and go to the [Radio ID database dumps web page](https://radioid.net/database/dumps#!)

	- Left-click or right-click (depending on how your browser handles downloads) on the __user.csv__ file to download it
	- Save the file to your PC.  If you already had a __user.csv__ in your Downloads folder, your browser may rename the file.  Note the name it assigns to the file.
1) Using your 868 CPS software, import the Digital Contacts list.

	- Click __Tool > Import__
	- Click __Digital Contact List__ and locate and select the digital contact list file you downloaded in the previous step.
	- Click  __Open__
	- Click __Import__ at the bottom of the window (*NOT* __Import from File List__ at the top of the window!) to import the contacts.  This will take some time.
	- Click __OK__ in the "Import Complete!" window

## Save your New 868 Code Plug
1) Save the file as a Data File (RDT)

	- Click __File > Save As__
	- Name the file and location as desired.
	- Select __Data File (*.rdt)__ as the "Save as type".  The APS will automatically append ".rdt" to the file name.
	- Click __Save__
	- Click __OK__ in the "Save File OK" window

## Write the New Code Plug to your 868
1) Make sure your programming cable is connected between your radio and PC

	- Click __Program > Write To Radio__
	- Click __OK__ in the "Write data to radio.  Do you wish to continue?" window
	- Check both "Digital Contact List" and "Other Data" in the "Read or Write Objects" window
	- Click __OK__.  This will take a couple of minutes or so to complete.
	- Click __OK__ in the "Write Data Completed" window

1) Wait for your radio to restart, then disconnect the programming cable and close your CPS (save your code plug file if prompted to do so).
1) Enjoy your new code plug!


