---
title: "Redmi Note 4 SD ★ Complete Guide ★ Unlock BL, TWRP, Root, Custom ROM, Xposed and More"
excerpt: "Redmi Note 4 SD ★ Complete Guide ★ Unlock Bootloader, Install TWRP, How to Root, Instaling Custom ROM, Xposed and More"
author: haidar
header:
 overlay_image: https://www.gadgetsinnepal.com.np/wp-content/uploads/2017/05/redmi-note-4-sd-price-in-nepal-00012142.jpg
 caption: "image credit: gadgetsinnepal.com.np"
category:
 - howto
 - tutorial
tags:
 - how to root
 - complete guide
 - redmi note 4 sd
 - install custom rom
 - install xposed
 - install twrp
---

Hello Redmi Note 4(SD) Users,
I am glad to see you all my another tech class. Today, I want to share guide for new users (you) about unlocking bootloader, Custom Rom flashing, flash recovery, Root and more .

_Note_: BL unlock, Rooting, flashing custom rom will void your phone warranty.This all below methods are only tested Redmi Note 4(SD) Variant, **don’t try it on any other model**. Please do some research if you have any concerns about flashing ROMs or any other doubts! Follow the steps correctly otherwise you may brick your device. We are **not responsible** for any damage of your phone.It will erase all your personal data including data of internal storage, so we advise you first to take a complete backup of your phone and then proceed. Ensure that your phone has **at least 50-60% charged** to prevent the accidental shutdown in-between the process.

**But you can always get warranty back by flashing stock MIUI ROM**

{% include toc %}

### Part 1 - How to request for unlocking bootloader?
Here the easiest step to requesting unlock bootloader permission:

