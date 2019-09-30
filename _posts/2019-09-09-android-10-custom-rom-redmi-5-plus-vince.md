---
title: "Potato Open Sauce Project (POSP) 10 For the Redmi 5 Plus"
excerpt: "Custom ROM for Redmi 5 Plus (international) or Redmi Note 5 (India) based on Android 10"
header:
 image: "https://www.xda-developers.com/files/2019/03/POSP-Potato-Open-Sauce-Project.png"
 teaser: "https://i0.wp.com/www.xda-developers.com/files/2019/03/POSP-Potato-Open-Sauce-Project.png?resize=460,320"
 og_image: "https://www.xda-developers.com/files/2019/03/POSP-Potato-Open-Sauce-Project.png"
 caption: "Android 10 for Redmi 5 Plus and more"
categories: [android]
tags: [android 10, custom rom, redmi 5 plus, posp 10]
---
**Android 10-based POSP** is now available for the Xiaomi Redmi Note 5 (India) / Xiaomi Redmi 5 Plus (International). This ROM is marked as an **alpha build**, so we would advise only experienced users try it out at this stage. There are issues with the Goodix-based fingerprint scanner, and issues with the thermal engine — stay away if you expect complete daily driver material.

## ATTENTION

This is an alpha build, no support will be provided for it.

## SCREENSHOOTS

|:---:|:---:|:---:|:---:|
|[![ss 1](https://catetan.istimiwir.host/assets/images/photo_2019-09-06_23-51-00.jpg)](https://catetan.istimiwir.host/assets/images/photo_2019-09-06_23-51-00.jpg)|[![ss 2](https://catetan.istimiwir.host/assets/images/photo_2019-09-06_23-51-13.jpg)](https://catetan.istimiwir.host/assets/images/photo_2019-09-06_23-51-13.jpg)|[![ss 3](https://catetan.istimiwir.host/assets/images/photo_2019-09-06_23-51-17.jpg)](https://catetan.istimiwir.host/assets/images/photo_2019-09-06_23-51-17.jpg)|
|[![ss 3](https://catetan.istimiwir.host/assets/images/photo_2019-09-06_23-51-21.jpg)](https://catetan.istimiwir.host/assets/images/photo_2019-09-06_23-51-21.jpg)|[![ss 4](https://catetan.istimiwir.host/assets/images/photo_2019-09-06_23-51-25.jpg)](https://catetan.istimiwir.host/assets/images/photo_2019-09-06_23-51-25.jpg)|[![ss 6](https://catetan.istimiwir.host/assets/images/photo_2019-09-06_23-51-28.jpg)](https://catetan.istimiwir.host/assets/images/photo_2019-09-06_23-51-28.jpg)|

## DOWNLOADS

|:--:|:---:|
|ROM|[potato_vince-10-20190906.CHIPS-v3.0.0-alpha+1.COMMUNITY.zip](https://sourceforge.net/projects/aperture-builds/files/POSP/10/potato_vince-10-20190906.CHIPS-v3.0.0-alpha%2B1.COMMUNITY.zip/download)|
|Recovery|1. [OrangeFox](https://sourceforge.net/projects/orangefox/files/vince/OrangeFox-R10.0-Stable-vince.zip/download){: rel="nofollow noreferer noopener} 2. [System As Root (SAR) TWRP](https://mi.knoacc.org/dl/drive?id=1yJh0dt980TnXA5689KWn11bdXA8bjO7l&name=SAR_TWRP&size=20.4MB){: rel="nofollow noreferer noopener} |
|GApps|[BiTGApps-Q.zip](https://mi.knoacc.org/dl/drive?id=11oBlR6OhWSdJbYG1MgH9WYL29RkLwUuc&name=Gapps10&size=91MB)|
|Developer|[4PERTURE](https://forum.xda-developers.com/member.php?u=8984156)|
|Thread|[xda forum](https://forum.xda-developers.com/redmi-note-5/development/rom-posp-q-t3965423){: rel="nofollow noreferer noopener} |

## INSTRUCTIONS

1. Flash latest **OrangeFox¹ recovery**, use link provided above or [check the latest](https://sourceforge.net/projects/orangefox/files/vince/) version, at the top of the list.
2. Reboot to recovery
3. Flash ROM you've downloaded
4. Flash **SAR TWRP**² (yes, provided above)
5. Reboot to recovery and
6. Reboot to recovery again (yes, twice)
7. Flash Gapps provided above.

## WORK and what's NOT

|:---:|:---:|
|Working|RIL, WiFi, Camera, Bluetooth, Sensors, Audio, Media, Playback, IR, GPS|
|**Not Working**|Goodix FP, Thermal engine is cucked (device will overheat if used while charging)|
|Untested|VoLTE, Fpc Fingerprint (probably works though)|

> **NOTE:** Do not attempt to flash a custom kernel in this rom, cause they're currently not adapted to Q's filesystem changes. Magisk does not currently work, it is a magisk bug and will hopefully be updated soon. Do NOT flash magisk as it is currently incompatible and will cause Wi-Fi issues and bootloops

## Another phone

**[Android 10](/)** is finally here, and it brings along a lot of goodies that software enthusiasts will appreciate. Officially, stable Android 10 is available on Google Pixel devices, the Essential Phone, and the Xiaomi Redmi K20 Pro, while beta builds can be found for the OnePlus 7 and OnePlus 7 Pro, and Samsung had been spotted testing the update with OneUI 2.0 for the Snapdragon and Exynos Samsung Galaxy S10 and Exynos Samsung Galaxy Note 10.

Source code for the new release is already up and available at AOSP, which brought to us the first Android 10 custom ROM, that too on the ASUS ZenFone Max Pro M1 with practically no bugs.

Now, more Android 10 custom ROMs have begun sprouting up for devices like the Xiaomi POCO F1, the Xiaomi Mi 6, and the Xiaomi Mi 8 beside this [POSP 10 for Redmi 5 Plus (vince)](/android/android-10-custom-rom-redmi-5-plus-vince/).

### Additional notes: LineageOS 16.0

Link to this section at [buildkite](https://buildkite.com/lineageos/android/builds?branch=lineage-16.0) to monitor LineageOS 16.0 Custom ROM.
