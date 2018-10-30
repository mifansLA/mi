---
title: "Simple Way to Upgrade to MIUI 9 ★ Complete Guide ★ All Devices"
excerpt: "Simple Way how to Upgrade to MIUI 9 for any Xiaomi Phone with Complete Guide"
author: zena
header:
 overlay_image: https://www.techora.net/wp-content/uploads/2017/07/miui-9-interface.png
 caption: "image credit: techora.net"
category:
 - tutorial
 - how to
tags:
 - how to update
 - simple way
 - xiaomi
 - miui 9
 - global beta
 - update miui
---
Xiaomi is famous for it’s Best Custom ROM MIUI, and recently announced its next version of ROM that is MIUI 9. MIUI 8 is based on Marshmallow, that’s why 9 is most awaited ROM for Xiaomi users. The main highlighted MIUI 9 features are smart search, Quick Switch, Split Screen and many more feature that’s available in Android Nougat. Still, MIUI 9 Stable version isn’t released but MIUI 9 beta ROM is rolling out for some beta tester. So if you also want to Install MIUI 9 Beta ROM on your Xiaomi Device then follow this article.

{% include toc %}

## How to get MIUI 9 Beta ROM Download Links for your Xiaomi Device.

MIUI developer team is still sending Download Links and Update only to selected Xiaomi users. If you want to get download links for your device then you need to apply for it or just search. And when the update gets the release for your device MIUI team will contact you with download links and instructions.

### Apply for MIUI 9 Beta ROM Download Links.

Step 1: Download Xiaomi MIUI forum App on your Xiaomi Device. If you’re already using MIUI forum app then move to the next step. Click on user icon from left upper corner > tap on Sign in and login into your Mi Account.

Step 2: Go back to home page and tap on recruitment option. Now a form page will open Select your device > Select time range to use the smartphone after that fill the reason why you want MIUI 9 ROM and submit.

Now wait for approval and you’ll get forum PM. To increase your chances of getting approval you need be active on the forum and earn forum credit.

** But, if you won't registering yoursel as beta tester, the you can also search MIUI 9 download link from this weblog at download category. 

## Unlock Bootloader to Install MIUI 9 Beta ROM.

If you’re already using Beta ROM then skip this, Because you unlocked your bootloader before. Or if you’re using the Global Stable version of MIUI 8 ROM then first you need to unlock Bootloader.

### Apply For Permission.

Xiaomi doesn’t allow its user to unlock the bootloader, If you want to unlock then you first need to apply for permission to unlock. It takes maximum 3-7 for approval, alternatively, you can post in MIUI forum, use app that you downloaded.

### Install MI Unlock tool and Unlock Bootloader.

Step: 1 After Getting Permission to unlock Bootloader, Download MI unlock tool and sign in using Mi Account.

Step: 2 Fastboot Mode – Shut down your phone > hold Volume down + Power button. After that Connect your phone to PC using USB cable and click “Unlock”. Hold Down power button to Exit from FastBoot Mode.

## Install MIUI 9 Fastboot ROM.

If you got approval for MIUI 9 Beta ROM then Download MIUI 9 ROM for your device. Or you can check direct download link of MIUI 9 Fastboot ROM in this article.

Step: 1 After Downloading ROM File Extract it in your computer using WinRAR Software. Copy the location of MIUI 9 ROM extracted Files.

Step 2: Download Mi Flash Tool and Install it in your Computer. Open the tool and paste the location of MIUI 9 extracted files or you can use Browse option.

Step 3: After that go to Fastboot mode. (Shut Down device and press Volume down + Power Button.) and connect your device using USB

Step 4: On Mi Flash tool press Refresh button, it will detect your device is connected into the fast-boot mode. If you want to delete all your data and clean installation choose clean all option and then Hit the Flash Button.

## Flash MIUI 9 ROM Zip File Using CWM Recovery.

ADB and Fastboot File. (And Extract on your Computer.)
Download Twrp.img File for your device and move it to the ADB and Fastboot Folder. (Rename Twrp File if it’s Different like (TWRP 2.2.0.0 > TWRP), it will easy to give command)

Step 1: Open your phone in the Fastboot Mode (Volume Down+Power Button). Connect to the computer and don’t forget to Install ADB Driver.

Step 2: Open Extracted folder and Press Shift + Right click on Mouse and choose “Open Command Prompt Window FromHere.”

Step 3: Now command prompt window will open, give the following command one by one. (Make sure your bootloader is unlocked, otherwise, it will not boot into TWRP Recovery.)

Command 1: Type or copy the following command and press enter- By using this command you can check your Device is connected into the fastboot mode or not.

fastboot devices

If Command Prompt shows some characters, it means your device is connected. Or if not then check ADB drivers are installed properly or not.

Command 2: To Flash TWRP recovery give the following command and hit enter. (Make sure TWRP recovery image is in the same folder with TWRP name)

fastboot flash recovery twrp.img

Command 3: To temporary boot into Twrp recovery give the following command and TWRP recovery will open.

fastboot boot twrp.img

### Flash ROM. (Move File into Pendrive and connect Using USB OTG.)

After booting into TWRP Recovery go to Install Option > Select MIUI Zip File > and Swipe to Confirm Flash. After completing Flashing ROM Reboot the System, Done you have successfully Installed MIUI 9 ROM.

Next time to boot into TWRP Recovery use Volume Up + Power Button. One more thing after installing TWRP recovery you’ll not able to update your device using OTA update.
