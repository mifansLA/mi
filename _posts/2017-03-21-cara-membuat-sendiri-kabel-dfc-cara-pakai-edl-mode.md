---
title: "Tutorial ★ Membuat Deep Flash Cable (DFC) Sendiri ★ EDL Mode Xiaomi"
excerpt: "Panduan untuk membuat sendiri Deep Flash Cable (DFC) dan Bagaiman cara pakai kabel DFC yang benar agar bisa masuk mode EDL (Emergency Download)"
header:
 teaser: https://i0.wp.com/alephsecurity.com/assets/img/edl_cable.jpg
 og_image: https://i0.wp.com/xiaomitips.com/media/2016/08/MIUI-Deep-Flash-Cable.jpg?resize=640,340
categories:
 - tutorial
tags:
 - membuat kabel dfc
 - kabel edl mode
 - deep flash cable
 - cara masuk edl
date: 2017-03-21 00:01:12 +7
last_modified_at: 2018-07-14 13:16:45 +7
---
{% include respo.html %}

Bagi kamu yang sudah terbiasa ngoprek Android, khususnya smartphone Xiaomi tentu sudah tidak asing lagi dengan kabel DFC, setdaknya pernah dengar. Namun, akan sangat asing bagi kamu yang tidak pernah atau masih baru mengenal seputar Android. Jika kebetulan kamu belum tahu [apa itu DFC](#apa-itu-kabel-dfc), dan apa fungsinya berikut ini dijelaskan terlebih dahulu sebelum kita membahas tentang cara membuatnya.

## Apa itu kabel DFC

![{{ page.title }}]({{ page.header.og_image }}){:.align-center title="Kabel EDL Xiaomi"}

DFC atau Deep Flash Cable merupakan kabel USB yang dimodifikasi secara khusus supaya bisa digunakan untuk melakukan flash Xiaomi brick ataupun Xiaomi-Xiaomi yang tidak bisa masuk mode EDL (Mode 9008). DFC ini juga disebut dengan kabel EDL Xiaomi.

Dengan menggunakan kabel DFC ini secara otomtis Xiaomi akan terdeteksi 9008 di devices manager PC sehingga proses flashing bisa dilakukan.

## Membuat Kabel DFC Sendiri

Kabel DFC itu sendiri sebenarnya sudah banyak dijual bebas di pasaran. Mengingat cara pembuatannya yang sangat mudah sekali tidak ada salahnya kita membuat sendiri di rumah dengan peralatan sederhana. Berikut langkah-langkahnya;

### Alat yang dibutuhkan

- Kabel data USB biasa.
- Cutter atau silet untuk mengupas kabel data.
- Saklar atau _switch_ (bisa gunakan bekas handfree yang sudah tidak terpakai). Yang ini opsional, jadi tidak harus ada.

{% include adsense1.html %}

### Langkah Membuat Kabel DFC

Kupas perlahan kabel USB dengan silet atau cutter, di sana akan **ada 4 kabel** dengan warna berbeda. Yakni, hijau, hitam, merah dan putih.

Kelupas kabel warna hitam dan hijau sehingga terlihat srabutnya. Hubungkan kedua kabel tersebut seperti terlihat pada [skema ini](https://i2.wp.com/globaltechno45.files.wordpress.com/2017/03/cara-membuat-kabel-boot-dfc-andromax.jpg){: title="Skema Kabel DFC"}

Kamu bisa menggunakan saklar atau menyambungkan kabel secara manual.

Untuk mempermudah tentang **cara membuat kabel DFC** atau **kabel EDL Xiaomi**, berikut kamu juga busa melihat panduan videonya.

> **Catatan:**
> Yang dimaksud dengan "_brick_ Xiaomi" adalah kondisi dimana smartphone Xiaomi tidak bisa dinyalakan (matot), hanya muncul indikasi "_red led blink_" ketika dicas atau ketika dihubungkan ke PC. Ketika dikoneksikan ke PC **ada yang terdeteksi 900E**. Tetapi ada juga yang **sama sekali tidak terdeteksi** seperti pada Redmi 3 Pro dan Redmi Note 3 yang pernah dibahas sebelumnya.{:.warning}

Jika sudah bisa cara membuat kabel EDL ini, tidak akan sempurna jika tidak tahu [cara menggunakan kabel DFC](#cara-pakai-kabel-deep-flash). Kamu bisa melihat penggunaanya pada tutorial berikut.

Setelah kamu bejalar [membuat kabel DFC Xiaomi](#membuat-kabel-dfc-sendiri), sepertinya tidak akan lengkap kalau kita tidak mempelajari cara menggunakan Kabel DFC atau Kabel EDL Xiaomi. Masak iya cuma punya senjata langsung maju perang tanpa tahu cara pakainya.

{% include adsense2.html %}

## Cara Pakai Kabel Deep Flash

Sebelum memulai, pastikan bahwa kamu sudah meng_install_ driver Qualcomm terlebih dahulu kecuali agan menggunakan minimal Windows 7 dan terkoneksi ke jaringan internet. Karena driver akan terdwonload dan install secra otomatis. Untuk PC yang tidak terkoneksi ke internet, bisa download driver Qualcomm dari [sini](http://bit.ly/2kWZTFy){: rel="nofollow noreferer noopener"}

OK, untuk mempermudah dalam memahami cara menggunakan kabel DFC atau kabel EDL Xiaomi di sini akan diberikan tiga macam contoh pemakaian.

### Pemakaian yang salah:

Koneksikan HP ke PC dengan kabel USB, setelah konek **baru menggandengkan kabel Hitam dan Hijau** atau **baru menekan tombol saklar** (untuk kabel EDL yang dilengkapi dengan tombol saklar.

### Pemakaian yang kurang tepat:

Koneksikan HP ke PC dengan kabel USB sambil menggandengkan kabel Hitam dan Hijau. Setelah melepas kabel hitam dan hijau kemudian digandengkan lagi. Di sinilah kurang tepatnya, seharusnya setelah melepaskan antara kabel Hitam dan Hijau kamu **jangan menggandengkan lagi**, tapi **tunggu beberapa saat** sampai HP dikenali oleh PC dengan baik.

{% include respo.html %}

### Pemakaian yang benar

Menggandengkan Kabel hitam dan Hijau dulu, (atau menekan switch/ saklar), baru koneksikan HP ke PC dengan kabel USB. Tunggu beberapa saat, kemudian lepaskan saklar atau kabel Hitam dan Hijau yang kamu gandengkan tadi. Tidak lama setelah kamu melepas kedua kabel tersebut, PC akan mendeteksi device baru dengan nama **Qualcomm HS-USB QD-loader 9008** yang artinya sudah masuk mode EDL
<!--
Sebagai contoh untuk mempermudah, di sini kami sudah siapkan Xioami Redmi Note 3 Pro yang matot dan terdeteksi 900E (bukan 9008) di device manager PC. Untuk mengatasi hal ini kami gunakankabel DFC, langsung saja simak video tutorialnya berikut ini.
-->
> **Info:**
> Kabel DFC ini tidak hanya digunakan untuk Xiaomi saja, namun bisa juga untuk smartphone atau ponsel Android dengan chipset Qualcomm{:.info}
