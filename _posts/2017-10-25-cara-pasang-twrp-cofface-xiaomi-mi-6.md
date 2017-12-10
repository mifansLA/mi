---
title: "Tutorial TWRP ★ Xiaomi Mi 6 ★ Cofface"
excerpt: "Cara mudah memasang TWRP Cofface untuk Xiaomi Mi 6 dengan ADB Fastboot"
header:
 image: "https://www.honorbuy.com/img/Xiaomi_Mi_6_Smartphone1492592832.jpg"
 caption: "twrp cofface xiaomi mi 6"
category:
 - tutorial
tags:
 - twrp mi 6
 - tutorial twrp
 - twrp cofface
 - download twrp
---

Mempunyai TWRP sebagai pengganti recovery bawaan (Mi Recovery) sangat banyak sekali manfaatnya. Untuk memasang TWRP recovery di smartphone Xiaomi Mi 6 cukup mudah. Sekarang sudah tersedia TWRP  Cofface yang sudah mempunyai fitur _dm-verity disabler_ untuk smartphone ini. Fitur ini berguna agar Xiaomi Mi 6 tidak mengalami bootloop setelah pemasangan custom recovery. 

{% include toc %}

Dan sesuai judul {{ page.title }}, kali ini saya akan menjelaskan step by step untuk kamu semua. Berikut ini tutorialnya.

### Persyaratan Pasang TWRP

Sebelum kamu bisa memasang TWRP Recovery Official di smartphone kesayangan, kamu harus sudah melakukan **Unlock Bootloader (UBL)** Xiaomi Mi 6 kamu terlebih dahulu. Untuk tutorialnya bisa mengikuti tutorial UBL (unlock bootloader) yang sudah ada. Jika memang belum UBL silahkan ikuti tutorial [Unlock Bootloader Semua Ponsel Xiaomi](/https://mi.knoacc.org/dijamin-sukses-unlock-bootloader-semua-xiaomi) agar bisa memasang TWRP

### File/Bahan Pasang TWRP

- Minimal ADB & Fastboot v1.4.2 Via [Androidfilehost](/dl/afh?fid=745425885120698566&name=minimalADBv.1.4.2&size=Androidfilehost)
- TWRP Cofface via [Androidfilehost](/dl/afh?fid=817550096634771569&name=cofface_recovery_sagit_en.img&size=Androidfilehost)

### Cara Pasang TWRP Cofface

- Pastikan dulu USB Debugging pada smartphone Xiaomi Mi 6 kamu sudah aktif.
- Matikan device Xiaomi Mi 6 kamu ke mode fastboot dengan cara menekan tombol **Power** + **Volume Down** secara bersamaan sampai masuk ke dalam mode fastboot
- Hubungkan device kamu ke PC menggunakan kabel USB dalam keadaan mode fastboot
- Matikan device Xiaomi Mi 6 kamu ke mode fastboot dengan cara menekan tombol <strong>Power + Volume Down </strong>secara bersamaan sampai masuk ke dalam mode fastboot.
- Buka folder hasil ekstrak file ADB Fastboot
- Buka CMD dengan cara tekan tombol keyboard SHIFT (jangan lepaskan) kemudian klik kanan pilih **Open Windows Command Here**
- Setelah jendela CMD terbuka ketikan perintah `fastboot devices` jika Mi 6 sudah terdeteksi berarti bisa melanjutkan proses flashing TWRP Cofface
- Sekarang pindahkan file TWRP Cofface ke dalam folder ADB Fastboot
- Setelah itu ketikan perintah seperti di bawah ini `fastboot flash recovery cofface_recovery_sagit_en.img`
- Tekan enter untuk memulai proses flashing, jika gagal silahkan ubah `cofface_recovery_sagit_en.img` sesuai dengan nama file TWRP recovery yang kamu unduh.
- Lanjutkan dengan mengetik perintah `fastboot boot recovery` dan tekan enter.
- Sartphone Xiaomi Mi 6 kamu akan masuk ke TWRP recovery dengan sendirinya.

Selesai.

> NOTE : Jika kamu menggunakan TWRP Recovery ini tidak perlu install file **Patch dm-verity** karena TWRP Cofface ini sudah include fitur DM-Verity disabler. Kamu bisa melakukan flash Super SU untuk sekaligus [melakukan rooting pada Xiaomi Mi 6](/cara-root-xiaomi-mi-6-tanpa-pc) kamu.

Itu tadi tutorial tentang {{ page.title }}. Semoga artikel kali ini bermanfaat dan jangan lupa untuk membagikan halaman ini ke teman-teman kami di sosial media, supaya mereka juga mendapatkan manfaat yang sama seperti kamu saat ini, terima kasih sudah berkunjung dan membaca **{{ page.title }} di situs mifansLA**.

_Referensi : http://en.miui.com/thread-677755-1-1.html_
