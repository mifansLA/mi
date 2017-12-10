---
title: "Redmi 1S ★ Install ROM AICP 13.0 ★ It's OREO Time!"
excerpt: Ingin mencicipi OS Android Oreo untuk Xiaomi Redmi 1S. Ada AICP 13.0 yang bisa diapaki untuk upgrade Redmi 1S ke Android Oreo
author: phateholloway
header:
 overlay_image: https://4.bp.blogspot.com/-MZjR-dlHIgk/VKUBmP6NvxI/AAAAAAAAHkk/tGSljEnp6jA/s600/xiaomi-redmi-1s.jpg
 caption: Android Oreo Redmi 1S
category:
 - custom rom
tags:
 - rom aicp oreo
 - android oreo
 - redmi 1s oreo
 - aicp redmi 1s
---
**Oreo is here!!** Redmi 1S yang termasuk hape _lejen bingit_ ini dapat update Oreo! _Guendeng yo lur_? Test build pertama OS Oreo untuk hape yang sering dikatakan sebagai **embahnya hape Xiaomi** ini sudah muncul di dalam _list ROM Oreo AICP_. Karena itulah saya tertarik untuk mencobanya di ponsel Redmi 1S, yang sebetulnya sudah diwarisi adik terkecil saya gaes...

> Hampir gak percaya, hape umur 4th-an tetep dapet update Oreo. "Emmejing!" kata Tukul Arwana.

