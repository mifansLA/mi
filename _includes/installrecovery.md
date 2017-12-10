## Memasang custom recovery dengan fastboot

Download dulu custom recovery yang kamu inginkan. Kamu bisa download CWM Recovery dari link yang tersedia. Lebih direkomendasikan memakai TWRP untuk device keluaran baru. atau you can download TWRP. File semacam ini biasanya berupa file image (`twrp-x-x.img` atau `cwm-x-x.img`). Jika file berupa `*.zip`, biasanya untuk mempermudah update versi atau berganti recovery. Jika berniat untuk memasang custom recovery dengan fastboot, kamu perlu meng-ekstrak file `*.img` dalam file `*.img` tersebut.

Sambungkan ponsel kamu dengan PC dengan kabel data.

Beralih ke komputer, buka **command prompt** (OS Windows) atau **terminal** (Linux atau macOS), kemudian ketik perintah :

   adb reboot bootloader 

Kamu juga bisa masuk ke fastboot mode menggunakan tombol kombinasi :

Tahan tombol Volume Down dan Power bersamaan hingga tulisan “FASTBOOT” muncul pada layar ponsel baru dilepas.

> Untuk kamu yang kesulitan masuk fastboot mode (Xiaomi keluaran baru), biasanya harus [Unlock Bootloader (UBL)](https://mi.knoacc.org/carane-unlock-bootloader-hape-xiaomi)terlebih dahulu.

Jika sudah masuk fastboot mode, cek apakah ponsel sudah dikenali PC dengan mengetik :

   fastboot devices 

> Jika kamu melihat peringatan _no permissions fastboot_ saat memakai Linux atsu macOS, coba jalankan fastboot sebagai root.{:.alert alert-info}

Flash recovery ke ponsel kamu :

   fastboot flash recovery twrp-x-x.img

> Sesuaikan `twrp-x-x.img` dengan file`*.img` yang kamu unduh.

Sekarang reboot ke recovery untuk memeriksa apakah custom recovery sudah terpasang atau belum: Tahan tombol Volume Up (atau kedua tombol Volume) dan Power bersamaan hingga logo “MI” muncul di layar, baru kamu lepaskan tombol Power. Sambil tetap menahan tombol Power hingga muncul logo TWRP, baru lepaskan tombol Volume.