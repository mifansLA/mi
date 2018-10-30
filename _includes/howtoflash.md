### Recovery Method.
Tidak berbeda jauh dengan melakukan update via OTA, cara ini masih tetap menggunakan aplikasi pembaruan (_updater_) namun kamu mesti mengunduh ROM recovery pada Xiaomi smarphone yang berextensi `.zip` terlebih dahulu.

**Cara Pertama**

Klik aplikasi pembaruan (_updater_) pada Xiaomi smartphone atau dengan mengakses **Setelan** (_Settings_) -> **Tentang Ponsel** (_About Phone_) -> **Pembaruan** (_System updates_),  kemudian klik tiga titik pada sudut kanan atas  >  (_Choose update package_) temukan file `update.zip` pembaruan yang telah kamu download tadi, aplikasi akan melakukan pengecekan/verifikasi pada file tersebut apabila sukses kemudian klik **mulai ulang dan perbaharui**, smartphone akan reboot secara otomatis dan proses update akan berjalan dalam beberapa menit.

**Cara Alternatif**

Letakkan kopian file `.zip` yang sudah kamu unduh ke dalam folder **downloaded_rom**. Ingat, jangan dipindah (cut), agar kamu tetap punya cadangan jika gagal update. karena file yang ada di folder tersebut akan hilang semua setelah melakukan update atau reboot ke recovery mode. Jadi nanti kalau gagal, bisa mengulangi prosesnya.

Kemudian reboot ponsel ke recovery mode seperti biasanya (dengan tombol kombinasi). Atau bisa juga dari **Setelan** (_Settings_) -> **Tentang Ponsel** (_About Phone_) -> **Pembaruan** (_System updates_),  kemudian klik **tiga titik** pada sudut kanan atas  > pilih (_Reboot recovery_)

Sama halnya dengan update secara OTA dengan cara ini kamu tidak membutuhkan komputer (PC) untuk melakukan update pada versi Xiaomi smartphone yang terbaru.

### Fastboot Method

Kamu butuh bantuan PC/Komputer. Kemudian memasang software **Mi PC Suite** terlebih dahulu agar mempermudah driver smartphone terdeteksi pada komputer dan [**MiFlashtool**](/dl/any?dom=api.en.miui.com&code=url/MiFlashTool&name=MiFlashtool&size=Ready) untuk flashing file fastboot.

Sebelum melakukan update melalui MiFlash Tools ada baiknya melakukan backup data-data yang tersimpan pada penyimpanan primer (internal memory) kamu, karena melakukan update menggunakan metode ini umumnya akan memformat internal memory. Dengan metode ini juga dapat melakukan install ulang Xiaomi smartphone kamu.

Setelah kamu melakukan backup, matikan daya smartphone dan langsung masuk mode fastboot pada tipe keluaran lawas. Untuk tipe baru, devices kamu harus sudah [Unlock Bootloader (UBL)](/carane-unlock-bootloader-hape-xiaomi) agar kamu tidak perlu masuk ke Emergency Mode Download (EDL)

> Jika belum UBL kamu perlu masuk dalam mode EDL. Ada beberapa cara untuk beralih ke mode ini: [**4 Cara Masuk Mode Emergency Mode Download (EDL) Xiaomi**](/empat-cara-masuk-mode-edl-xiaomi).

Kemudian barulah menjalankan Mi Flash Tool yang telah kamu install terlebih dahulu pada komputer (PC) kamu, untuk mempergunakan tool ini klik **refresh** terlebih dahulu apabila terdeteksi driver kemudian baru klik "select / Browser" cari file ROM Fastboot yang telah kamu download dan **jangan lupa untuk di ekstrak terlebih dahulu**. 

Setelah kamu menemukan file ROM tersebut, pilih salah satu opsi yang ada di bagian bawah seperti clear all, save user data atau clear all and lock.

Terakhir barulah kamu mengklik **flash** tunggu hingga notifikasi tool menjadi **sukses** setelah selesai lepas kabel data yang terhubung dan nyalakan kembali smartphone kamu.