## Kenalan dengan AICP
![banner aicp](https://raw.githubusercontent.com/AICP/vendor_aicp/n7.1/xda_template/logo_black.png)

**AICP** adalah kependekan dari _Android Ice Cold Project_ yang dimulai dengan pembuatan ROM untuk  Desire HD dan sejak saat itu semakin berkembang menjadi ROM kustom yang semakin matang dan punya basis komunitas penggunanya sendiri seperti halnya **Ressurrection Remix** dan **Mooke**.

Sejak Lollipop, ROM ini selalu menggunakan AOKP sebagai basis pengembangannya. Sayang, AOKP kemudian berhenti mengembangkan ROM-nya unuk saat ini. Dan AICP pun beralih ke CM sebagai basis untuk pengembangan untuk fitur, driver, dan pengenalan hardware. Sedangkan mulai eisi **AICP Oreo**, ROM ini dekembangkan dari Lineage 15.0 sebagai basis yang artinya hampir bisa dikatakan sebagai _Android Pure_ yang sederhana, aman dan lebih cepat dari rom lain.

> Tapi ingat, karena ini masih Build stage awal, bisa dipastikan bahwa ROM ini masih belum layak untuk dipakai harian. Kalau sekedar icip-icip, bolehlah.

## Install AICP Oreo Redmi 1S

**Perhatian:** Pastikan ROM yang kamu unduh sudah sesuai dan memang dioeruntukkan untuk hape kamu sebelum melakukan _flashing_. Karena bisa menjadikan ponsel kamu _bootloop_ bahkan _brick_! Jika kamu yakin kamu bisa melakukannya, silahkan lanjut, tapi jangan pernah komplain jika terjadi sesuatu yang aneh pada hape kamu. Kamu sudah saya anggap bisa mengatasinya sendiri. Dan ingat baik-baik, **ini bukan ROM MIUI** jadi jangan terlalu berharap bahwa semua fitur berjalan sesuai keinginan kamu.

Okay, yuk kita mulai langkah-langkahnya sekarang. 

> baca proses instalasi berikut dengan seksama. Baca setidaknya satu kali sampai habis sebelum memulai.

### Persiapan Instalasi

Jika kamu memasang ROM ini maupun ROM kustom lain, tentu kamu butuh _custom recovery_ yang sudah terpasang. Yang paling populer untuk saat ini adalah [TWRP](http://twrp.me){: rel="noopener noreferer"}. Jadi silahkan flash TWRP ke Redmi 1S dulu. Caranya?

1. Install **TWRP**, gunakan versi terbaru _3.1.1-0_ unduh [di sini](https://dl.twrp.me/armani/twrp-3.1.1-0-armani.img.html).

2. Bagaimana **cara TWRP?** Mengingat ini hape lawas, sudah banyak sekali tutorial yang ada. Tapi kamu bisa mengikuti [tutorial ini](https://www.howtogeek.com/240047/how-to-flash-twrp-recovery-on-your-android-phone/) atau [cara ini](/install-twrp-terbaru-redmi-1s-armani).

3. Flash **Bootloader / Modem Kitkat**. File `zip` ini berisi partisi bootloader dan file modem dari rilis rom terbaru global stabil: **MIUI8 V8.0.1.0 KitKat**. Jadi kamu tidak perlu mengunduh ROM dan memasangya ke Redmi 1S sebelum memasang AICP Oreo. [Firmware 8.2.1.0](/dl/afh?fid=673368273298943134&name=File&size=Ready).

### Download ROM dan Pelengkapnya

Sekarang kamu tinggal mengunduh file ROM AICP beserta GAPS dan Magisk untuk pengatur superusernya:

1. AICP Oreo Edition ROM (the latest): [aicp_armani_o-13.0-UNOFFICIAL-20171030](/dl/afh?fid=673791459329057543&name=AICP&size=Ready).
2. GAPPS: OpenGapps [ARM, 8.0 pico](/opengapps?a=arm&p=pico&os=8.0). Baca: [Versi Lain GAPPS Oreo](https://mi.knoacc.org/daftar-link-download-gapps-android-oreo)
3. ROOT: [Magisk 14.3](http://mi.knoacc.org/dl/any?dom=tiny.cc&code=latestinstaller&name=magiskInstaller.zip&size=Ready). Baca: [Penjelasan Magisk dan Kelebihannya](http://www.knoacc.org/2017/04/penjelasan-magisk-root-cara-sembunyikan-status-root.html)

### BACKUP itu PENTING!

Jangan pernah meremehkan sesuatu! Semudah dan seaman apapun prosesnya, lakukan backup agar mudah kembali ke kondisi sebelumnya!

Untuk itu, lakukan _nandroid backup_ dengan TWRP dengan memilih tiga partisi penting: Boot, Data, dan System dari ROM kamu saat ini. Jika kamu punya Titanium Backup, Backup juga aplikasi kamu sebelum masuk TWRP.  Untuk MIUI, bisa kamu lakukan backup dari: settings > additional settings > Backup & reset > Local backups.

### Langkah Instalasi

1. Unduh semua file yang kamu butuhkan dan simpan di SDCARD
2. Masuk ke mode TWRP dan lakukan **Full wipe**. Ini penting dan harus dilakukan.
3. Flash Firmware. _hanya jika tidak dalam posisi ROM MIUI 8.2.1.0)_
4. Flash paket zip AICP ROM
5. Flash Magisk, hanya kalau kamu ingin Redmi 1s kanu root
6. Flash Gapps. _**Perhatian:** Jangan pasang GAPPS setelah System Reebot dan berjalan jika kamu tak ingin Google play services banyak error and tidak bisa login ke Google server dengan baik_
7. Reboot System

## Fitur yang Berfungsi dan Tidak?

Gaesss... Berhubung ROM ini masih tahap awal pengembangan, ada beberapa fitur yang berfunsibdan tidak.

### Berfungsi Normal

1. Wi-Fi, mobile network berfungsi normal
2. Sharing file dengan Bluetooth bisa jalan lancar.
3. FM Radio maupun Spotify (radio/musik online) bisa betfungsi.
4. Fitur Picture in Picture (PiP) bisa di pake.
5. ROM sehalus paha artis korea, very smoot. Termasuk cepat untuk ukuran hape tuwir. Baterai juga gak boros-boros amat.
6. Untuk sound, sepertinya lebih baik kalau pakai Viper sound mod!

### Tidak/Belum berfungsi

beberapa fitur yang tidak berfungsi:
- Kamera untuk saat ini. Kayaknya bakalan lama nih fix-nya, kayaknya bakalan balik ke rom sebelumnya. _nah kan?_ backup itu penting gaes.
- A2DP Bluetooth gak bisa di pake. Jadi mi bluethoot speaker-nya nganggur.
- Kompas dan sensor lain gak fungsi. (?)
- Ada pop-up yang cukup mengganggu di tiap reboot: **Process system isn't &responding**.

Meskipun banyak hal yang belum berfungsi, akan tetapi rasanya dalam waktu dekat akan sangat banyak perbaikan-perbaikan yang akan diberikan oleh developer/[maintainer](https://forum.xda-developers.com/member.php?u=5963121) AICP Oreo untuk Redmi 1S di forum XDA. Untuk update yang stabil kamu bisa cek langsung di situs official AICP [di sini](http://aicp-rom.com) ya gaes..
