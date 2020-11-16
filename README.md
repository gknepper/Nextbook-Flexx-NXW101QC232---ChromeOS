# Nextbook-Flexx-NXW101QC232---ChromeOS
My notes about installing Chrome OS on Nextbook Flexx NXW101QC232 

##### Based on: 
* https://github.com/burzumishi/linux-baytrail-flexx10
* https://github.com/shrikant2002/ChromeOS/
* https://www.youtube.com/user/kedar123456889
* https://github.com/sebanc/brunch

##### Fixit documentation:
* https://www.ifixit.com/Device/Nextbook_Flexx_10

# THIS PROCEDURE WILL ERASE WINDOWS COMPLETELLY FROM THE TABLET - MAKE YOUR BACKUPS !!! 
# I DON'T RECOMENT THIS PROCESS. THIS IS JUST MY NOTES AND WORKED FOR ME. IF SOMETHING GOES WRONG, DON'T BLAME!

## Setup on BIOS/UEFI

* Press Volume + and - and Turn on the tablet.

## Create a Installing USB boot drive: 

**8GB minimum:** For some unknown reason, some thumb drive don't boot. If this happen, just try another one.  

1. Format the thumbdrive as Fat32
2. Download Zorin linux or whatever debian based linux.
3. Mount the linux ISO and copy all files to the thumbdrive.
4. Download UEFI 32 bit file:  **bootia32.efi** to **/efi/boot/** inside the thumbdrive.
5. Create a **ChromeOS** directory inside the thumbdrive.
6. Download the **install.sh** to **/ChromeOS** inside the thumbdrive.
7. Download the file **brunch_r86_k4.19_stable_XXXXXXXX.tar.gz** from **https://github.com/sebanc/brunch/releases** 
8. Extract all files from **brunch_r86_k4.19_stable_XXXXXXXX.tar.gz** to **/ChromeOS** inside the thumbdrive.
9. Download the Recovery file **rammus** from https://cros-updates-serving.appspot.com/ and **extract the content**
10 Rename  **** to **rammus_recovery.bin**






## Download Chrome OS:

* https://cros-updates-serving.appspot.com

## Boot on USB Thumb drive:

* Press Volume + and - and Turn on the tablet

## Status

| Feature                     | Status | Notes |
|-----------------------------|--------|-------|
|Screen backlight control     | **OK** | | 
|Light sensor                 | ToDo    | |
|External Screen (HDMI)       | **OK** | | 
|Built-in (Touchpad)          | **OK** | | 
|Built-in (Touchscreen)       | **OK** | Pinch works too | 
|Bluetooth                    | **OK** | | 
|Keyboard's Hotkeys           | **OK** | | 
|Wireless/Wifi                | **OK** | Sometimes doesn't work, Need a reboot or Sleep and Wakeup | 
|Sound                        | **Partial** | Internal speakers works, Internal mic don't - ToDo: Test earphone connection | 
|MicroSD card reader          | ToDo | | 
|Built-in front camera        | No | | 
|Built-in rear camera         | No | | 
|Accelerometers               | ToDo | | 
|USB OTG                      | ToDo | | 
|USB on keyboard              | **OK**| |
|Tablet keys - (Power) (Vol+) (Vol-) (Super Win)  | **OK** | Super Win key maped manually on settings to work as search | 

## Chrome OS Features:
| Feature                     | Status | Notes |
|-----------------------------|--------|-------|
|Sync                         | **OK** | | 
|Linux crostini               | **OK** | | 
|Google Play                  | **OK** | | 
|Android Apps                 | **OK** | | 
|3D Acceleration              | ToDo   | | 
