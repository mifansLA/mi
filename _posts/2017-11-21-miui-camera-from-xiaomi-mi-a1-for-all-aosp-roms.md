---
title: "Resources ★ Ported Mi A1 MIUI Camera ★ LOS AOSP ROM"
excerpt: "Download and Install MIUI Camera from Xiaomi Mi A1/ported for Lineage OS and All AOSP based ROMs"
header:
 image: "https://i0.wp.com/i.ytimg.com/vi/o025Si1cIu0/maxresdefault.jpg?resize=720%2C360"
 teaser: "https://i0.wp.com/i.ytimg.com/vi/o025Si1cIu0/maxresdefault.jpg?resize=350%2C200"
 caption: "MIUI Camera Ported to All AOSP LOS ROMs"
category:
 - resources
tags:
 - mi a1 camera
 - stock camera miui
 - flashing miui camera
 - ported xiaomi camera
 - stock mi a1 camera
 - aosp los roms
---
Sebenarnya Camera MIUI yang diambil dari Xiaomi Mi A1 ini sudah lumayan lama wira-wiri di forum XDA, cuman sayang kalau dibiarkan tak di posting di situs mifans Lamongan. Pada awalnya, niat @star2 (XDA) membuat ported camera miui ini untuk Xiaomi Mi 5 yang memakai custom ROM berbasis AOSP sebut saja Lineage OS dan lainnya. Eh, trit @star2 juga [diposting ulang](http://en.miui.com/thread-860484-1-1.html){: rel="nofollow noopener noreferer"} di MIUI forum oleh @Miftahzy (miui forum).

Namun kemudian banyak yang mencoba memasang di device Xiaomi lain yang juga menggunakan ROM AOSP based. Dan banyak yangemberi testimoni berhasil. Termasuk saya yanh memasang di Redmi 3 Prime (ido) menggunakan LOS 14.1 (nougat).

Selang beberapa minggu kudian saat saya mencoba mencari (lagi) dengan kata kunci **ported camera mi a1** di google, ternyata posting dari @star2 hilang dari XDA dan malah muncul thread kamera bawaan miui ini di subforum Redmi 3S disini. Dan agak kaget juga saat perkembangan camera mi a1 porting ini cepat sekali. Bahkan hingga saat artikel ini ditulis, sudah _"mencapai"_ versi 7 (whaaaat?) padahal seingat saya waktu itu belum ada versi-versi 1.x.

Mungkin itu karena ada penjelasan di trit @star2 yang menyebutkan bahwa **semua fitur eksklusif camera mi a1** bisa dipakai jika menambahkan/merubah file `/assets/decvice_features.xml/gemini.xml` sesuai codename ponsel Xiaomi kita.

Tetapi ya gak segampang itu melakukan decompile apk. Jadi ya berterimalasihlah pada @mizdrake7 (XDA) yang mau aktif dan susah-susah membongkar dan me-repack ulang agar bisa dipakai di semua ponsel Xiaomi (atau ber-cipset snapdragon?) yang memakai LOS atau Ressurection Remix. Dan tentu saja semua fitur eksklusif Mi A1 jadi milik kita semua. :p

### Fitur Kamera Mi A1 (port)

Photo Mode Rear

- panorama
- timer
- audio (voice control)
- manual (full manual control, white ballance, focus distance, exposure time, iso
- straighten
- beautify
- group selfies
- scene (scene selection)
- tilt-shift
- square
- hht (hand-held twilight)

Photo Mode Front

- timer
- audio (voice control)
- group selfies
- beautify is auto

Video Mode Rear

- time-lapse (480p, 720p, 1080p, 2160p)
- slow motion (480p, 720p, 1080p @ 120fps hfr)
- video recording (480p, 720p, 1080p, 2160p)
- focus mode (tap or continous autofocus)
- image stabilization (this is crop the resolution, because the stabilization is software method, but if you uncheck, the ois is working)
- shoot photo while recording

#### Daftar Device Yang Support

Hingga saat ini, ponsel yang bisa menggunakan dengan baik kamera mi a1 ini adalah:

- Xiaomi Mi 4c (libra)
- Xiaomi Mi 4s (aqua)
- Xiaomi Mi 5s (capricorn)
- Xiaomi Mi 5s Plus (natrium)
- Xiaomi Redmi 3 (ido)
- Xiaomi Redmi Note 3 Pro (kate)
- Xiaomi Redmi Note 3 Special (kenzo)
- Xiaomi Redmi Note 4X (mido)
- Xiaomi Redmi 4X (santoni)

Dan tidak menutup kemungkinan device kamu (terutama yang ber-chipset snapdragon/qualcomm bisa memakai kamera ini.

### Download Xiaomi Mi 1A MIUI Cam

Listing dari versi awal sampai versi terakhir. Semua saya ambil dari postingan @mandrake7, karena yang asli dari @star2 sudah hilang. Untuk detail perubahan tiap versi bisa langsung ke [trit ini](https://forum.xda-developers.com/xiaomi-redmi-3s/themes/miui-8-camera-port-land-t3671079){: rel="nofollow noopener noreferer"}

| Versi MIUI Camera | Link Unduh |
|:------:|:------:|
| Installer Versi 1 | [Via G-Drive](/dl/drive?id=0B7fIOZZgI8cVeG40THRPeEN5UUE&name=miuiCAM.zip&size=v1){:.btn .btn--primary} |
| Installer Versi 2 | [Via G-Drive](/dl/drive?id=0B7fIOZZgI8cVMGhUUkFLU1hIN2M&name=miuiCAM.zip&size=v2){:.btn .btn--primary} |
| Installer Versi 3 | [Via G-Drive](/dl/drive?id=0B7fIOZZgI8cVMWVuZnpFa04tR0U&name=miuiCAM.zip&size=v3){:.btn .btn--primary} |
| Installer Versi 4 | [Via G-Drive](/dl/drive?id=0B7fIOZZgI8cVSG43LXZGS2QwZVk&name=miuiCAM.zip&size=v4){:.btn .btn--primary} |
| Installer Versi 5 | [Via G-Drive](/dl/drive?id=0B7fIOZZgI8cVRElvN3N6b2ZLX2s&name=miuiCAM.zip&size=v5){:.btn .btn--primary} |
| Installer Versi 6 | [Via G-Drive](/dl/drive?id=0B7fIOZZgI8cVYkJBNlBUVmN1elk&name=miuiCAM.zip&size=v6){:.btn .btn--primary} |
| Installer Versi 7 | [Via G-Drive](/dl/drive?id=0B7fIOZZgI8cVZi1tNFJvbW1lUWs&name=miuiCAM.zip&size=v7){:.btn .btn--primary} |

{% include adsense1.html %}

| Un-Imstaller | [Via G-Drive](/dl/drive?id=0B7fIOZZgI8cVMTA4MTRBdnlDb1k&size=un-istaller.zip&name=miuiCAM)

> Untuk Versi 7 [menggunakan porting](https://forum.xda-developers.com/xiaomi-redmi-3s/themes/miui-camera-port-mod-hdr-denoise-t3685529){: rel="nofollow noopener noreferer"} @maxsmeller (XDA).

### Cara Memasang Mi A1 Ported Camera

- REBOOT TO RECOVERY 
- SELECT THE FILE 
- SWIPE TO CONFIRM FLASH 
- WIPE CACHES/DALVIK 
- REBOOT 
- GO TO SETTINGS - APPS - CAMERA AND GIVE ALL PERMISSIONS 
- FOR USERS WHO ALREADY FLASHED V1 DELETE "MiuiCamera" FOLDER FROM "system/priv-app" THEN FLASH V2
- FOR USERS WHO ALREADY FLASHED V2, NORMALLY FLASH V3
- FOR USERS WHO ALREADY FLASHED V3 DELETE "MiuiCamera" FOLDER FROM "system/priv-app" THEN FLASH V4
- FOR USERS WHO ALREADY FLASHED V4 DELETE "MiuiCamera" FOLDER FROM "system/app" THEN FLASH V5
- FOR USERS WHO ALREADY FLASHED V5 DELETE "MiuiCamera" FOLDER FROM "system/app" THEN FLASH V6
-FLASH V7 NORMALLY FROM TWRP AND WIPE CACHES/DALVIK

### Uninstall

- REBOOT TO RECOVERY 
- FLASH UNINSTALLER
- WIPE CACHES/DALVIK
- REBOOT

> Recommended to read: **[Fixes Google Came4a HDR+ on Mi A1](https://mi.knoacc.org/google-camera-hdr-plus-fixes-on-xiaomi-mi-a1)**

-
