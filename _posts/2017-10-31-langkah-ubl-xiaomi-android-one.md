---
title: "Tutorial UBL ★ Xiaomi Mi A1 ★ Unlock Bootloader"
excerpt: "Cara cepat mudah unlock bootloader untuk Xiaomi Mi A1 dengan ADB Fastboot tanpa reuest unlock!"
header:
 image: "/img/mi-a1.jpg"
 caption: "UBL Xiaomi Mi A1"
category:
 - tutorial
tags:
 - unlock bootloader
 - ubl mi a1
 - ubl tanpa miflash
 - xiaomi mi a1
---
Berselang beberapa minggu yang lalu dari Flashsale Xiaomi Mi A1 di Lazad*. Seperti biasa (dan mungkin kamu juga sudah tahu) biasanya mesti minta ijin dulu buat UBL [di sini](http://en.miui.com/unlock) agar bisa melakukan UBL ponsel Xiaomi kamu dengan MiFlash Unlock Tool. **Tetapi**, beda dengan device Xiaomi lain, untuk UBL ponsel mid-range flagship camera Android One device buatan Xiaomi bersama Google ini, prosesnya sangat mudah sekali. langkah-langkah Unlock Bootloader Mi A1 bisa kamu ikuti berikut ini:

> Note: Baca dulu artikel ini
[Warning: The Risks of Unlocking Xiaomi Mi A1](http://en.miui.com/thread-833843-1-1.html){: rel="noopener noreferer"}

Sebelum itu, pastikan kamu sudah memasang ADB and Fastboot driver di PC kamu. Kamu bisa mengunduh-nya dari link berkut:
[Minimal ADB and Fastboot Drivers](/dl/afh?fid=385035244224386526&name=MinimalADB&size=Ready)

Kemudian pastikan juga kamu sudah disable driver signature enforcement di Komputer/PC kamu. Kamu bisa ikuti panduan ini: [Disable Driver Signature](/)
<!--
[MIUI DEVICE TEAM] Disable Driver Signature Enforcement in Windows 7/8/10 64-Bit
http://en.miui.com/thread-237673-1-1.html
-->

Nah sekarang kamu harus mengaktifkan Developer Options pada Mi A1 kamu terlebih dahulu. Caranya:

- Buka menu settings dan buka About Phone

- Sentuh cepat 7 kali pada Build Number untuk mengaktifkam menu Developer Options.

- Kembali ke menu sebelumnya dengan menekan tombol back dan pilihan Developer Options kini sudah muncul di About Phone.

- Sekarang buka Developer Options and aktifkan OEM unlocking dan USB Debugging.

Tencapkan Mi A1 kamu ke PC dengam kabel data. Windows akan otomatis mendeteksi ponsel kami dan memasang  driver yang dibutuhkan.

Buka folder ADB dan jalankan  Command Prompt dengan menekan [shift] dan klik kanan di ruang kosong dalam folder ADB.

Dalam jendela CMD yang muncul, ketik perintah berikut:

`adb devices`

Lihat di layar ponsel Xiaomi A1 kamu dan pilih OK agar komputer boleh mengirim perintah adb ke ponsel.

Lanjut dengan perintah berikut untuk masuk fastboot mode, jangan luoa tekan enter setelah mengetik.

`adb reboot bootloader`

Setelah Mi A1 me-restart otomatis, kamu akan melihat (seperti biasa) layar fastboot yang ada Mi Bunny lagi nge-las android.

Cek lagi kabel data kamu, pastikan masih tertancap dan gak goyang. Lalu ketik lagi perintah berikut untuk melihat apakah ponsel sudah dikenali: 

`fastboot devices`

Nah, silahkan cek dulu apakah device kamu sudah unlock atau belum dengan perintah:

`fastboot oem device-info`

> jika belum unlock, akan tampil pesan device locked bootloader

Finally, kamu bisa lakukan UBL Xiaomi Mi A1 kamu hanya dengan mengetik perintah berikut: 

`fastboot oem unlock`

Yosshaaah! **Your Mi A1 bootloader is now unlocked**. Enjoy gaesss...
