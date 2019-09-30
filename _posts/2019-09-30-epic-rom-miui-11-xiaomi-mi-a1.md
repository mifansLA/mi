---
title: "Install dan Download Epic ROM MIUI 11 untuk Xiaomi Mi A1"
excerpt: "Epic ROM untuk Mi A1 kali ini dibangun dari ROM MIUI Eropa (Xiaomi EU) yang dibangun atas dasar MIUI Beta"
header:
 image: https://www.xda-developers.com/files/2019/09/Image-190.jpg
 caption: "MIUI 11 Epic ROM"
categories:
 - ROM
tags:
 - android oreo
 - epic rom
 - miui 11
last_modified_at: 2019-10-01 12:31:04
---
Epic ROM port MIUI 11 merupakan ROM kustomasi, bukan ROM resmi dari Xiaomi. Di komunitas pengguna ponsel Xiaomi sendiri sudah lumayan banyak yang memakai. Punya beberapa fitur yang tidak ada di MIUI 11 versi resmi dan beberapa bloatware juga dihilangkan.

Secara khusus, Epic ROM untuk Mi A1 kali ini dibangun dari ROM MIUI Eropa (Xiaomi EU) yang dibangun atas dasar [MIUI Beta](https://mi.knoacc.org/download-miui-11-beta-semua-tipe) 9.9.26] yang baru dirilis. Bisa jadi pilihan bagi yang tidak sabar menunggu [MIUI 11 Official dirilis](https://mi.knoacc.org/miui-11-fitur-jadwal-rilis-daftar-ponsel-redmi).

<figure class="half">
<a href="/assets/image/FB_IMG_1569864128243.jpg" title="Screenshoot 1"><img src="/assets/image/FB_IMG_1569864128243.jpg" alt="Epic ROM MIUI 11" /></a>
<a href="/assets/image/FB_IMG_1569864134439.jpg" title="Screenshoot 2"><img src="/assets/image/FB_IMG_1569864134439.jpg" alt="Epic ROM MIUI 11" /></a>
<figcaption>Tangkapan layar MIUI 11 Epic ROM</figure>
</figure>

**Perhatikan:** Tutorial ini hanya diperuntukkan bagi yang sudah memahami resiko menggunakan custom rom dan segala akibat yang ditimbulkan jika gagal salam proses instalasi maupun setelah instalasi. Serta mampu membenahi sendiri jika terjadi hal-hal yang tidak diinginkan .
{:.notice .notice--danger}

### Langkah instalasi

Pastikan bootloader sudah **Unlocked** sebelum mempraktekan. Sebaiknya gunakan custom **TWRP CosmicDan**, bisa di unduh [di sini](https://github.com/CosmicDan-Android/android_device_xiaomi_tissot/releases/tag/2.5){:rel="nofollow external noopener"}. Untuk data di internal, sebaiknya pindahkan ke penyimpanan cadangan/eksternal.

Berikut langkahnya secara singkat.

- Back up EFS & Modem terlebih dahulu.
- Full wipe termasuk Internal storage.
- Flash Firmware Oreo November
- Instal ROM
- Restore EFS & Modem
- Reboot System

### Troubleshoot

1. Bug mic, suara telepon: flash fix dari tread di forum xda [ini](https://forum.xda-developers.com/mi-a1/themes/twrp-voice-calls-fix-10-0-3-0-firmware-t3882745){:rel="nofollow external noopener"}
2. Bug kamera: Gunakan **Google Camera**, bisa ambil [dari sini](https://www.celsoazevedo.com/files/android/google-camera/){:rel="nofollow external noopener"} (pilih sendiri).
