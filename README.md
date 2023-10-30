**Latar Belakang**
  Salat adalah salah satu kewajiban penting dalam agama Islam, dan merupakan salah satu cara utama untuk berkomunikasi dengan Allah. Waktu-waktu salat telah ditetapkan dalam ajaran Islam, dan setiap muslim diwajibkan untuk menunaikan salat lima kali sehari. Namun, dalam era teknologi modern, penggunaan ponsel pintar dan notifikasi nada dering telah menjadi bagian tak terpisahkan dari kehidupan sehari-hari.
  Sayangnya, dalam beberapa situasi, notifikasi nada dering ponsel dapat mengganggu pelaksanaan salat, terutama saat salat berjamaah di masjid. Ketika seorang muslim berada di dalam masjid, fokusnya seharusnya tertuju pada ibadah dan konsentrasi dalam berkomunikasi dengan Allah. Notifikasi ponsel yang tidak dimatikan atau nada dering yang terdengar dapat mengganggu ketenangan dan konsentrasi dalam ibadah.
  Selain itu, ada juga tantangan dalam hal kesadaran akan waktu salat dan lokasi masjid terdekat. Terkadang pengguna ponsel mungkin tidak sadar tentang waktu salat yang telah tiba atau tidak tahu lokasi masjid terdekat, yang dapat menghambat pelaksanaan salat berjamaah.
Dalam konteks ini, diperlukan sebuah aplikasi yang dapat membantu pengguna dalam menjalankan ibadah salat dengan lebih baik. Aplikasi ini harus mampu memberikan pengingat waktu salat, membantu menemukan masjid terdekat, dan secara otomatis menonaktifkan notifikasi nada dering saat pengguna memasuki masjid. Hal ini akan membantu pengguna dalam meningkatkan kesadaran terhadap waktu salat, memfasilitasi pelaksanaan salat berjamaah, dan mengurangi gangguan notifikasi nada dering selama ibadah di masjid.
  Dengan memahami tantangan ini, kami merasa perlu untuk mengembangkan aplikasi yang dapat menjadi solusi praktis bagi umat Islam dalam menjalankan ibadah salat dengan lebih baik dan meningkatkan kualitas ibadah mereka di masjid.
**Branding**
Merk: SolatYuk
Tagline: Lebih nyaman ke masjid 
Campaign: Bagaimana membantu mengurangi hambatan solat berjamaah seperti notifikasi handphone 
Target user: Usia 7+
Yang terlalu sibuk dengan notifikasi gadget
User experience theme: 
Mudah dikonfigurasi dan digunakan
Terknoneksi dengan aplikasi berbasis mobile
**User Story**
**Metode dan Algoritma**
Pada tahap ini kita menjelaskan metode dan algoritma yang digunakan pada setiap komponen teknologi UbiCom. Contoh:
Sensor:
API Gmaps pada mobile apps
Responder:
Notifikasi Handphone
Mobile software development
**Struktur Data**

1. Entitas Waktu Salat:
   - Nama waktu salat (subuh, dzuhur, asar, maghrib, isya).
   - Jam waktu salat (dalam format 24 jam).
   - Tanggal waktu salat (jika diperlukan).
   - Nama masjid terdekat tempat salat dilaksanakan.

2. Lokasi Masjid:
   - Nama masjid.
   - Koordinat GPS (latitude dan longitude).
   - Alamat masjid.
   - Jadwal waktu salat di masjid tersebut.

3. Pengaturan Pengguna:
   - Preferensi pengguna terkait notifikasi (suara pengingat, mode getar, atau nonaktifkan notifikasi).
   - Lokasi pengguna (lokasi default atau yang terkini).
   - Pengaturan pribadi lainnya (pengingat kustom, latar belakang aplikasi, dll.).

4. Status Mode Masjid:
   - Status aktif/nonaktif mode masjid untuk pengguna tertentu.
   - Masjid yang diatur dalam mode masjid.
   - Pengaturan terkait mode masjid (notifikasi dinonaktifkan, latar belakang aplikasi disesuaikan, dll.).

5. Pemberitahuan Notifikasi:
   - Daftar notifikasi yang muncul pada ponsel pengguna.
   - Tanggal dan waktu notifikasi.
   - Tipe notifikasi (waktu salat, pemberitahuan masjid).

6. Log Aktivitas Pengguna:
   - Riwayat aktivitas pengguna, seperti waktu salat yang telah dilaksanakan di masjid tertentu.
   - Pencatatan penggunaan aplikasi dan pengaturan yang telah dilakukan.

**Arsitektur Sistem**
a.	Pemberitahuan Waktu Salat: Aplikasi akan memiliki database waktu salat harian yang diambil dari sumber yang terpercaya. Pengguna akan menerima pemberitahuan ketika waktu salat tiba.
b.	Lokasi Masjid Terdekat: Aplikasi akan menggunakan GPS atau lokasi pengguna untuk menemukan masjid terdekat dan memberikan petunjuk arah ke masjid tersebut.
c.	Mode Masjid: Aplikasi akan memiliki mode masjid yang, ketika diaktifkan, akan secara otomatis menonaktifkan notifikasi nada dering pada ponsel pengguna saat mereka berada di dalam masjid. 
d.	Pengaturan Pribadi: Pengguna dapat mengatur pengingat waktu salat sesuai preferensi pribadi, seperti suara pengingat yang diinginkan atau pengaturan kustom lainnya. 
e.	Notifikasi dan Peringatan: Aplikasi akan memberikan notifikasi kepada pengguna beberapa menit sebelum waktu salat tiba dan memberikan peringatan tentang jadwal waktu salat yang akan datang.
f.	Integrasi dengan Peta: Aplikasi akan terhubung dengan layanan peta untuk memberikan informasi tentang lokasi masjid terdekat dan arah ke sana.
**Deskripsi Teknologi**
Pada tahap ini kita menjelaskan setiap teknologi hardware dan software yang digunakan dalam pembangunan sistem. Contoh:
Smart phone: Android & iPhone. Aplikasi ini dapat diakses melalui perangkat handphone.
Software development
Mobile development: Flutter. Flutter mempermudah untuk membuat apps dan juga meletakan API Gmaps
Sensor
Radius Jarak : Menggunakan API Gmaps dalam flutter
Responder
Notifikasi Handphone
**User Experience (UX) Design**
