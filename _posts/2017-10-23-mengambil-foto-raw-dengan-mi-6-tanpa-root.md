---
title: "Mobile Fotografi ★ Mengambil Foto RAW dengan Camera Mi 6 Tanpa Root ★ Tips Trik"
excerpt: 
author: "phateholloway"
header:
 image: "https://www.honorbuy.com/img/Xiaomi_Mi_6_Smartphone1492592832.jpg"
 caption: "tips trik mobile fotografi"
category:
 - resources
tags:
 - mobile fotografi
 - raw image
 - xiaomi mi 6
 - tips trik
---

Halo para pengguna Xiaomi Mi 6 pecinta **Mobile Fotografi**, sempat kecewa saat Kamu tahu bahwa ponsel flagship ini **tidak mendukung RAW file**. Ya... Saya tahu kalau fitur RAW bisa di aktifkan dengan merubah nilai camera HAL3 menjadi: `persist.camera.HAL3.enabled=1` dalam file build.prop. Tetapi kan butuh root? Sementara gak semua orang mau melakukannya dengan alasan tersendiri.

Okay, jadi apakah ada cara lain selain cara tersebut diatas? Ada. Kamu semua bisa mengikuti trik yang akan saya bagikan berikut ini **agar bisa mengambil foto RAW dengan Kamera Mi 6 tanpa root**. Ayo langsung di praktekkan saja. 

## Cara mudahnya

Persiapkan dulu 2 aplikasi fotografi berikut:

