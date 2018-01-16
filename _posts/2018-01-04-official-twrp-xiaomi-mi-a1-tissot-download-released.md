---
title: Resources ★ Official TWRP 3.2.1-0 tissot ★ Xiaomi Mi A1
excerpt: Download officially released TWRP for Xiaomi Mi A1 (tissot) and guide how to install permanently
header:
 image: https://i0.wp.com/theandroidpoint.com/roms/wp-content/uploads/2017/11/teamwin.png?resize=700,350
 teaser: https://i0.wp.com/theandroidpoint.com/roms/wp-content/uploads/2017/11/teamwin.png?resize=360,180
categories:
 - resources
tags:
 - twrp recovery
 - xiaomi mi a1
 - how to
 - twrp official
---

Team Win Recovery Project 3.x, or twrp3 for short, is a custom recovery built with ease of use and customization in mind. Its a fully touch driven user interface no more volume rocker or power buttons to mash. The GUI is also fully XML driven and completely theme-able. You can change just about every aspect of the look and feel.

### Changelogs)

**What's new in 3.1.1-0**

- Backups will now include adopted storage keys *(Dees_Troy)*
- Fixed an adb restore issue *(bigbiff)*
- Fixed rebooting when no OS is present *(Dees_Troy)*
- Fixed line wrapping in the GUI terminal *(_that)*
- Updated TWRP source code to AOSP 7.1.2 *(Dees_Troy)*

**What's new in 3.2.1-0**

- minui fixes *(cryptomilk)*
- Better android-8.0 compatibility in ROM trees *(Dees_Troy)*
- Fix missing library in android-8.0 *(nkk71)*
- Fix inconsistent SDCard naming *(DevUt)*
- Default to TWRP restore instead of adb backup restore to fix restore on fresh TWRP boot *(jlask)*

### Whats working in this version?

- All partions are mounting
- Can change Slot A/ Slot B on twrp its self
- Everything as usual.. (Backup/Restore)
- Recovery booting after rebooting to system
- Sdcard working
- USB-OTG working
- Add system_image mount point to flash system images

# Download TWRP for Xiaomi Mi A1

Mi A1 Codename is **Tissot**

| TWRP 3.1.1-0 | TWRP 3.2.1-0 |
|:------:|:------:|
| [Download](/dl/pcloud?code=XZiypp7Z3NmSBO9vBmHjcplAR7L5mydVeDLV&size=30.2MB&name=twrp-3.1.1-0-tissot.img){:.btn.btn-primary} | [Download](/dl/pcloud?code=XZS7pp7Z7SRIX1C4OFH3BFys5PeilLH2isM7&size=30.2MB&name=twrp-3.2.1-0-tissot.img){:.btn.btn-primary} |

TWRP Flasher for Tissot

| 3.1.1-0 | 3.2.1-0 |
|:------:|:------:|
| [Download](/dl/afh?fid=817906626617943385&size=7.7MB&name=twrp-3.1.1-1-installer-tissot.zip){:.btn.btn-primary} | [Download](/dl/afh?fid=817906626617943385&size=7.7MB&name=twrp-3.1.1-1-installer-tissot.zip){:.btn.btn-primary} |

## TWRP installation instructions:

**WARNING: DO NOT FLASH TWRP IMG DIRECTLY FROM FASTBOOT**

Just do as this step by step guide to avoid bricking your Xiaomi Mi A1. Thus I don't take any responsibility from your doing.

- Download required files ())from downloads
- Unlock your bootloader (You must be unrooted)
- ADB Fastboot properly installed.
- Place file `twrp-3.x.x-x-installer.zip` to your Mi A1 internal storage.
- Rename `twrp-3.x.x-x-tissot.img` to `recovery.img` and place it inside **adb-fastboot** instalation folder
- Press Shift button and Right-Click mouse then choose **Open Command prompt**
- Reboot to bootloader by typing `adb reboot bootloader` in command prompt appeared.
- Type `fastboot boot recovery.img` in command prompt to boot into TWRP.
- Flash `twrp-3.x.x-x-installer.zip ` from your phone.
- Choose Reboot to recovery menu and check if TWRP is re-open, if not (100% chances) then you need do:
- Reboot to bootloader (again)
- Type `fastboot set_active b`
- Again, Type `fastboot boot twrp.img`
- Flash `twrp-3.x.x-x-installer.zip` again.
- Now choose reboot to recovery menu

TWRP should re-open, and it means your Mi A1 already installed with TWRP permanently.

_Source:_ [TeamWin](https://eu.dl.twrp.me/tissot/)
[XDA](/)
