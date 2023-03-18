# BTT-TFT35_V3.0.27-CR10Smart_CR6SE
Repository for BTT TFT35 firmware for Embrace Making CR10 Smart and CR-6 SE upgrade in combination with SKR MINI E3 V3. Mainboard upgrade made easy using the Embrace Making Easy Swap PCB kit for these machines. You can find those PCBs here:

* https://embracemaking.com/products/cr10-smart-cr6-se-mainboard-easy-swap-pcb-kit

The 3D printable files to fit the screen to the CR10 Smart can be found here:

* https://www.printables.com/model/422494-cr10-smart-x-skr-mini-e3-v3-mounts-and-btt-tft35-v

The 3D printable files to fit the screen to the CR-6 SE can be found here:

* https://www.printables.com/model/422494-cr10-smart-x-skr-mini-e3-v3-mounts-and-btt-tft35-v

Video showing installation on CR10 Smart:

* https://youtu.be/vo5xYLcvk2w


## **! PLEASE READ !**

These files are from BTT firmware TFT35_V3.0.27 This is release xx.27 from Big Tree Tech. These config and bin files SHOULD ONLY BE USED WITH THE CORRECT MODEL TOUCH SCREEN. PLEASE MAKE SURE YOU ARE USING THE TFT35 V3.0 TOUCH SCREEN. THIS IS NOT THE E3 VERSION AND IT IS NOT THE B1 VERSION!

Firmware update on the screen is very easy.

Step 1: Download these files in this repository and extract them to a folder.
  
Step 2: Navigate to TFT35/bmp/ and look for the .bmp files named "logo.bmp" and "logo2.bmp"  The first is for the CR10 smart. If you are using the CR10 smart, delete the "logo2.bmp" file. If you are using the CR-6 SE, delete the "logo.bmp" file and rename "logo2.bmp" to "logo.bmp" These are the splash screen files and the end result is that you only have one file in this folder named "logo.bmp"
  
Step 3: Get 8GB SD card and format it clean. Copy the files onto the SD card. You should only have 3 items on the card: the TFT35 folder, the .bin file and the .ini file.
  
Step 4: Insert the SD card into the TFT35 module and power it on. Wait 2-3 mins for the firmware update to complete

See my videos here for the entire mainboard and screen upgrade:

![Breakout_Render1](https://user-images.githubusercontent.com/109498075/224583184-0bb8151a-3680-42a4-bcc2-7355593700b0.JPG)

![AUX-BOARD_Render2](https://user-images.githubusercontent.com/109498075/224583201-adb482dd-7fab-422b-b6c1-a3909e319aaf.JPG)
