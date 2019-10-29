---
title: All In One Guide for Redmi Note 7 (lavender)
excerpt: "This guide for Redmi Note 7 is explaining how to unlock bootloader, installing twrp, rooting, installing custom rom etc."
categories:
 - tutorial
tags:
 - redmi note 7
 - unlock bootloader
 - install twrp lavender
 - root lavender
---
Hello there! Do you have a Xiaomi Redmi Note 7? Off course, why woulf you read this if you don't. Here are the complete guide for who want to customise their Redmi Note 7. Please remember, this guide is written for **lavender** device.

**Disclaimer:** I'm not responsible if anything happens to your device. If you execute these AiO procedures properly then you shouldn't face any problems.
{:.notice .notice-warning}

_Tips:_ Before you proceed please back up all your important data and make sure that your phone battery is charged >80%!
{:.notice .notice-info}

### A. Prerequisites:

1. Disable driver signature enforcement in Windows
   If your computer doesn’t recognize Xiaomi drivers then please disable driver signature enforcement. How to do this please read [here](http://en.miui.com/thread-237673-1-1.html)
2. Install ADB and Fastboot tools with drivers on Windows
   How to do this please read [here](https://forum.xda-developers.com/showthread.php?t=2588979)
   **Restart your computer**.
3. Enable "OEM unlocking" and "USB debugging" in your device
   a. Enable Developer Options in: Settings/About Phone/MIUI version. Click on MIUI version seven times
   b. Now go to: Settings/Additional Settings/Developer Options and check "OEM unlocking" and "USB debugging"
4. Check if your bootloader is locked
   a. After successful installation of "ADB and Fastboot" enter the fastboot mode by holding together "Volume Down + Power" and connect your device to your computer via USB cable (best would be the original cable).
   b. Go to the folder where you have put the "ADB and Fastboot" and open a command window inside that folder. To do that hold together "Shift + Right Click" on any empty white space inside the folder and then select "Open PowerShell Window Here" or "Open Command Window Here"
   c. Enter the terminal command in command line: `fastboot devices`
      If you don't see your device it means that the drivers weren't installed properly or the device wasn't connected properly. If this happens please reinstall your drivers from Point A. 2. or try these drivers [here](http://xiaomiadvices.com/download-xiaomi-usb-drivers/)
   d. If you see your device then enter the terminal command in command line: `fastboot oem device-info`
      If your bootloader is locked, you'll get the following status (or something similar):
      ```
      (bootloader) Device tampered: false
      (bootloader) Device unlocked: false
      (bootloader) Device critical unlocked: false
      (bootloader) Charger screen enabled: false
      (bootloader) Display panel:
      OKAY [ 0.058s]
      finished. total time: 0.063s
      ```
      If your bootloader is unlocked, you'll get following status (or something similar):

      ```
     (bootloader) Device tampered: false
     (bootloader) Device unlocked: true
     (bootloader) Device critical unlocked: true
     (bootloader) Charger screen enabled: false
     (bootloader) Display panel:
     OKAY [ 0.053s]
     finished. total time: 0.055s
     ```
5. Request Permission from Xiaomi to Unlock the Bootloader
   a. Create a Mi Account: [register](https://global.account.xiaomi.com/pass/register)
   b. Sign to Xiaomi and apply for unlocking: [unlock](https://en.miui.com/unlock/)
6. Connect your Mi Account to your Device
   Go to: Settings/Additional Settings/Developer Options/Mi Unlock status and check "Add account and device"

### B: Unlock the Bootloader

Unlocking the bootloader will erase all your data! So please back up your data before you unlock the bootloader!

1. You must enable "OEM unlocking" and "USB debugging" as per point A. 3.
2. You must connect your Mi Account with your device as per point A. 6.
3. Download Mi Unlock Tool [here](https://en.miui.com/unlock/)
4. Enter the fastboot mode by holding together "Volume Down + Power" and connect your device to your computer via USB cable (best would be the original cable)
5. Start the Mi Unlock Tool
6. Enter your eMail and your password of your Mi Account
7. Connect you device to your computer and start the unlock procedure
8. Follow the unlock tool instructions until the unlock procedure is finished
9. Reboot your device

If you get the message, that the unlocking can be done after 72h or 360h or 720h etc., then you have to wait for that time to pass.

### C: Install the TWRP Recovery

1. Your bootloader must be unlocked
2. The official twrp can be downloaded [here](https://twrp.me/xiaomi/xiaomiredminote7.html). However the official twrp for Redmi Note 7 is not yet available. For the time being please download the latest unofficial "twrp-x.x.x.img" from [here](https://forum.xda-developers.com/redmi-note-7/development/recovery-unofficial-twrp-touch-recovery-t3921637) and put it into a dedicated folder in your computer and rename it to "twrp".
3. Go to the folder where you have put the twrp-file. Now open a command window inside that folder. To do that hold together "Shift + Right click" on any empty white space inside the folder and then select "Open PowerShell Window Here" or "Open Command Window Here"
4. Enter fastboot mode by holding together "Volume Down + Power" and connect your device to your computer
5. Enter the terminal command in command line: `fastboot flash recovery twrp.img``. Attention: Do not restart your device otherwise Xiaomi's original recovery might overwrite the custom recovery twrp!
6. Boot your device into recovery (3 possible methods)
   + by entering terminal command in command line: `fastboot boot twrp.img`, or
   + by holding together "Volume Up + Power" until you see the MI logo, release "Power" button but keep pressing "Volume Up" until you see the recovery, or
   + by holding together "Volume Up + Volume Down + Power" until you see recovery

If you only want to root your smartphone, then please continue to [point D](#d-root-your-smartphone)

If you want to install a custom rom, then please continue to [point E](#e-install-a-custom-rom)

### D. Root Your Smartphone

1. Download latest Magisk from [here](https://forum.xda-developers.com/apps/magisk/official-magisk-v7-universal-systemless-t3473445) and put it into internal memory of your smartphone or into the micro sd-card or into on-the-go memory stick
2. In the main twrp screen please click "Install", search for the Magisk-*zip*-file and flash it
3. Restart your smartphone

### E. Install A Custom Rom

1. Download the desired rom and put it into device's internal memory or into the micro sd-card or into on-the-go memory stick:
   a. Lineage OS
      The official Lineage for Redmi Note 7 is not yet available, but when it becomes available you can download it from [here](https://download.lineageos.org/lavender)
      
      Lineage roms don't have Google Apps integrated in them.
   b. Resurrection Remix
      Please download the official Resurrection Remix for Redmi Note 7 (lavender) from [here](https://get.resurrectionremix.com/?dir=lavender)      
      Resurrection Remix roms don't have Google Apps integrated in them.
   c. ATOM
      Please download the official ATOM for Redmi Note 7 (lavender) from [here](https://sourceforge.net/projects/atom-os-project/files/Ten/lavender/)
      
      ATOM roms usually don't have Google Apps integrated in them but the developer of AOSP Extended for lavender is offering both versions, with and without Google Apps.
   d. Xiaomi.EU
      Download the latest rom (weekly or stable) from [here](https://xiaomi.eu/community/)
      
      Global Xiaomi.EU roms already have Google Apps integrated in them.
2. (in case you want to have root on your device) Download "addonsu-arm64-signed.zip" (for Lineage: https://download.lineageos.org/extras) or (for other Roms) the latest Magisk from [here:](https://forum.xda-developers.com/apps/magisk/official-magisk-v7-universal-systemless-t3473445) and put it into device's internal memory or into the micro sd-card or into on-the-go memory stick.
3. If the rom doesn’t contain Google Apps then download Google Apps ARM64, Mini, Pico, Nano etc. from here www.opengapps.org and put them into device's internal memory or computer or on-the-go memory stick or micro sd-card.
4. Enter recovery mode:
   + by holding together "Volume Up + Power" until you see the MI logo, release "Power" button but keep pressing "Volume Up" until you see the recovery, or
   + by holding together "Volume Up + Volume Down + Power" until you see recovery
5. Wipe: Dalvik / Art Cache; System; Data; Cache; (be careful, don't wipe internal storage!)
6. Go back to main twrp screen and install the Rom, install Google Apps (if the Rom doesn’t contain them), install "addonsu-arm64-signed.zip" (in case of Lineage) or the latest Magisk (in case of other Roms).
7. Reboot. That's it, you are done.

### F. Returning To The Original Xiaomi Rom, MIUI

for those users who would like to return to original Xiaomi rom MIUI, below the flashing instructions and download links for the Fastboot and Recovery roms:

1. Fastboot:
   a. Download latest fastboot rom (*.tgz*-file) from [here](http://en.miui.com/a-234.html)
   b. Flash the rom as per instructions explained in the a.m. link.
2. Recovery:
   a. Download latest recovery rom (*.zip*-file) from [here](http://c.mi.com/oc/miuidownload/detail?device=1700360) and put it into device's internal memory or into the micro sd-card or into on-the-go memory stick
   b. Enter recovery mode:
      + by holding together "Volume Up + Power" until you see the MI logo, release "Power" button but keep pressing "Volume Up" until you see the recovery, or
      + by holding together "Volume Up + Volume Down + Power" until you see recovery
   c. Wipe: Dalvik / Art Cache; System; Data; Cache; (be careful, don't wipe internal storage!)
   d. Go back to main twrp screen and install the rom
   e. Reboot. That's it, you are done.

Good Luck!
