# Smartphone-N-of-1-Predicting-Treatment-Success-with-Autopsy-Data
#  Autopsy Data Collection Guideline

##  Requirements (Software needed):
1.  Autopsy:  [to read and analyze the data from Android and iPhone devices] https://www.autopsy.com/download/
2.  Free ISO Creator:  [to make disk image file] http://www.freeisocreator.com/
3.  DB SQL lite:    [to see data in more detail which save as db file] https://sqlitebrowser.org/dl/ 
4.  HxD Freeware hex editor and disk editor [to see decoded data] https://mh-nexus.de/en/hxd/

##  Data collection process:
1.	Prepare the Device:
Ensure the Android or iPhone device you want to collect data from is fully charged and connected to a computer with a USB cable.
2.	Create Disk Image (Android):
Launch the Free ISO Creator software.
Follow the software's instructions to create a disk image (ISO) of the Android device. This image will preserve the data on the device for analysis.
3.	Extract Data (iPhone):
For iPhone devices, you'll need to add the iPhone data extraction plugin to Autopsy. Use the following GitHub link for the plugin: https://github.com/ernestbies/iOSDeviceDataExtractor
Follow the instructions provided in the plugin's repository to integrate it into your Autopsy installation.
4.	Import Disk Image (Android) and iPhone Data:
Launch Autopsy on your computer.
Create a new case by selecting "New Case" and providing relevant details.
Add the disk image (ISO) created from the Android device and the data extracted from the iPhone device to the case.
5.	Data Analysis and Examination:
Autopsy will process the data and present it in a user-friendly interface.
Use Autopsy's built-in tools to analyze the data from both devices. You can explore call logs, text messages, photos, videos, app usage, internet browsing history, and more.
6.	Viewing Data in DB SQLite (Optional):
If you need more detailed examination of specific data, use DB SQLite to view the data saved as a DB file.
7.	Decoding Data with HxD (Optional):
For further analysis, you can use HxD Freeware Hex Editor and Disk Editor to view and decode specific data.
8.	Data Export (Optional):
If you want to export specific data for further analysis outside of Autopsy, you can use the export features provided by Autopsy or DB SQLite.

