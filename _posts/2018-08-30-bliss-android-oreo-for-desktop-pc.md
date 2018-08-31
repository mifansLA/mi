---
title: "USB based install ★ Bliss-x86 8.0/10.x ★ 32bit or 64bit"
excerpt: Dokumentasi untuk pemasangan Android OS Oreo untuk Desktop PC atau Laptop. Tidak ada jaminan BlissOS akan berfungsi dengan baik. Dokumentasi dan instruksi dalam Bahasa Inggris
header:
 image: https://i.imgur.com/nzsZTTY.png
 teaser: https://i.imgur.com/nzsZTTY.png
 caption: BlissOS based on Android Oreo for PC
categories:
 - Emulator
 - Resources
tags:
 - Android Oreo
 - Android Emulator
 - Android for PC
locale: en
---
{% include respo.html %}
## BlissOS based on Android Oreo for PC

Ini adalah dokumentasi untuk pemasangan **Android OS Oreo untuk Desktop PC**{: style="color:red"} atau Laptop. Tidak ada jaminan BlissOS akan berfungsi dengan baik. Dokumentasi dan instruksi dalam Bahasa Inggris.

### Part 1 - Gather Your Tools

> ** Please note that Bliss-x86 builds do not currently support this install method for all machines **

For this method, we are going to want to download [Rufus](http://rufus.akeo.ie/downloads/), and the 32bit .iso or 64bit .iso/.img file of [Bliss-x86](#download-blissos). And you are going to need a **decent speed USB drive** (4gb or larger is recommended). Once we have those tools, we can move on. 

### Part 2 - Flashing Bliss-x86 to the USB drive

1. Plug in your USB drive, and load up Rufus. 
2. Once loaded, click on the icon next to the ISO Image dropdown menu.
3. Now browse to where you have your Bliss-x86 (32bit) .ISO, or your Bliss-x86_64 (64bit) .ISO/.IMG file.
4. Once chosen, the dropdown should switch to the correct image type, and fill the rest in for you. Once you are ready, click **Start**.

> or, just do [like this one](https://www.knoacc.org/2013/07/panduan-install-windows-81-dari-usb.html)?

### Part 3 - Testing Bliss on your system

> **!!IMPORTANT STEP!!**
> If you as a user do not test the OS first to make sure it is compatible with your device, please do not expect us to support you if you happen to just install it and something goes wrong. You continued to scroll past all of our warnings about reading and understanding what you are doing, so it's all on you

From here, you can choose to reboot your machine, and make sure it can boot to USB from BIOS. Once that is set, reboot and choose the USB. If everything went smoothly on the install process, you should see a Grub boot screen. Select the **"Live CD"** option, and if your machine is compatible, you should then see a little bit of text, and then the Bliss bootanimation. This will go on for a few minutes, but should eventually boot to Bliss-x86. If the system never boots to Bliss-x86, this is a good sign that your system might not be able to run it. If it does boot, and you would like to install it, continue to the next step.

### Part 3.5 - Using Bliss-x86 from your USB drive

If you so choose to use Bliss from the USB drive, your data will be saved in a temporary state unless you create a data.img to store the data. We can create a data.img in the root dir of the USB drive (make sure you have a minimum 4-5gb free). We suggest using a tool like one from XDA called [RMXtools](http://forum.xda-developers.com/remix/remix-os/rmxtools-remix-os-data-img-t3308158) to create it (we suggest you use version 1.7). 

Check the tool's thread for how to use it, but when you figure it out, you will want to create your data.img inside the root directory of your USB drive, with all the other .img files. From there, just boot into live mode, setup your system the way you want. and the data should be persistant across a reboot now.

### Part 4 - Setting up and Installing Bliss-x86 on your HDD/SSD/SDcard

> Team Bliss is not responsible for any damage, tears, lost time, broken marriages, hallucinations or anything of the sort if things go south with this install. Don't even think about blaming us. You automatically agree to these terms upon continuing the install.

This is where things start to get a little tricky, especially with how PC's vary. Make sure you have a backup plan in case something goes wrong.

Start off by opening your favorite [Partition Management software](https://www.knoacc.org/search/label/Partition%20Manager%20Software), and create a newpartition, making it the size you want (suggested minimum is 8gb.). Just format it to NTFS for now, because it will be changed by the installer later anyways. Remember what drive you setup here, it's important. For Windows machines, it will typically be **Sda4** or **Sda5**. Also create another 300mb FAT32 partition for Grub to install to. _(This part might require a [third-party partition manager](https://www.knoacc.org/2012/11/minitool-partition-wizard-7.html), Windows disk manager won't let it be that small)_

1. Boot up the Bliss-x86 USB, and select the Installation option from Grub. _(second one down)_
2. The installer will load, and you will have an option to choose which partition you created earlier. Pick it, and select Ext4. __You don't want to get this step wrong. If you are unsure, please boot back to Windows, and write it down this time. It will be Sd•• typically__{: style="color: red"}
3. When it asks if you want to install Systemas R/W, select YES.When it asks if you want to install Grub, select Grub for Legacy BIOS boot type, Grub2 for UEFI boot type, or neither if you are already running a Linux system.
4. If you chose to install a Grub option, the installer will allow you to choose. Make sure you select the 300mb partition you setup earlier for Grub.
5. The process will install and create the datadirectory/img, so go get a drink or something and come back to it.
6. When finished, the installer will then ask if you want to run Android-x86, you can just reboot here, and make sure you remove the USB drive.

If we have followed all the directions correctly, you should be presented with a Grub bootmenu. You can choose your _bliss_android_x86_ option (or _android-x86_), and it will boot into Bliss-x86. If you feel the need to customize your grub boot entry, please search the web first. We use the same grub setup that Android-x86 project uses. so their forums will contain just about all the info you will need.

## Download BlissOS
{% include inarticle.html %}

| v10.1 _(beta)_ | v7.2 _(stable)_ |
|:---:|:---:|
| [download .iso](https://downloads.blissroms.com/BlissOS/bleeding_edge/Bliss-v10.1-Beta-android_x86_64-OFFICIAL-20180803-1436_k4.16.8-ipts-blissified-ath_18.1.0-devel_w14_dev-kernel.org.iso){:.btn.btn--primary rel="noopener noreferer"} | [download .iso](https://downloads.blissroms.com/BlissOS/stable/Bliss-v7.2-android_x86_64-OFFICIAL-20171014-1217_k4.9.iso){:.btn.btn--primary rel="noopener noreferer"} |


{% include adsense1.html %}

### Bugs / Issues:

> Only aplied on BETA

- Android Service Has Stopped dialog is back. It does not harm anything though.
- Bluetooth issues still exist on some devices
- you will get Play Store and process crashes until WiFi is connected. Just dismiss these for now. Once connected to WiFi, things should work properly. **ONLY ON OPENGAPPS BUILDS**
- Sound or keyboard might not work, try to boot using the secondary modprobe optionExpect more. It's only a beta release.

> Report your issues, but make sure you SEARCH the thread first to make sure it hasn't been answered. And post logs too (I know, WTF are logs anyways??) on the [AIO thread](https://forum.xda-developers.com/bliss-roms/bliss-roms-discussion/bliss-aio-thread-informations-t3723970){: rel="nofollow noopener"} on XDA Forum.

_source_: [XDADevs forum](https://forum.xda-developers.com/bliss-roms/bliss-roms-development/x86-bliss-x86-pc-s-t3534657){: rel="nofollow noopener"}
