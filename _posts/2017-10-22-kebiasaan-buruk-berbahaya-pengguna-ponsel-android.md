---
title: "Intermezo ★ Punya 4 Kebiasaan Buruk ini? Android Kamu Tidak Aman!"
excerpt: "4 Kebiasaan buruk dalam menakai ponsel android yang menjadikan data pribadi gampang dicuri hacker dan solusinya"
author: phateholloway
header:
 image: https://www.logicmanager.com/wp-content/uploads/2011/07/IT-Risks.jpg
 caption: security risk
category:
 - intermezo
tags:
 - keamanan wifi publik 
 - aplikasi berbahaya
 - bahaya instal apk
 - cache aplikasi
 - miui security
---

Salam peluk (cium juga kalau mau) untuk member Mi Fans Lamongan! Dan MIUI Fans Indonesia! Pada thread kali ini, saya akan mencoba memberi pencerahan terkait isu keamanan ber-internet terutama sejak munculnya publikasi tentang KRACK Attack. Tentu saja ada beberapa hal lain yang juga berisiko. Langsung saja kita mulai.

**Kebiasaan Buruk Yang Harus Kamu Dihindari**

Ada beberapa hal umum yang meningkatkan resiko serangan dari beberapa kebiasaan yang sepertinya  sering kita lakukan.

## 1. Menggunakan Hotspot/Wi-Fi Publik

Apa sih maksudnya Wi-Fi publik? Wi-Fi publik biasa dikenal sebagai Hotspot dapat ditemukan di tempat umum senisal; bandara, kedai kopi, mal, restoran, atau hotel yang disediakan agar pengunjung bisa mengakses Internet secara gratis. "Hotspot" ini begitu luas dan umum sehingga kita sering menggunakannya tanpa berpikir dua kali. Meskipun sepertinya tidak berbahaya saat dipakai untuk mainan med-sos, atau cuma buat baca-baca berita, membaca e-mail, memeriksa rekening bank Anda, dan aktivitas lain yang mehgharuskan log-in merupakan aktifitas berisiko saat memakai Wi-Fi publik.

### Apa Saja Bahayanya?

#### Pencurian data pribadi

HotspotHotspotHotspotHotspot publik tidak hanya "_menarik_" pengguna biasa, tapi juga "_seksi beut_" di mata para hacker. Para peretas mampu mencuri data perangkat yang terhubung ke hotspot tanpa enkripsi dan pegamanan yang menadai. Melalui hotspot publik, para peretas dapat berkomunikasi dengan perangkat kamu tanpa autentikasi dari perangkat kamu dengan mudahnya. Setiap informasi seperti email, rincian kartu kredit/debit, foto pribadi, dan kredensial keamanan pun tak luput dari bahaya.

#### Distribusi perangkat lunak berbahaya.

Hacker juga bisa menggunakan jaringan ini untuk men-distribusi-kan malware ke perangkat yang terhubung. Malware membutuhkan waktu lebih singkat untuk terdistribusi via hotspot, yang mungkin langsung bisa beraksi sesaat setelah terkoneksi. Hacker juga bisa meng-hack server wi-fi ini kemudian memodifikasi keamanan & koneksi yang ada.

#### Koneksi hotspot palsu.

