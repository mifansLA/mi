---
title: "Orange Fox TWRP for Redmi 5 Plus (Vince) Official Stable"
excerpt: "Download Custom TWRP Orange Fox untuk Xiaomi Redmi 5 Plus"
categories: [TWRP]
tags: [twrp orange fox, redmi 5 plus, twrp vince, download twrp]
header:
 teaser:
---
Orange fox adalah custom recovery hasil modifikasi dari custom recovery TWRP (Team-Win Recovery). OrangeFox menambahkan banyak fungsionalitas tambahan yang normalnya tidak diberikan oleh TWRP.

### Download OrangeFox R.10.0 Stable

|Versi|Status|Download|Release|
|---|---|---|---|
|Orange Fox R.10.0|Stable|**Sourceforge**{:.btn .btn--info target="_blank" onclick="window.location.href='https://sourceforge.net/projects/orangefox/files/vince/OrangeFox-R10.0-Stable-vince.zip/download'"}|July 9, 2019|

{% include redpo.html %}

### Instalasi OrangeFox

- Untuk yang belum pernah pasang custom recovery lain, ekstrak file `.zip` yang sudah diunduh.
- Cari file `recovery.img` dalam folder yang sudah diekstrak, pindahkan dalam folder ADB fastboot tool.
- Jika sudah Bootloader sudah unlocked, boot Redmi 5 Plus (vince) ke mode fastboot.
- Tancapkan ke Komputer/Laptop dengan kabel USB.
- Dalam mode fastboot, ketik `fastboot flash recovery recovery.img` dalam Command Prompt (CMD).
- Untuk melakukan boot ke dalam mode recovery, gunakan (1) perintah `fastboot boot recovery.img` dalam CMD atau (2) matikan ponsel fan nyalakan kemnbali dengan menekan ketiga tombol bersamaan.

**Note:** Bootloader perangkat harus di unlock terlebih dahulu untuk memasang custom recovery.

Bagi yang sudah memasang custom recovery TWRP:
- Pindahkan file `OrangeFox-R10.0-Stable-vince.zip` ke penyimpanan eksternal
- Boot ke mode Recovery (TWRP) dan lakukan flashing file `.zip` dari TWRP.
- Pilih Reboot ke Recovery untuk melihat hasilnya.
