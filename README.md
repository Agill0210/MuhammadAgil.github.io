# MuhammadAgil.github.io
Untuk link database : https://drive.google.com/drive/folders/1uBeivscVKK9RTfNzB9IB9jodCC9GNocp?usp=drive_link

🐦 Aplikasi Puyuh

📜 Deskripsi

Aplikasi Puyuh adalah sebuah sistem berbasis web yang dikembangkan menggunakan PHP, HTML, dan CSS dengan database MySQL yang dijalankan melalui XAMPP. Aplikasi ini dirancang untuk membantu dalam pengelolaan dan pemantauan usaha ternak burung puyuh.

✨ Fitur Utama

📊 Manajemen data burung puyuh

🏥 Monitoring kesehatan dan produksi telur

🍽️ Manajemen stok pakan dan kebutuhan ternak

📈 Laporan berkala mengenai produksi dan pengeluaran

🛠 Teknologi yang Digunakan

💻 Bahasa Pemrograman: PHP, HTML, CSS

🗄 Database: MySQL

🖥 Server Lokal: XAMPP

🚀 Instalasi

📥 Unduh & Instal XAMPP

Jika belum memiliki XAMPP, unduh dan instal dari Apache Friends.

📂 Pindahkan Proyek ke Direktori XAMPP

Pindahkan folder proyek ke dalam folder htdocs di dalam direktori XAMPP.

🛢 Konfigurasi Database

Jalankan XAMPP dan nyalakan Apache serta MySQL.

Buka http://localhost/phpmyadmin di browser.

Buat database baru (misalnya puyuh_db).

Impor file SQL yang ada di folder database/ ke dalam database.

⚙️ Konfigurasi Koneksi Database

Buka file config.php atau file konfigurasi database lainnya.

Sesuaikan pengaturan berikut dengan kredensial MySQL Anda:

$host = "localhost";
$user = "root";
$password = "";
$database = "puyuh_db";

🌍 Jalankan Aplikasi

Buka browser dan akses:

http://localhost/nama_folder_proyek/

📂 Struktur Folder

/repository
├── /assets        # 🎨 Berisi file CSS, JavaScript, dan gambar
├── /database      # 🗄 Berisi file SQL untuk database
├── /includes      # 🔧 Berisi file koneksi dan konfigurasi
├── /pages         # 📄 Berisi halaman utama aplikasi
├── index.php      # 🏠 Beranda aplikasi
└── config.php     # 🔑 Konfigurasi koneksi database

🤝 Kontribusi

Jika ingin berkontribusi, silakan fork repository ini dan buat pull request dengan perubahan yang diusulkan.

📜 Lisensi

Aplikasi ini menggunakan lisensi MIT.

📌 Catatan: Jika ada kendala atau pertanyaan, silakan buat issue di repository ini atau hubungi saya.