SebagianSebagian besar restoran atau tempat umum memiliki koneksi hotspot asli yang dilengkapi dengan beberapa pengamanan. Namun, hotspot palsu bisa dibuat dengan SSID yang sama, sehingga pengguna yang percaya bahwa hotspot palsu ini sama dengan yang asli, mebjadi korban hacker. Bahkan baru-baru ini ada kasus [WPA2 bisa dibobol dengan KRACK Attack](https://mi.knoacc.org/krack-attack-breaks-wpa2-wifi-protocol) yang membuat vendor besar kalang kabut. Jangankan Wifi Publik, Jaringan Wi-Fi dengan keamanan WPA2 saja masih bisa dibobol.

### Bagaimana agar tetap aman saat memakai Hotspot/Wi-Fi publik?

Cara terbaik untuk menjamin bahwa koneksi kami sdah aman saat menggunakan Wi-Fi publik adalah **dengan menggunakan virtual private network (VPN)**, Bahkan jika hacker berhasil memposisikan dirinya di tengah koneksi ataran kamu dan hotspot (MITM), data kamu di sini masih aman karena terenkripsi. Jika kamu masih suka mamakai Wi-Fi publik, sebaiknya gunakan VPN untuk melindungi informasi kamu. Atau jika Anda tidak ingin terhubung secara otomatis ke hotspot tersebut, lebih baik mematikannya bila tidak dibutuhkan.

{% include inarticle.html %}

## 2. Memasang aplikasi dari sumber yang tidak dikenal.

### Apa itu sumber yang tidak dikenal?

Semua sumber dari aplikasi yang anda pasang selain Playstore disebut sebagai **Sumber tak dikenal**. 

### Seberapa besar risiko memasang aplikasi dari sumber yang tidak dikenal?

Jika kamu memilih untuk [mendownload aplikasi](https://mi.knoacc.org/videoder-v14-video-music-downloader-adfree) selain dari Google Play Store dan memasangnya pada perangkat Android, maka sangat beresiko pada perangkat kamu. Kamu harus berhati-hati saat mendownload aplikasi dari sumber pihak ketiga. Beberapa aplikasi atau file APK, mungkin saja disisipi perangkat lunak yang berbahaya bagi perangkat kamu dan  data yang tersimpan di dalamnya. Bahkan ada juga beberapa aplikasi berbahaya yang mengunduh perangkat lunak jahat lain di latar belakang. 

### Bagaimana agar aman dari aplikasi berbahaya?

Sebelum mendownload dan menginstal aplikasi dari sumber pihak ketiga, lebih baik mengetahui bagaimana cara meminimalisasi aplikasi yang disisipi perangkat lunak berbahaya. Kamu juga harus melakukan beberapa tindakan pencegahan. Pertama, periksa perizinan yang diminta aplikasi dari ponsel kamu. Kamu bisa melihat aplikasi game yang meminta izin untuk mengakses kontak, email, atau call-log, yang tidak masuk akal. Beberapa aplikasi meminta banyak sekali izin padahal tidak begitu dibutuhkan. Selalu lebih baik untuk memeriksa perizinan daripada menyesal dibelakang. Kamu bisa memakai aplikasi keamanan yang sudah ada di ROM MIUI untuk memeriksa izin khusus yang diminta aplikasi tertentu.

ROM MIUI, juga memiliki scanner/anti-virus. Setelah memasang aplikasi dari sumber yang tidak diketahui, sebaiknya memindai perangkat satu kali, tidak perlu mencari aplikasi anti-virus lain!! Yang ada malah bikin kacau! 

## 3. Cache yang menumpuk

Apakah ponsel kamu mulai melambat dari waktu ke waktu? Berikut ada tips ringan untuk mengembalikan performa seperti sediakala.

Ada dua alokasi cache di ponsel Android: **1. Cache aplikasi** dan **2. Cache sistem**.

### Cache aplikasi. 

Sama seperti file Temporary yang ada di OS Windows. Yakni tempat dimana aplikasi menyimpan data sementara. Sebenarnya file cacche ini berguna saat memakai aplikasi karena mengurangi waktu pemuatan. Namun jika dibiarkan malah menumpuk dan menjadi beban, inilah penyebab aplikasi menjadi tidak lelet.

Jika sebuah aplikasi mulai bertingkah, biasanya praktik yang baik untuk mencoba dan membersihkan cache terlebih dahulu dan melihat apakah itu membantu.Manfaatnya hanya untuk membersihkan ruang baik di telepon Anda dan untuk alokasi sementara aplikasi. 

> Baca juga: [Aplikasi Gawe Ngresiki File Sampah Android](https://mi.knoacc.org/donlot-aplikasi-gawe-ngresiki-memori-sdmaid-pro-apk)

### Cache sistem.

Yang ini jarang sekali yang tahu apalagi mengaksesnya. Di sinilah sistem menyimpan data sementara untuk proses yang berjalan. Prinsip yang sama juga berlaku di sini: Jika ponsel kamu mulai terasa berat dan kadang berperilaku aneh seperti serinh menutup paksa aplkasi tertentu, kamu bisa mencoba membersihkan cache sistem.

Untuk membersihkan ini hanya bisa  melalui 'Recovery Mode' dan melakukan pilihan wipe cache. Untuk Android terbaru, akses recovery mode ini hanya bisa diakses dengan melakukan rooting atau mealui custom recovery.

Menghapus cache berarti bahwa semua file sementara yang ada aplikasi atau sistem yang tersimpan telah hilang. Akibatnya, waktu start-up menjadi lebih lama saat dibuka pertama kali setelah cache dihapus.

## 4. Mengabaikan update MIUI

Tidak seperti penyedia rom custom lainnya, Xiaomi punya basis dukungan [komunitas pengembang](//en.miui.com/fotum.php) yang besar untuk ROM MIUI. Developer di MIUI memberikan update secara reguler. Untuk update pengguna rom yang stabil diberikan sekali dalam satu atau dua bulan namun untuk pengguna rom beta, diberikan update mingguan, dua-mingguan bahkan ada yang harian. 

### ROM Beta dan ROM Stabil

Pengguna yang memakai rom beta memperbarui secara otomatis segera setelah ada pembaruan, karena mereka ini adalah pengguna yang membantu pengembangan ROM agar bisa memberikan uodate pada rom stabil. Sebagian besar pengguna rom MIUI memakai versi global stabil, yang tidak banyak tertarik untuk melakukan flashing & update, apalagi update mingguan. Pengguna rom stabil harusnya melakukan pembaruan yang rilis secara OTA tepat waktu dan tidak menunda memperbarui. Dalam tiap pembaruan biasanya akan ada fitur baru yang ditambahkan, perbaikan bug, penambalan celah keamanan Android & update versi Android (sangat jarang sekali).

Mengabaikan pembaruan dapat menyebabkan kerusakan perangkat, rentan diserang peretas (karena tingkat patch keamanan yang lemah) dan tidak bisa menikmati fitur baru. Jadi 100% dianjurkan untuk [mengupdate MIUI](https://mi.knoacc.org/download-miui-9-global-beta-71019-fastboot-recovery) saat ada pemberitahuan 

Secara keseluruhan, sangat perlu untuk waspada dan tidak sembrono dalam memakai ponsel Android. Tetapi sebagai pengguna Xiaomi, rasanya tidak perlu kuatir karena ROM MIUI termasuk baling banyak update dan pembaruan fitur. Jadi, bagaimana menurut kamu?
