**Latar Belakang**

1. Konteks dan Kebutuhan:
Dalam konteks pengelolaan kehadiran karyawan atau peserta suatu acara, pencatatan absensi merupakan aspek penting untuk memastikan kehadiran yang akurat dan efisien. Sistem manual seringkali memakan waktu dan berisiko terjadi kesalahan. Oleh karena itu, penggunaan teknologi QR code dalam mengelola absensi dianggap sebagai solusi yang lebih modern, cepat, dan akurat.

2. Alasan Memilih QR Code:
QR code dipilih sebagai teknologi untuk sistem absensi karena keunggulannya dalam kecepatan pemindaian dan kemudahan implementasinya. Setiap individu atau peserta akan memiliki QR code unik yang dapat dipindai menggunakan perangkat kamera ponsel pintar atau perangkat pembaca QR code lainnya.

3. Manfaat Sistem Absensi QR Code:

- Efisiensi Waktu: Proses absensi menjadi lebih cepat dan efisien karena hanya memerlukan pemindaian QR code.
- Akurasi Data: Mengurangi risiko kesalahan manusia yang mungkin terjadi pada sistem manual.
- Pelacakan Kehadiran Real-time: Sistem memungkinkan pemantauan kehadiran secara langsung dan dapat memberikan laporan real-time.
4. Pemilihan Framework CodeIgniter 4:

- Ringan dan Cepat: CodeIgniter 4 dikenal sebagai framework PHP yang ringan dan memiliki kinerja tinggi, cocok untuk proyek-proyek dengan kebutuhan responsif dan efisien.
- MVC Architecture: Arsitektur Model-View-Controller (MVC) pada CodeIgniter memisahkan logika bisnis, presentasi, dan pengelolaan database, memudahkan pengembangan, pemeliharaan, dan pengujian aplikasi.
5. Keamanan:

- Proteksi Data: CodeIgniter 4 menyediakan fitur keamanan yang kuat untuk melindungi data, termasuk proteksi terhadap serangan SQL injection dan Cross-Site Scripting (XSS).
6. Pengembangan Fitur Tambahan:
Selain fitur dasar absensi QR code, aplikasi juga dapat dikembangkan dengan beberapa fitur tambahan, seperti:

- Riwayat Kehadiran: Menyimpan dan menampilkan riwayat kehadiran untuk keperluan pelacakan.
- Notifikasi: Mengirim notifikasi kepada pengelola atau peserta terkait status kehadiran.
- Integrasi Database: Integrasi dengan database untuk menyimpan dan mengelola data kehadiran.
  
**Branding**

Branding: QRAttend

Tagline: Hadirkan Kehadiran dengan Mudah

Deskripsi:
QRAttend adalah solusi modern untuk manajemen kehadiran yang menggabungkan kemudahan penggunaan dengan teknologi QR code. Dirancang khusus untuk mempermudah proses absensi, QRAttend memberikan solusi yang efisien dan terhubung dengan aplikasi berbasis mobile.

Nilai Utama:
1. Absensi Tanpa Batas: QRAttend memungkinkan absensi tanpa batas dengan menggunakan QR code yang unik untuk setiap individu.
2. Kemudahan Penggunaan: Penggunaan QRAttend sangat mudah, cukup dengan pemindaian QR code untuk merekam kehadiran.
3. QRAttend memberikan kemudahan konfigurasi dan pemantauan kehadiran secara real-time.

Campaign Message:
"Dengan QRAttend, kehadiran menjadi lebih mudah dan efisien. Pemindaian QR code memberikan pengalaman absensi yang cepat dan terhubung dengan aplikasi mobile memastikan Anda selalu terkini dengan data kehadiran. Hadirkan kehadiran dengan mudah bersama QRAttend."

Target User:
Organisasi atau perusahaan yang mencari solusi modern dan efisien untuk manajemen kehadiran, serta memprioritaskan kemudahan penggunaan.

User Experience Theme:
Mudah Dikonfigurasi dan Digunakan, Terkoneksi dengan Aplikasi Mobile

Visual Identity:
Warna: colorfull yang mencerminkan teknologi modern dan kepercayaan.
Font: Bersih, futuristik, dan mudah dibaca.

QRAttend tidak hanya membawa kemudahan teknologi QR code untuk manajemen kehadiran, tetapi juga menghadirkan pengalaman pengguna yang efisien dan terhubung. Bersama QRAttend, kehadiran menjadi lebih dari sekadar absensi, tetapi bagian dari pengelolaan yang modern dan cerdas.

