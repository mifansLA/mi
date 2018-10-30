---
title: Resources ★ Google Camera HDR+ Fixes ★ Xiaomi Mi A1
excerpt: How to fix issues with installations of thr Google Camera app including crashing or failure to open etc.
header:
 image: https://www-jagatreview-com.cdn.ampproject.org/i/www.jagatreview.com/wp-content/uploads/2015/06/Aplikasi-Kamera-Android-Google-Camera1.png
 teaser: https://i0.wp.com/www.jagatreview.com/wp-content/uploads/2015/06/Aplikasi-Kamera-Android-Google-Camera1.png?resize=350%2C250
 caption: Google Camera HDR+ Fixes
category:
 - resources
tags:
 - google camera
 - fix hdr+ google
 - xiaomi mi a1
 - gcam ported
 - google cam crash
 - can not install hdr+
 - crash on capture
 - crash at opening
---

The [Google Camera HDR+](https://mi.knoacc.org/download-aplikasi-google-camera-cocok-untuk-miui-xiaomi) is a must-have for [Xiaomi Mi A1](https://mi.knoacc.org/lima-alasan-utama-memiliki-xiaomi-mi-a1). With it, the phone’s dual camera works surprisingly well in low light.

But, some users are facing issues with installations of the app. Problems include crashing or failure to open.

> If you dont know what it is, read **Install Google Camera HDR+ on Xiaomi Mi A1** article.

Here, I’ll explain possible fixes. I’ll also list links to working Gcam ports by BSG, Ivanich, and Arnova.

## How to fix Google Camera HDR+ issues

![Google Camera HDR+](https://cdn57.androidauthority.net/wp-content/uploads/2016/04/Google-Camera-interface-Nexus-6P-Android-N.jpg){: .align-center}

### Can’t Install Google Camera HDR+

- The port you are using isn’t compatible with your Mi A1’s Android version. Try another one.
- Remove any previous Google Camera HDR+ installations. It could be the reason the new Gcam isn’t installing.

### Google Camera Crashes on Opening

- New Gcam apk releases may not work on your Mi A1’s Nougat. Try the earlier versions.
- If you’ve upgraded your Gcam, the previous settings may be incompatible with it. So, clear the app data. And then redo the whole installation.
- Some files that may be interfering with your Gcam (see below). Delete them and retry the process. (Needs root access and a file explorer like ES File Explorer.)
```cmd
/System/framework/com.google.android.camera.experimental2016.jar
/System/etc/permission/com.google.android.camera.experimental2016.xml
```
- Activate Camera2 API. (Some ROMs don’t enable it, you know.) There are two ways to do this.
  - By editing the build.prop file to add the line:
`persist.camera.HAL3.enabled=1`
  - By flashing a zip that enables the API. An example is the [HAL3 Enabler](https://www.celsoazevedo.com/files/android/f/HAL3_Enabler.zip). (You can undo the changes using the [HAL1 Enabler zip](https://www.celsoazevedo.com/files/android/f/HAL1_Enabler_by_siankatabg.zip).)
  - Restart your phone to save the changes.

### Google Camera Crashes on Image Capture

Check your Google camera’s HDR+ settings. Remember to apply the suggestions that come with the Gcam apk download.

### Crashes on Activating Slow Motion

Slow motion may not work depending on the ROM your Mi A1 uses.

The `_media_profiles.xml_` file is what contains these settings. So, you’ll have to update it. (Download and use this one that’s already done for you.)

- Save it in the `/root/system/etc/` folder
- Assign the following permissions: `rw-r–r– (0644)`
- Restart your phone

## Google Camera HDR+ Ports

There are ports by BSG, Ivanich, or Arnova. Here’s what you should expect from each of them.

- BSG ° It works as expected (if you use the settings that I’ll share in a second).
- Ivanich ° It’s very stable and doesn’t need lots of tweaking.
- Arnova ° It’s a Gcam 5.1.x port. It doesn’t have the best RAW capabilities, however. Find suggested settings below.

### BSG Settings

**General:**

> Model: Nexus 6P Support level
> override: Nexus_2015 SUPPORTED
> HW LEVEL BACK CAMERA: Limited
> SUPPORTED HW LEVEL FRONT CAMERA: Level_3
> Panorama resolution: High
> Volume key action: Shutter 

**Photo:**

> Config camera: Nexus6 HDR+ Auto
> Buffers size: 3 (Default)
> Total imagereader image count: 14 (AllPixel+AllExp)
> hdr+ burst frame count: 7 (N6P+AllPixel+AllExp)
> Calculation hdr+ imagereader image count: Pixel, PixelXL 

### Arnova Settings

> Model: Pixel 2XL
> Config camera HDR+: Nexus6
> HDR+ Auto Zsl HDR+ parameters: Medium 

### Download Links

| Version | Download |
|:------:|:------:|
| BSG version 4.0 | [MGCB-7.0H-C2API](https://www.celsoazevedo.com/files/android/google-camera/f/MGCB_7.0H_C2API_v.4.0_AllinOne_Full_Manual.apk) (recommended) |
| BSG version 4.0 (v3) | [MGC-4.4.20-7.0H-C2API](https://www.celsoazevedo.com/files/android/google-camera/f/MGC_4.4.20_7.0H_C2API_v.4.0_AllinOne_Full_Manual.apk) |
| Ivanich version 1.4 (v3) | [MGCB-7.0H-C2API-Full-PXL2-v.1.4-60FPS-noburst](https://www.celsoazevedo.com/files/android/google-camera/f/MGCB_7.0H_C2API_Full_PXL2_v.1.4_60FPS_noburst_v3.apk) (recommended) |
| Ivanich version 3.7 | [MGCB-7.0H-C2API-Mid](https://www.celsoazevedo.com/files/android/google-camera/f/MGCB_7.0H_C2API_Mid_v.3.7_AllinOne_Full_Manual_60fps.apk) (latest port) |
| Arnova version 5.1.014 (v11.1) | [GCam5.1.014-Arnova8G2-v11.1](https://www.celsoazevedo.com/files/android/google-camera/f/GCam5.1.014-Arnova8G2-v11.1-N.apk) (recomended) |
| Arnova version 5.1.0114 (v8.1) |  [GCam5.1.014-Arnova8G2-v8.1](https://www.celsoazevedo.com/files/android/google-camera/f/GCam5.1.014-Arnova8G2-v8.1.apk) |