_Step 1_: Open up your web browser in your computer then go to [this url](http://en.miui.com/unlock/)

_Step 2_: You’ll see the official page of “Unlock Your Mi Device”. Now simply click on the blue “Unlock Now” Button in the middle of the page.

_Step 3_: You’ll see a login page in the next page which is in Chinese. If you use Google Chrome to open the page, then you can simply use its built-in Google Translate feature.

_Step 4_: Once logged in, you’ll see the Unlock Application Permissions page which is similar to this.

_Step 5_: Now simply fill in all required fields then click on that green Apply Immediately button. p.s: Type in your reason to unlock your device in English (or chinese language).

“My phone is bricked in boot loop mode. Please approve my unlocking request.” or any reason like "i would like to try public beta ROM release."

_Step 6_: In the next page, you’ll need to enter a verification code sent to you via SMS. Check your phone for any SMS verification sent by Xiaomi server. The code is usually valid for only 5 minutes so you need to enter it immediately.

_Step 7_: Once you have submitted the 6 digits code, you’ll then be redirected to another page saying that from the point toward all you need to do is just waiting for Xiaomi Developers to review and approve your application. Once approved, you’ll get another SMS which normally arrives between 3 to 21 days. The approval process is manual so just be patient on this. But in my case **it took only less than one hour** for approval.

> Note : In case your application is rejected, you can reapply again later [here](http://miui.com/unlock/apply.php?retry=1).

### Part 2 -  How to Unlock bootloader?
After you have the Unlock BL permission, here are steps for unlocking bootloader:

_Step 1_: On your device, please login to your Mi account.

_Step 2_: Download [Mi Unlock app](/download-miflash-unlock-tool-2380310) and extract to desktop on PC.

> file name: *miflash_unlock-en-2.2.624.14.zip* (25.8 MB)

_Step 3_: Put / reboot your device into bootloader mode. To do that, simply turn off your device, press the Power button and Volume down ( – ) button at the same time for about 5 second or more until fastboot logo appeared on your screen.

_Step 4_: On your computer, open MiFlash Unlock tool you’ve just installed. Click on the Agree button when asked.

_Step 5_: Login to MiFlash Unlock tool **with the same Mi Account**.

_Step 6_: Now connect your phone to computer using its USB cable.

_Step 7_: Once your phone is connected, the Unlock button **will become active**. Next, simply click on the **Unlock** button to start the process. The unlock process will take about 10 – 15 seconds to complete. That’s all. After unlocking your phone’s bootloader, you’ll be able to flash Fastboot ROM or custom ROM. Enjoy.

> Troubleshoot: If stuck at 50% or could not verify your mi account please try again and again.
> Note: please ensure you got sms from approval permission from xiaomi, and when you got approval sms, you need to wait 5 to 7 days (until then, please don't try).

For more information about unlocking bootloader <del>click here</del>

### Part 3 - How to backup/restore your data?
The most important part is made a back-up. Now, read guide below to make a back-up and ho to restore it later.

_**Backup stage**_

_Step 1_: Open **Settings** >> **Aditional settings** >> **Backup & Reset** >> **Local backups** and Click Backup tap (not lock symbol)

_Step 2_: Select the items that your want to backup, the you can click **back up** >> click **finish** when it says: 100% complete.

_Step 3_: MIUI system will create a [Date_Time] folder in the MIUI\backup\AllBackup\ directory to save all the backup files.

_Step 4_: Connect your phone to your computer, and then transfer the [Date-Time] folder to your computer.

> Note: Backup function doesn’t backup photos, music and other downloaded files on your phone storage. You need to **transfer manually** to your computer.

_**Restore stage**_

_Step 1_: Connect your phone to your computer, and then copy the [Date-Time] backup folder to the MIUI\backup\AllBackup\ directory on either the phone **or** SD card storage.

_Step 2_: Go to your phone’s **Settings**, tap **Additional settings** > **Backup & reset** > **Local backups**. Here, you should see the backup file that you’ve just copied over from your computer.

_Step 3_: Tap to restore your settings and data.

_Step 4_: Restart your phone and enjoy.

Note: this restore step only work if you using MIUI ROM and not aplicable on other custom ROM, eg: AOSP and/or LineageOS.

### Part 4 - How to flash fastboot rom?

> Note: This method is only applicable for devices with an unlocked bootloader.

_Step 1_: Download Fastboot ROM for your device here.

_Step 2_: Download and install Mi Flash Tool on your PC.

**How to download and install miui flash beta tool?** [read this]()

_Step 3_: Put / reboot your device into bootloader mode. To do that, simply turn off your device, press the Power button and Volume down ( – ) button at the same time.

_Step 4_: Now go the downloaded ROM folder and **decompress** it. Copy the complete path of the ROM.

See example picture:
![fastboot rom files]()

_Step 5_: Run the **Mi Flash Tool**. Paste the copied path in the address bar. Now press the **Refresh** button and your device will be recognized automatically. When your device is detected now select **clean all** then click second button **Flash**.

See example picture:
![flashing clean all]()

_Step 6_: Your flashing process will begin. Wait until the whole bar turns into **fully green** abd say **Success**. Now you have successfully installed **[MIUI fastboot ROM](/categories/#fastboot)** on your device. Once the success message comes, phone will reboot automatically and will start booting. Have some patience. It will be up and running in no more than 10 mins.

See example picture:
![flashing complete]()

> Important! Don't turn off your device during flashing process.

### Part 5 - How to flash custom recovery (TWRP)?

> Note - You need to Unlock Bootloader of Redmi Note 4(SD). Please follow Part 1 and Part 2 for How to unlock bootloader of Redmi Note 4(SD).

Be carefull when doing these steps.

_Step 1_: Download [TWRP Installer for Redmi Note 4(SD)]() and extract to your PC.

> file name: TWRP Instaler for RMN 4-mido.zip (17.76 MB) 

_Step 2_: Put / reboot your device into bootloader mode. To do that, simply turn off your device, press the Power button and Volume down ( – ) button at the same time.

_Step 3_: Run **twrp-installer.bat** as an administrator. And press any key in your keyboard to continue the process

_Step 4_: After flashing press any key - Your phone will automatically boot into recovery mode.

_Step 5_: Device will be booted to twrp recovery. Flash [lazyflasher zip]() file and reboot

> file name: lazyflasher-no-verity-opt-encrypt.zip (420.95 KB)

### Part 6 - How to Root your Phone?

Need to root your Redmi Note 4 SD? Follow these steo by step:

_Step 1_: You need to Unlock Bootloader of Redmi Note 4(SD).

> Please follow Part 1 and Part 2 for How to unlock bootloader of Redmi Note 4(SD).

_Step 2_: Download SuperSu from [here]() and transfer into your phone’s internal storage.

> file name: SR3-SuperSU-v2.79-SR3-20170114223742.zip (5.62 MB)

_Step 3_: Now Boot your Redmi Note 4(SD) in to TWRP Recovery mode. After Booting In TWRP recovery mode you will see Many options. For now, choose **Install** button.

_Step 4_: As soon as you choose Install, you will be asked to select the File. Now choose the _rooting package_ (superSU zip) you have downloaded earlier and move it to internal storage.

_Step 5_: After the successful rooting you will receive a Successful message written on the Top. chose **Reboot** then **system**

### Part 7 - How to flash custom ROM like LineageOS, RR, Mokee and others?

Many of us stuck on "un-upgrade-able OS" if MIUI. I mean, even we get MIUI upgrade version, we don't get Android version upgraded. So it may make you bored and decided to changing ROM to custim one.

_Step 1_: First of all, You need to Unlock Bootloader ofRedmi Note 4(SD). Please follow Part 1 and Part 2 for How to unlock bootloader of Redmi Note 4(SD).

_Step 2_: You need to install custom recovery (TWRP Recovery) Please follow Part 4 for How to flash custom recovery(TWRP) on Redmi Note 4(SD).

_Step 3_: Then download and Copy the Custom ROM ZIP to your device.

For you here the most Custom ROM Redmi Note 4 SD users install:

- Resurrection Remix, [Click](/tags/#Ressurection-Remix) Here to download.
- Mokee, Click [Here](/tags/#Mokee) to download

_Step 4_: Boot into Recovery. Make sure to have a Custom recovery like TWRP.

_Step 5_: Take a backup using a synchronization application like Mi Cloud or Manual backup (Part 3) or if you have TWRP installed then you can **take a NANDROID backup** using the TWRP itself.

_Step 6_: Wipe data, factory reset, Cache partition, Dalvik Cache and **Format the System partition**.

_Step 7_: Select **Instal** button and choose downloade-copied ROM ZIP from your device.

_Step 8_: Reboot and Enjoy the Custom ROM on your Redmi Note 4(SD).

> Note - Reboot will take 3-10 mins based on custom rom builds


### Part 8 - How to flash from custom rom back to MIUI rom?


_Step 1_: You need to Unlock Bootloader ofRedmi Note 4(SD). Please follow Part 1 and Part 2 for How to unlock bootloader of Redmi Note 4(SD). **I'm sure you've been did it before** so skip this step.

_Step 2_: You need to install custom recovery(TWRP Recovery). Please follow  Part 4 for How to flash custom recovery(TWRP) on Redmi Note 4(SD).

_Step 3_: Download MIUI ROM and move it into internal memory.

_Step 4_: Go to Recovery Mode.

_Step 5_: Select Wipe, Factory Reset it (Wipes data, dalvik and cache)

_Step 6_: Select Install and flash the MIUI ROM.zip file from SD card. Reboot.

> Note: After rebooting Mi stock recovery will replaces TWRP recovery.

### Part 9 - How to flash TWRP Recovery back to Mi Stock Recovery?

_Step 1_: Download [Mi Stock Recovery]() and move it into SD card.

> file name: recovery.img (22.56 MB)

_Step 2_: Power off your phone. Turn on your phone and hold on Power button + Volume Up button and Recovery Mode.

_Step 3_: Select **Install** (need to Instal image) and flash the Mi recovery img file from SD card. Reboot.

_Step 4_: Successfully flashed Mi Stock recovery in your phone.

### Part 10 - MIUI Official ROMs

> 1. For Developer fastboot roms and stable roms [click here]()
> 2. For Developer recovery roms and stable roms [click here]()


### Part 11 - Install Google Play Store in MIUI Rom

_Step 1_: Open up the Settings icon. Go to **Additional settings** >> **Privacy** >> tick to activate **Unknown Sources**.

_Step 2_: Download and install [Google Installer]() app from here.

> file name: Google Installer_2.0.apk (165.53 KB)

You can also install it from Mi Store App. Open **Mi Store** app  >  type _Google Play_  > install *谷歌安装器_3.0* app.

_Step 3_: Go back to the front page of your phone. Look for and tap on the **Google Installer** or **谷歌安装器_3.0** icon to launch it.

_Step 4_: Once launched, tap on the blue (**Install**) button then wait till the process reached 100%. The process will install *Google Services Framework*, *Account Manager*, *Play service*, *Calendar synchronization*, and *Contact synchronization service*. Just tap in **Install** then **OK** when asked.

_Step 5_: Finally, restart your phone to make sure all Google Services will load completely. One your phone has restarted, try launching up Google Play for the very first time by tapping on its icon.

### Part 12 - Install Xposed Framework

_Step 1_: You need to Unlock Bootloader ofRedmi Note 4(SD). Please follow Part 1 and Part 2 for How to unlock bootloader of Redmi Note 4(SD).

_Step 2_: You need to Root your Redmi Note 4(SD). Please follow Part 6 for How to rootRedmi Note 4(SD).

_Step 3_: You can follow guide below with Video procedure.

How To Install Xposed On Redmi Note 4 Snapdragon

> Disclaimer: We didn't created this ROMs and tools, i am just sharing this ROM and tools itself without making any modifications and source link is provided below. If anybody wants more info then he/she can visit the source here. Thank You.
> Credits to: Xposed: SolarWarez, Root: ChainfireXDA, Recovery: TWRP team, ROM: AOSP
