---
title: "[Qualcomm] Fix IMEI NULL untuk ponsel Xiaomi dengan file QCN"
excerpt: "Cara Memperbaiki IMEI Hilang dan Baseband melalui Cara Restore File QCN pada Device Xiaomi"
categories:
 - IMEI
tags:
 - Fix IMEI null
 - Fix erase persist
 - Baseband Null
 - QCN imei fix
header:
 og_image: https://u01.appmifile.com/images/2018/04/03/3cef2eec-6811-406b-bed8-89dd91bf9916.jpg
---

Halao halao MiFans LA yang budiman, ketemu lagi dengan pak diman di sini yang ingin membagikan sebuah cara memperbaiki IMEI Hilang atau _invalid_ dan  kasus Baseband melayang yg mengakibatkan ~sariawan dan bibir pecah-pecah~ tidak bisa menyalakan wi-fi dan bluetooth. Solusinya akan dijelaskan dalam acara **Restore file QCN pada Device Xiaomi**.

Dalam beberapa kasus yang terjadi, bahwa hilangnya IMEI dan Baseband bisa diksebabkan oleh kesalahan dalam memasang firmware, corrupt saat flashing, dan juga karena kesengajaan (menghapus partisi persist untuk mem-bypass Mi Account). Terhapusnya IMEI dan beberapa alamat WiFi dan Bluetooth (Baseband)

Berbeda dengan ponsel cipshet Mediatek yang imeinya bisa diganti dengan aplikasi android, IMEI Qualcomm sedikit lebih rumit. Dan kebanyakan smartphone Xiaomi memakai Qualcomm. Demi kalian, artikel tentang cara mengembalikan IMEI yang hilang ini muncul. 

> Catatan: Bagi mifans yang salah memasang firmware hanya perlu mengmbalikan firmware ponselnya ke firmware yang tepat sebelum lanjut ke tahap ini.

### Siapkan Alat, File dan Software yang dibutuhkan
Hal-hal yang perlu dipersiapkan sebelum melakukan perbaikan IMEI/Baseband

1. Siapkan PC/Laptop, jika tidak punya sebaiknya pinjam kawan, jangan di Warnet. 
2. Kabel USB Original/bawaan atau yang berkualitas bagus.
3. Download **Tool QPST 2.2.422** [dari sini](https://drive.google.com/file/d/12IidHLvtbvZ66AhwpLPdFqMflUVvnUAb/view?usp=drivesdk)
4. Download file **QCN Xiaomi** yang sesuai dengan device mifans, cari [di sini](https://mi.knoacc.org/daftar-file-qcn-ponsel-xiaomi-untuk-fix-imei)
5. Download Tool **Write Dual IMEI** [di sini](https://drive.google.com/file/d/1MF9S6ouFk45J3KnRXWtQletqo4J8jpnt/view?usp=drivesdk)
6. Download **Minimal ADB Fastboot** [di sini](https://drive.google.com/file/d/1nljtGoYfDQTpcdPi_g2DhnJNz7dkXmpU/view?usp=drivesdk) jika belum punya.
7. Download **Driver HS USB QDLoader 32bit** [di sini](https://drive.google.com/file/d/1rD-dXhnoGDhlz0lbF4WMvN1TjUZt6-ip/view?usp=drivesdk) untuk Windows 32 bit
8. Atau download **Driver HS USB QDLoader 64bit** [di sini](https://drive.google.com/file/d/1HQO3uRIIf2snvbVu3kOumBug8RM0uH_U/view?usp=drivesdk) untuk Windows 64 bit

> Ekstrak file yang di unduh dalam satu lokasi (folder) agar mudah mengakses, install software QPST dan Driver,

Setelah siap semua bahan di atas, lanjut ke langkah selanjutnya.

### Langkah-Langkah Melakukan Restore QCN

1. Pertama nyalakan _USB Debugging_ dengan cara **Setting** - **Developer Options** - Ceklis **USB Debugging** dan bagi kalian yang belum tau cara aktifkan opsi pengembang / developer option bisa mengikuti cara berikut **Setting** - **About Phone** - tap7x pada **MIUI Version**.
2. Setelah itu sambungkan perangkat kalian ke PC/Laptop menggunakan kabel USB.
3. Ekstrak **Minimal ADB Fastboot.zip** di PC (jika belum) kemudian masuk ke folder _Minimal ADB Fastboot_ dan jalankan file **Start.bat** (atau tekan keyboard `shift` dan klik kanan, pilih Command Promt) maka akan muncul jendela command prompt lalu ketik perintah berikut :
`adb devices` (enter) 
Akan muncul kombinasi huruf dan angka.
bila sudah lanjutkan ketik perintah : 
`adb shell` (enter)
`su` (enter)
`setprop sys.usb.config diag,adb` (enter)
4. Cek pada ponsel akan muncul pop up pemberitahuan diag port terbuka, dan cek pada Device Manager di PC seharusnya sudah muncul port **Qualcomm HS-USB Android DIAG 901D (COMxx)**.
![Diag 901D Port](https://u01.appmifile.com/images/2018/04/03/3ca11801-1f46-4ecc-ba22-703f292b8a0e.jpg)
5. Jika sudah kedetek lanjut jalankan tool **QPST** lalu pilih software download dibagian port klik browse dan pilih driver diag port device agan (COMxx sesuaikan dengan yang di Device Manager sebelumnya).
![set port COM](https://u01.appmifile.com/images/2018/04/03/35ba4804-9ece-4e0c-a20a-5194fecff83b.jpg)
6. setelah itu pilih **Restore** dan di bagian **QCN File** pilih **browse** kemudian cari file.qcn xiaomi yang sudah didownload lalu klik start dan tunggu proses sampai beres.
![qcn file](https://u01.appmifile.com/images/2018/04/03/4cad5ca6-f453-4c57-a7c1-cbb1fec33998.jpg)
7. Setelah selesai jalankan IMEI Writer Tool
![imei writer](https://u01.appmifile.com/images/2018/04/03/21d6eb7b-567a-4545-9327-f8273645e54c.jpg)
8. Tuliskan Nomor IMEI smartphone kalian sesuaikan dengan yang ada di box ponsel kalian atau yang ada di balik baterai, lalu klik start,selesai.
9. Selanjutnya matikan kembali koneksi diag nya dengan masuk ke folder Minimal ADB Fastbootdi PC kemudian jalankan file Start.bat maka akan muncul jendela cmd prompt lalu ketik perintah berikut :
`adb shell` (enter)
`setprop sys.usb.config adb,mtp` (enter)
10. Selesai, kemudian reboot hape nya.
11. Setelah itu silahkan kalian cek IMEI dengan dial *#06#.

Okay, Restore File QCN pada Device Xiaomi sudah selesai.

Semoga bermanfaat, jangan lupa tiggalkan jejak kalian. Itung-itung numpang terkenal seperti Ngadimin, hehehe..
Bantu admin menyebarkan ilmu dengan membagikan artiekl ini ya luur...
