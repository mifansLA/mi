---
title: "Persiapan Langkah Sukses Unlock Bootloader (UBL) Xiaomi Devices"
excerpt: "Dijamin Sukses UBL tanpa pesan kesalahan Couldn't Verify Device lagi apalagi stuck 50% atau bengong di 99%"
author: phateholloway
---
Beberapa hal yang perlu disiapkan dan langkah langkah yang perlu diambil agar tidak banyak gangguan saat akan melakukan UBL akan saya terangkan dalam artikel ini berdasarkan beberapa kali membantu user/member mifansLA. Terutama untuk masalah **Couldn't Verify Device**. Simak yang berikut ini:

### Langkah pertama: Minta izin UBL dulu ke halaman unlock official MIUI.

Pastikan sudah daftar akun **miui forum** atau **mi community** agar lebih mudah mendapat izin UBL.

Caranya: Daftar saja dengan browser bawaan MIUI. Sebab bisa langsung daftar menggunakan akun Mi yang ada di ponsel. Jadi pastikan kamu tahu password akun Mi yang ada di ponselmu karena ini akan dibutuhkan saat menggunakan miflash unlock. 

Kalau bisa lengkapi juga alamat email yang valid. Yang berguna agar tidak perlu mengingat nomor akun mi (sebagai pengganti nomor Mi ID) saat login adalah nomor hape yang masih aktif karena akan dipakai untuk mengirim SMS verifikasi dan pengiriman izin UBL.

Silahkan kunjungi [halaman ini](http://en.miui.com/unlock/) dan klik di tombol **unlock now**{:.btn .btn--primary}

Isi Formulir yang sesuai. Bagian pentingnya adalah pada kolom reason. Kamu bisa mengisinya dengan bahasa inggris, misalnya: "I need unlock bootloader permission for my [type hape] to flash Official ROM since my phone comes with tamperred Firmware" yang artinya kurang lebih begini: "Om minta ijin UBL dong, hape gue sejak beli dapetnya rom abal-abal ey-ke-ey rom distri".

Sekarang tinggal nunggu sms ke nomor hape yang kamu masukkan sevelumnya. Normalnya bisa sampai 3 hari. Tapi kalau sudah pernah posting di forum en.miui.com, ebtah cuma reply, rate, biasanya lebih cepat, pernah gak sampai 1 jam nunggu sudah dapet SMS permission.

### Langkah kedua: Download Mi Unlock tool

Setelah dapet SMS cinta dari miui.com, langsung download tool Mi Unlock dari link berikut

[Download Mi Unlock](http://bigota.d.miui.com/miflashunlock/MiFlashUnlock_1.1.0317.1_en.zip){:.btn .btn--primary}

Ekstrak dan jalankan `mi unlock.exe` setelah langkah kelima selesai.

### Langkah ketiga: Pindah ke ROM Beta dulu.

Untuk kamu yang pakai ROM Global Stable, sebaiknya pindah ke ROM Global Beta dulu. Silahkan cari ROM Recovery (file `.zip` bukan yang `.tgz`) yang sesuai dengan type ponsel kamu.

FYI: Kamu tidak bisa pindah ke ROM ke ROM China Stable langsung dari ROM Global Stable. Kalau dari Global Beta baru bisa.

### Langkah keempat: Login akun Mi Harus Sama.

Buka aplikasi Mi Unlock tool dan login dengan akun yang sama saat minta ijin UBL. Akun yang dipakai harus sama dengan yang dipakai di ponsel Xiaomi kamu. 

> Note: Lebih baik login menggunakan nomor hape di kolom username. Kecuali kamu benar-benar aktif di forum MIUI.

Langkah kelima: Login ke Mi Cloud dengan akun yang sama.

Sekarang buka browser, dan buka Mi Cloud dari [link ini](http://i.mi.com). Login/Signin dengan akum Mi kamu.

Tunggu beberapa saat hingga kamu dapat SMS kode verifikasi dan isikan ke kolom yang ada. Langkah ini untuk mengecek apakah ponsel kamu sudah terhubung dengan Mi Cloud atau belum. Cek Device yang terhubung, hapus ponsel lain yang terhubung jika ada.

Kalau ponsel kamu beluk muncul, coba buka di **Setelan** - **Sinkron** dan _on-off_ kan dengan jeda 5-10 detik sampai device kamu muncul. Refresh halaman Mi Cloud di browser untuk mengecek.

> Untuk memastikan ponsel kamu terhubung, coba gunakan fitur **find my device** dan pastikan GPS nyala. 

### Langkah ke enam: Login akun Mi di Mi Unlock Tool.

Sekarang kamu bisa jalankan `mi unlock.exe` dan silahkan login dengan akun Mi. Gunakan nomor hape untuk username, jangan pakai email.

### Langkah ketujuh: Hidupkan USB Debugging dan OEM Unlock

Ambil ponsel kamu dan masuk menu **Setelan** - **Tentang ponsel** kemudian ketuk 7 kali di bagian **Versi MIUI** hingga muncul toast message `"Sekarand anda adalah seorang pengembang"` dan kembali ke menu **Setelan** dan masuk ke opsi **Setelan tambahan**.

Masuk ke menu **Pilihan pengembang** dan aktifkan **USB debugging**. Aktifkan juga pilihan **Aktifkan OEM terbuka**.

Langkah kedelapan: Masuk mode Fastboot

Matikan dulu ponsel kamu. Kemudian masuk mode fastboot dengan menekan tombol **volume -** bersamaan dengan tombol **Daya/Power** selama beberapa detik hingga muncul Mi Bunny dengan tulisan Fastboot.

Hubungkan ke PC dengan kabel data.

### Langkah terakhir: Unlock Bootloader

Tunggu beberapa saat hingga ponsel Xiaomi kamu terdeteksi.

Langsung saja tekan tombol **Unlock** jika tombol sudah aktif.

Voilllaaaaa hahahahaha....

Sekarang ponsel unyu kamu sudah terbuka kunci bootloadernya. Kamu bisa bebas memodifikasi ponsel kamu. Mulai Rooting, pasang TWRP ganti Custom ROM atau nambahin fitur keren lain semisal Ad-blocker hingga modifikasi Audio Enhancer macam Viper, Dolby Atmos atau mungkin **Unlock Jaringan 4G?**

Terserah kamulah...