**User Story**

![rate](https://github.com/BillyYudha/absensiqr/assets/113665144/e561b3b7-8b80-4610-8773-e3182282f5ab)

Metode dan Algoritma

Perangkat lunak pada penelitian ini dikembangkan dengan metode waterfall. Metode ini mempunyai kelebihan karena bersifat sistematis dan berurutan 
sehingga memudahkan pengembang dalam melakukan pembuatan sistem dan membuat perangkat lunak terjaga kualitasnya.

**Struktur Data**

![struktur data absen qr](https://github.com/BillyYudha/absensiqr/assets/113665144/b3022b39-ccac-42e1-9667-03177db6b1d9)

**Arsitektur Sistem**

a.	Pemberitahuan Waktu Salat: Aplikasi akan memiliki database waktu salat harian yang diambil dari sumber yang terpercaya. Pengguna akan menerima pemberitahuan ketika waktu salat tiba.

b.	Lokasi Masjid Terdekat: Aplikasi akan menggunakan GPS atau lokasi pengguna untuk menemukan masjid terdekat dan memberikan petunjuk arah ke masjid tersebut.

c.	Mode Masjid: Aplikasi akan memiliki mode masjid yang, ketika diaktifkan, akan secara otomatis menonaktifkan notifikasi nada dering pada ponsel pengguna saat mereka berada di dalam masjid. 

d.	Pengaturan Pribadi: Pengguna dapat mengatur pengingat waktu salat sesuai preferensi pribadi, seperti suara pengingat yang diinginkan atau pengaturan kustom lainnya. 

e.	Notifikasi dan Peringatan: Aplikasi akan memberikan notifikasi kepada pengguna beberapa menit sebelum waktu salat tiba dan memberikan peringatan tentang jadwal waktu salat yang akan datang.

f.	Integrasi dengan Peta: Aplikasi akan terhubung dengan layanan peta untuk memberikan informasi tentang lokasi masjid terdekat dan arah ke sana.

**Deskripsi Teknologi**

Teknologi yang digunakan dalam pengembangan aplikasi absensi QR code dengan menggunakan framework CodeIgniter 4 mencakup berbagai komponen, mulai dari backend hingga frontend, serta komponen pendukung. Berikut adalah deskripsi teknologinya:

1. Backend:
   - CodeIgniter 4: Framework PHP yang digunakan untuk membangun backend aplikasi. CodeIgniter 4 menyediakan struktur MVC yang kokoh, mempermudah pengelolaan kode, serta menyediakan sejumlah pustaka dan helper        yang mempercepat pengembangan.
   - PHP 8.x: Versi PHP yang digunakan oleh CodeIgniter 4. PHP 7.x memiliki peningkatan kinerja dan keamanan dibandingkan dengan versi sebelumnya.

2. Database:
   - MySQL atau PostgreSQL: Database relasional yang digunakan untuk menyimpan data pengguna, data kehadiran, dan data lain yang diperlukan. CodeIgniter 4 memiliki dukungan yang baik untuk berbagai jenis              database relasional.

3. Frontend:
   - PHP, CSS, JavaScript: Bahasa-bahasa dasar untuk membangun antarmuka pengguna (UI) pada bagian frontend.

4. QR Code Generation:
   - QR Code Generator Library: Pustaka yang dapat menghasilkan QR code dari data yang diberikan. Beberapa pilihan pustaka populer termasuk `bacon/bacon-qr-code` untuk PHP atau pustaka JavaScript seperti `qrcode.js`.

5. Authentication:
   - CodeIgniter 4 Authentication Library: CodeIgniter menyediakan pustaka bawaan untuk otentikasi pengguna. Pustaka ini dapat diintegrasikan dengan model pengguna untuk mengelola otentikasi.

6. Security:
   - Security Helpers: CodeIgniter menyertakan sejumlah helper keamanan, termasuk fungsi hashing password, validasi input.

7. Middleware:
   - CodeIgniter 4 Middleware: Memungkinkan untuk menyisipkan kode atau logika sebelum atau setelah eksekusi dari suatu request. Middleware dapat digunakan untuk otentikasi, logging, atau sejumlah tugas               middleware lainnya.

8. Development Tools:
   - Composer: Untuk manajemen paket PHP, termasuk pustaka-pustaka yang diperlukan untuk proyek.
   - Code Editor atau IDE: Seperti Visual Studio Code, PhpStorm, atau IDE lainnya untuk pengembangan dan penyuntingan kode.
