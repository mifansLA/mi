---
title: "Tutorial TWRP ★ Xiaomi Mi 6 ★ Official"
excerpt: "Cara paling mudah memasang TWRP Official untuk Xiaomi Mi 6 dengan flasher toolkit"
header:
 image: "https://www.honorbuy.com/img/Xiaomi_Mi_6_Smartphone1492592832.jpg"
 caption: "twrp official xiaomi mi 6"
category:
 - tutorial
tags:
 - twrp mi 6
 - tutorial twrp
 - official twrp
 - download twrp
---

Mempunyai TWRP sebagai pengganti recovery bawaan (Mi Recovery) sangat banyak sekali manfaatnya. Untuk memasang TWRP recovery di smartphone Xiaomi Mi 6 kini menjadi lebih mudah. Sebabnya, sekarang sudah tersedia sebuah _flasher toolkit_ untuk smartphone ini, jika pada [tutorial pemasangan TWRP recovery](/cara-pasang-twrp-cofface-xiaomi-mi-6) yang sebelumnya masih dengan cara manual, saat ini  sudah dengan cara semi otomatis karena sudah menggunakan toolkit dari user **feed64** anggota forum _en.miui.com_. 

{% include toc %}

Dan sesuai judul {{ page.title }}, kali ini saya akan menjelaskan step by step untuk kamu semua. Berikut ini tutorialnya.

### Persyaratan Pasang TWRP

Sebelum kamu bisa memasang TWRP Recovery Official di smartphone kesayangan, kamu harus sudah melakukan **Unlock Bootloader (UBL)** Xiaomi Mi 6 kamu terlebih dahulu. Untuk tutorialnya bisa mengikuti tutorial UBL (unlock bootloader) yang sudah ada. Jika memang belum UBL silahkan ikuti tutorial [Unlock Bootloader Semua Ponsel Xiaomi](/https://mi.knoacc.org/dijamin-sukses-unlock-bootloader-semua-xiaomi) agar bisa memasang TWRP

### File/Bahan Pasang TWRP

1. Flasher Toolkit TWRP Recovery via [Androidfilehost](/dl/afh?fid=961840155545579488&name=FlaserToolkit&size=Androidfilehost)
2. Minimal ADB & Fastboot v1.4.2 Via [Androidfilehost](/dl/afh?fid=745425885120698566&name=minimalADBv.1.4.2&size=Androidfilehost)
3. DM Verity Disabler via [pCloud](/dl/pcloud?code=XZcFrX7ZzqihMUSpoYmDUbxrthb1zLGMhU0X&name=no-verity-opt-encrypt-5.1.zip&size=1MB)

### Cara Pasang TWRP 3.1.1-0

- Pasang Minimal ADB Fastboot
- Pastikan dulu USB Debugging pada smartphone Xiaomi Mi 6 kamu sudah aktif.
- Matikan device Xiaomi Mi 6 kamu ke mode fastboot dengan cara menekan tombol **Power** + **Volume Down** secara bersamaan sampai masuk ke dalam mode fastboot
- Hubungkan device kamu ke PC menggunakan kabel USB dalam keadaan mode fastboot
- Kemudian ekstrak file Flasher toolkit yang sudah kamu unduh di PC kesayangan kamu
- Kemudian Buka _FLASHER TOOLKIT Sagit.bat_
- Ikuti saja intruksi yang muncul di Command Promp yang terbuka.
- Maka otomatis TWRP Recovery akan terinstall di smartphone Xiaomi Mi 6 (sagit) kesayangan kamu.
- Tekan apa saja setelah pemasangan berhasil, maka smartphone akan reboot ke menu utama TWRP recovery.
- Jika sudah masuk ke TWRP Recovery segera instal **DM-Verity disabler** yang sudah kamu unduh dari link di atas.
- Jika sudah selesai silahkan di reboot

Selesai.

> NOTE : Jika kamu menggunakan TWRP Recovery ini di stock ROM (MIUI) maka install file **Pacth dm-verity** menggunakan TWRP Recovery setelah kamu memilih **Allowing System Modification** kalau gak ingin smartphone kami bootloop, atau kamu bisa melakukan flash Super SU untuk sekaligus [melakukan rooting pada Xiaomi Mi 6](/cara-root-xiaomi-mi-6-tanpa-pc) kamu.

Itu tadi tutorial tentang {{ page.title }}. Semoga artikel kali ini bermanfaat dan jangan lupa untuk membagikan halaman ini ke teman-teman kami di sosial media, supaya mereka juga mendapatkan manfaat yang sama seperti kamu saat ini, terima kasih sudah berkunjung dan membaca **{{ page.title }} di situs mifansLA**.

_Referensi : http://en.miui.com/thread-677755-1-1.html_