1. Pasang aplikasi **Bacon Camera** via [Playstore](https://play.google.com/store/apps/details?id=com.fgnm.baconcamera) atau unduh apk-nya [di sini](/dl/mega?hash=dlEV3BxD!HNN8-mq8S-ITGnaL4dXnA8i-2I49sN_CCr2WxqKH8fA&name=BaconCam.apk&size=7.8MB).
2. Pasang aplikasi Adobe Lightroom via [Playstore](https://play.google.com/store/apps/details?id=com.adobe.lrmobile)

![bacon camera](https://i.imgur.com/Sh82JnO.png)

> Perhatian: Cara ini mungkin gagal di beberapa ponsel. Kalau gagal silahkan langsung ke [Cara sulitnya](#cara-sulitnya).

Setelah terpasang, lakukan langkah-langkah berikut:

**Langkah pertama:** Buka aplikasi kamera Bacon Camera dan and buka bagian **Pengaturan**. Caranya: Klik pada menu, lihat ada (3 garis di kiri tengah) dan pilih **setting**

![setting](https://i.imgur.com/XxJwm2R.jpg)

**Langkah kedua:** Pilih Save Bayer RAW format

Sebenernya kamu bisa juga memilih format BMP di bagian pilihan format gambar (picture format).

![format gambar](https://i.imgur.com/uMivsm1.png)

**Langkah ketiga:** Coba ambil foto dengan Bacon Camera. Hasil foto akan di sinpan dalam ekstensi DNG.

![hasil capture](https://i.imgur.com/fyEnmaj.png)

Hasil foto ini tidak akan muncul di gallery. Silahkan cari hasil foto di folder **DCIM/Camera/RAW/** di penyimpanan default Mi 6 kamu.

### Yang perlu diperhatikan:

- Tidak ada mode HDR untuk pengambilan foto dengan format file gambar bayer
- Tidaknada tanda air '**Shot On Mi 6**'
- Suara Kamera/Shutter tidak bisa silent meskipun sudah di non-aktifkan
- Kadang aplikasi menutup sendiri (FC)
- Pengambilan gambar dalam mode default lebih gelap (karena memang file mentah). Jika ingin lebih cerah, lebih baik pakai mode manual.

### Pengolahan Gambar

Untuk pengolahan gambar agar layak pisting/publish, gunakan **Adobe Lightroom** dan sesuaikan gambar yang kamu mau. Gambar hasil olahan terproses tipis-tipis saja. Tapi setidaknya lebih hemat waktu. Kalau ini. Kalau kamu mau hasil yang murni gambar RAW, langsung saja ke [metode lanjutan](#cara-sulitnya). Berikut contoh hasilnya:

![adobe lightroom](https://i.imgur.com/RjaFLUo.png)

Hasil Mentah (Bacon Camera)

[foto bunga raw](https://i.imgur.com/LzOqA10.jpg){:.btn .btn--info} [foto kedua raw](https://i.imgur.com/kkRLflD.jpg){:.btn .btn--info}

Hasil Edit (Adobe Lightroom)

[hasil edit bunga](https://i.imgur.com/UXILobp.jpg){:.btn .btn--info}[hasil edit kedua](https://i.imgur.com/pfcOD6R.jpg){:.btn .btn--info}

## Cara sulitnya

{% include inarticle.html %}

Karena ini cara sulit, maka kamu perlu ekstra sabar untuk mendapatkan hasil RAW. Yang jelas, hasilnya benar-benar murni RAW. Mentah-sementah-mentahnya! Dan tentu saja membutuhkan bantuan PC.

Siapkan dulu beberapa hal berikut:

1. Pasang aplikasi FreeDcam di Mi 6, download apk-nya [di sini](/dl/mega?hash=Al0nhbjD!qBDCbXtBkJXT2XMjJClCEV9pwPOGFGGr9ovDcAw6-OE&name=Freedcam4.1.apk&size=4.64MB) dan ikuti [langkah pengaturannya](#pengaturan-freedcam)
2. Pasang software Dcraw di PC. Download file zip-nya [dari sini](/dl/mega?hash=d4FAXArY!BzdO_4nmtp5Ofgz7rZwlJT_uXumIz2fndmgnlnmK5YE&name=DavidCoffindcraw.zip&size=205KB) dan ekstrak saja di PC. Berguna untuk [pengolahan gambar](#mengolah-foto-raw) hasil capture

> Catatan: Metode ini juga kadang gagal. Mau gak mau harus rooting Mi 6 kalau masih _keukeuh_ pingin hasil foto RAW

### Instalasi dan Persiapan

**Langkah pertama:** Untuk pemasangan aplikasi FreeDcam silahkan pasang seperti biasa. Jangan lupa aktifkan pilihan `Unknown Source` agar bisa memasang aplikasi ini.

![allow permission](https://i.imgur.com/5mUZKSk.png)

Buka aplikasi dan berikan izin (allow) untuk semua permintaan yang diminta.

**Langkah kedua:**{:#pengaturan-freedcam} Dalam aplikasi, atur ukuran gambar pada ukuran `4032 x 3016` untuk gambar dengan kualitas yang lebih tinggi lihat bayer format-nya di bagian **RAW stuff** seharusnya ada `bayer-mipi-10rggb` di situ.

![pengaturan freedcam](https://i.imgur.com/BwEzexc.png)

Pastikan juga API disetel pada `camera`.

> Jika format 'bayer-mipi-10rggb' tidak ada maka cara ini tidak bisa kamu lanjutkan. Kamu harus mengaktifkan **Camera2 API** agar Mi 6 kamu mendukung RAW.

**Langkah ketiga:** 

### Mengolah Foto RAW

Mengkonversi file `.bayer` menjadi RAW

**Langkah pertama:** Hubungkan Mi 6 kamu ke PC dan salin/pindahkan file dengan ekstensi `.bayer` yang tersimpan dalam folder **/DCIM/FreeDcam/**

[file .bayer](https://i.imgur.com/U3tM1qU.png){:.btn .btn--info}

**Langkah kedua:** Letakkan file `.bayer` di dalam folder yang sama dengan software dcraw (`dcraw.exe`)

[lokasi salinan](https://i.imgur.com/Xcej0Bb.png){:.btn .btn--info}

**Langkah ketiga:** Jalankan Command Promt (CMD) dengan cara menekan tombol [ctrl] + [shift] dan [klik kanan] pada folder yang sama, klik pada pilihan **Open command window here**

**Langkah keempat:** Ketik perintah berikut untuk mengkonversi file `.bayer`menjadi file RAW
`dcraw -v -c -T 2017_09_30_17_17_03.bayer > 2017_09_30_17_17_03.raw`.

[perintah konversi](https://i.imgur.com/Nm4AQm5.png){:.btn .btn--info}

Setelah menekan enter, kamu akan memperoleh file `.raw`. Kamu juga bisa mendapatkan type file dengan format lain semisal `.tiff`

**Langkah kelima**: Cek hasil konversi. Lokasi hasil konversi ada dalam folder yang sama.

[file-file RAW](https://i.imgur.com/aywa8QB.png){:.btn .btn--info}

Coba lihat, Gambar akan terlihat kehijauan dan ini normal kok.

![gambar RAW](https://i.imgur.com/c55gUta.jpg)

Ini karena gambar **belum di proses** sama sekali. Jadi masih mentah, murni dari hasil tangkapan sensor camera Mi 6 langsung.

### Beberapa paraneter perintah konversi yang bisa dipakai antara lain: 
- -v : Print verbose messages
- -c : Write image data to standard output
- -e : Extract embedded thumbnail image
- -i : Identify the files (JPEG file might not work),No Decoding occurs
- -i -v : Output EXIF data that is stored in the file
- -a : Automatic adjust the white balance
- -w : Uses the camera white balance
- -r : Set custom white balance [r, g, b, g(default is 1.0)]
- -b Set the brightness (default is 1.0)
- k : Set the darkness-o [0-4] Output colorspace (raw,sRGB,Wide Gamut,XYZ)
- -d : Document Mode (no color, no interpolation)
- -q : [0-3] Set the interpolation quality
- -f : Interpolate RGGB as four colors
- -B : Using bilateral filter to eliminate noise
- -2 : Write 8-bit non-linear PPM or PGM
- -4 : Write 16-bit linear PPM or PGM
- -3 : Write 16-bit linear PSD

> Tutorial lanjutan untuk pengolahan memakai **Dcraw** bisa langsung ke situs [Image Engineering](https://www.image-engineering.de/library/technotes/720-have-a-look-at-the-details-the-open-source-raw-converter-dcraw)

#### Contoh pemmakaian perintah

Perintah untuk meningkatkan  **darkness** dan **white balance** adalah:

`dcraw -v -c -T -r 2.0 2.0 2.0 2.0 -k 65 2017_09_30_17_17_03.bayer > 2017_09_30_17_17_03.raw`

Berikut adalah hasilnya: 

![hasil konversi](https://i.imgur.com/DsdRqE7.jpg)

### Mengolah Gambar RAW

![Adobe Lightroom](https://i.imgur.com/qiPsg9c.jpg)

Aplikasi yang mendukung pengolahan gambar RAW tidak banyak. Hanya sedikit sekali, salah satunya adalah **Adobe Lightroom** and **Snapseed**.

![hasil olahan](https://i.imgur.com/jgNdqKL.jpg)

Meskipun bisa memakai kedua aplikasi ini, tetapi tentu lebih ajib kalau mengolah gambar RAW dengan PC/Laptop daripada di ponsel langsung mengingat banyak sekali software image editing yang tersedia untuk PC yang mendukung pengolahan gambar RAW.
