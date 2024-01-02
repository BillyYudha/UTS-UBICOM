# UAS UBIQUITOS COMPUTING
## Aplikasi Web Sistem Absensi Sekolah Berbasis QR Code
**NO 1**

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

![absensiqr](https://github.com/BillyYudha/UTS-UBICOM/assets/113665144/a773abee-cf14-48ef-9078-ce8a4ef91091)

**Arsitektur Sistem**

![arsitektur sistem qrcode](https://github.com/BillyYudha/UTS-UBICOM/assets/113665144/fc49edd4-1249-42e5-8eba-f3d8c2e53bd0)

**Deskripsi Teknologi**

Teknologi yang digunakan dalam pengembangan aplikasi absensi QR code dengan menggunakan framework CodeIgniter 4 mencakup berbagai komponen, mulai dari backend hingga frontend, serta komponen pendukung. Berikut adalah deskripsi teknologinya:

1. Backend:
   - CodeIgniter 4: Framework PHP yang digunakan untuk membangun backend aplikasi. CodeIgniter 4 menyediakan struktur MVC yang kokoh, mempermudah pengelolaan kode, serta menyediakan sejumlah pustaka dan helper        yang mempercepat pengembangan.
   - PHP 8.x: Versi PHP yang digunakan oleh CodeIgniter 4. PHP 7.x memiliki peningkatan kinerja dan keamanan dibandingkan dengan versi sebelumnya.

2. Database:
   - MySQL: Database relasional yang digunakan untuk menyimpan data pengguna, data kehadiran, dan data lain yang diperlukan. CodeIgniter 4 memiliki dukungan yang baik untuk berbagai jenis              database relasional.

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

**NO 2 DAN NO 3**

VIDEO Demo Aplikasi :
https://youtu.be/63s9VTDwj5s

![Screenshot (239)](https://github.com/BillyYudha/UTS-UBICOM/assets/113665144/1400d1af-fa83-4cc4-9da1-fa141303efae)

Aplikasi Web Sistem Absensi Sekolah Berbasis QR Code adalah sebuah proyek yang bertujuan untuk mengotomatisasi proses absensi di lingkungan sekolah menggunakan teknologi QR code. Aplikasi ini dikembangkan dengan menggunakan framework CodeIgniter 4 dan didesain untuk mempermudah pengelolaan dan pencatatan kehadiran siswa dan guru.

## Fitur Utama

- **QR Code scanner.** Setiap siswa/guru menunjukkan qr code kepada perangkat yang dilengkapi dengan kamera. Aplikasi akan memvalidasi QR code dan mencatat kehadiran siswa ke dalam database.
- **Login petugas.**
- **Dashboard petugas.** Petugas sekolah dapat dengan mudah memantau kehadiran siswa dalam periode waktu tertentu melalui tampilan yang disediakan.
- **QR Code generator.** Petugas yang sudah login akan men-generate qr code setiap siswa/guru secara otomatis. Setiap siswa akan diberikan QR code unik yang terkait dengan identitas siswa. QR code ini akan digunakan saat proses absensi.
- **Ubah data absen siswa/guru.** Petugas dapat mengubah data absensi setiap siswa/guru. Misalnya mengubah data kehadiran dari `tanpa keterangan` menjadi `sakit` atau `izin`.
- **Tambah, Ubah, Hapus(CRUD) data siswa/guru.**
- **Tambah, Ubah, Hapus(CRUD) data kelas.**
- **Lihat, Tambah, Ubah, Hapus(CRUD) data petugas.** (khusus petugas yang login sebagai **`superadmin`**).
- **Generate Laporan.** Generate laporan dalam bentuk pdf.

## Framework dan Library Yang Digunakan

-  CodeIgniter 4
-  Material Dashboard Bootstrap 4
-  Myth Auth Library
-  Endroid QR Code Generator
-  ZXing JS QR Code Scanner

## Screenshots

### Tampilan Halaman QR Scanner

![Screenshot (250)](https://github.com/BillyYudha/UTS-UBICOM/assets/113665144/23babfef-0c6d-434e-9985-cd337c983365)

### Tampilan Absen Masuk dan Pulang

![Screenshot (248)](https://github.com/BillyYudha/UTS-UBICOM/assets/113665144/f1bffb63-912b-47c8-994c-c0eedf04b38a)
![Screenshot (249)](https://github.com/BillyYudha/UTS-UBICOM/assets/113665144/7249079f-d9ef-489e-a6b2-3a50b983ba0f)

### Tampilan Login Admin

![Screenshot (236)](https://github.com/BillyYudha/UTS-UBICOM/assets/113665144/2127772d-a0c9-48a0-952f-abb849e1143e)

### Tampilan Dashboard Admin

![Screenshot (239)](https://github.com/BillyYudha/UTS-UBICOM/assets/113665144/b78eef2b-673a-4356-90a8-f2ddfbb96889)

### Tampilan CRUD Data Absen


| Siswa (Dengan Data Kelas)                                                                                                   |                                                           Guru                                                           |
| --------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------: |
| ![Screenshot (240)](https://github.com/BillyYudha/UTS-UBICOM/assets/113665144/891c4fd8-f8c0-4059-84e0-8de20c8d2bac) | ![Screenshot (241)](https://github.com/BillyYudha/UTS-UBICOM/assets/113665144/411ad2e5-e089-45b8-bed4-cad0c35dadaf)

### Tampilan Ubah Data Kehadiran

![image](https://github.com/BillyYudha/UTS-UBICOM/assets/113665144/0da14a9f-cc80-4404-b599-63b9c29c65b4)

### Tampilan CRUD Data Siswa & Guru

![image](https://github.com/BillyYudha/UTS-UBICOM/assets/113665144/acbd4d4c-7721-44b7-9b01-52466467b8f0)
![image](https://github.com/BillyYudha/UTS-UBICOM/assets/113665144/c93679f1-ae07-4456-80ae-f34eb71a12aa)

### Tampilan CRUD Data Kelas & Jurusan

![image](https://github.com/BillyYudha/UTS-UBICOM/assets/113665144/fdb21d42-9f6a-4a55-9066-22803554eb9f)

### Tampilan Generate QR Code dan Generate Laporan

![image](https://github.com/BillyYudha/UTS-UBICOM/assets/113665144/e43ece16-8a9a-4638-8b08-1af4f0a0162f)
![image](https://github.com/BillyYudha/UTS-UBICOM/assets/113665144/36d3c225-6be1-4b11-8c40-a13922451518)
![image](https://github.com/BillyYudha/UTS-UBICOM/assets/113665144/4e277f00-dfd7-45ec-a822-0b6389b99b2c)

## Cara Penggunaan

### Persyaratan

- [Composer](https://getcomposer.org/).
- PHP dan MySQL atau [XAMPP](https://www.apachefriends.org/download.html) versi 8.1+ dengan mengaktifkan extension `-intl` dan `-gd`.
- Pastikan perangkat memiliki kamera/webcam untuk menjalankan qr scanner. Bisa juga menggunakan kamera HP dengan bantuan software DroidCam.

### Instalasi

- Unduh dan impor kode proyek ini ke dalam direktori proyek anda (htdocs).
- (Opsional) Konfigurasi file `.env` untuk mengatur parameter seperti koneksi database dan pengaturan lainnya sesuai dengan lingkungan pengembangan Anda.
- (Opsional) Ganti/replace logo sekolah di `public/assets/img/logo_sekolah.jpg`.
- (Opsional) Konfigurasi file `app/Config/App.php` untuk mengubah base url sesuai dengan nama folder project.
- Penting ⚠️. Install dependencies yang diperlukan dengan cara menjalankan perintah berikut di terminal:

```shell
composer install
```

- Buat database `db_absensi` di phpMyAdmin / mysql
- Penting ⚠️. Jalankan migrasi database untuk membuat struktur tabel yang diperlukan. Ketikkan perintah berikut di terminal:

```shell
php spark migrate --all
```

- Buka file `vendor/myth/auth/src/Config/Auth.php`. Lalu ubah kedua baris berikut:

```php
    public $requireActivation = 'Myth\Auth\Authentication\Activators\EmailActivator';

    public $activeResetter = 'Myth\Auth\Authentication\Resetters\EmailResetter';
```

- ubah value menjadi `null`:

```php
    public $requireActivation = null;

    public $activeResetter = null;
```

- (Opsional) Masih di file yang sama, ubah baris berikut:

```php
public $views = [
        'login'           => 'Myth\Auth\Views\login', // baris ini
        'register'        => 'Myth\Auth\Views\register',
        'forgot'          => 'Myth\Auth\Views\forgot',
        'reset'           => 'Myth\Auth\Views\reset',
        'emailForgot'     => 'Myth\Auth\Views\emails\forgot',
        'emailActivation' => 'Myth\Auth\Views\emails\activation',
    ];
```

menjadi:

```php
public $views = [
        'login'           => '\App\Views\admin\login', // menggunakan tampilan login custom
        'register'        => 'Myth\Auth\Views\register',
        'forgot'          => 'Myth\Auth\Views\forgot',
        'reset'           => 'Myth\Auth\Views\reset',
        'emailForgot'     => 'Myth\Auth\Views\emails\forgot',
        'emailActivation' => 'Myth\Auth\Views\emails\activation',
    ];
```

- Jalankan web server.
- Lalu jalankan aplikasi di browser.
- Login menggunakan krendensial superadmin:

```
username : superadmin
password : superadmin
```

Jika ingin mengubah email, username & password dari superadmin

Buka file `app\Database\Migrations\2023-08-18-000004_AddSuperadmin.php` lalu ubah & sesuaikan kode berikut:

```php
// INSERT INITIAL SUPERADMIN
$email = 'adminsuper@gmail.com';
$username = 'superadmin';
$password = 'superadmin';
```

- Izinkan akses kamera.

**NO 4**

Context Aware Systems yang digunakan sejauh ini adalah sistem yang peka terhadap hari,tanggal,tahun dan jam sehingga bisa didapat data absensi masuk pada waktu kapan.

**NO 5**

Aspek Kecerdasan yang dikembangkan menurut saya cukup inovatif yang diterapkan dalam sistem absensi yang menyebabkan hal ini lebih efisien dalam segi waktu serta menghemat sumber daya kertas.

**NO 6**

- Sensor berupa fungsi atau metode pada bagian controller yang menangani permintaan pemindaian QR code menggunakan kamera. CodeIgniter 4        dapat menggunakan library atau helper QR code untuk membaca informasi dari QR code.
- Responder terletak dalam controller yang mengelola logika bisnis untuk absensi. Setelah QR code dipindai, sistem dapat memanggil              metode yang akan mencatat kehadiran pengguna ke dalam database atau melakukan tindakan lain sesuai kebutuhan.

**NO 7**

Secara khusus, berikut adalah beberapa aspek yang berkaitan dengan protokol komunikasi data dalam sistem tersebut:

-  HTTP (Hypertext Transfer Protocol):
    Menggunakan HTTP sebagai protokol komunikasi utama. Permintaan (request) dari klien, seperti pemindai QR code atau browser, dikirimkan ke     server menggunakan metode HTTP seperti GET atau POST. Server kemudian merespons dengan memberikan data atau melakukan tindakan yang           sesuai.

-  Metode HTTP (GET, POST):
    Metode HTTP GET umumnya digunakan untuk permintaan yang tidak memodifikasi data di server, misalnya saat mengakses halaman untuk              pemindaian   QR code. Metode HTTP POST, di sisi lain, sering digunakan untuk mengirim data yang dapat memodifikasi status di server,          seperti saat mengirim informasi kehadiran ke database.

-  JSON (JavaScript Object Notation):

    JSON dapat digunakan sebagai format pertukaran data antara klien dan server. Misalnya, ketika pemindaian QR code berhasil, data kehadiran     dapat dikirim dari klien ke server dalam format JSON, dan server dapat merespons dengan data lainnya dalam format yang sama.

 -  URL Encoding:

     Pada saat pengiriman data melalui URL, data sering kali dienkripsi menggunakan URL encoding untuk memastikan keamanan dan kebenaran           pengiriman data. CodeIgniter 4 mendukung manajemen parameter URI dan dapat memproses data yang dikirim melalui URL dengan aman.






