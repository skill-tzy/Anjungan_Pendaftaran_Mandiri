# Anjungan Pendaftaran Mandiri

Sistem Anjungan Pendaftaran Mandiri dengan Teknik UI DESIGN menggunakan Framer<br>
Download [PDF laporan Project](https://github.com/user-attachments/files/18745821/240103240_MUHAMMAD.ADZKIA.ADI.SYAHPUTRA_PROJECT.UAS.IMK.pdf)<br>
Lihat [Implementasi Project](https://anjunganpendaftaranmandiri.framer.website)<br>

## 🚀 Latar Belakang

<p align="justify">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Di era modern seperti ini, teknologi sudah menjadi kebutuhan utama dalam segala aspek kehidupan masyarakat, sehingga sebagian besar dalam pelayanan kesehatan terjadi perubahan. Di satu sisi, rumah sakit sering berstatus sebagai garda depan dalam melakukan layanan kesehatan harus selalu upgrade dengan beragam perubahan-perubahan dalam menopang pelayanan di lembaganya. Beberapa isu sering ditemui pada pelayanan pendaftaran pasien yang masih panjang dan sulit, kemacetan antrean yang sangat lama, sering membuat pasien tidak merasa nyaman.
</p>

<p align="justify">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Nah, di sinilah letak peran sistem anjungan pendaftaran mandiri atau disingkat APM. Dengan teknologi ini, pasien bisa mendaftarkan diri secara mandiri melalui antarmuka yang dirancang agar mudah dipahami dan digunakan oleh semua kalangan. Tidak hanya mempercepat proses administrasi, sistem ini juga mengurangi beban kerja petugas pendaftaran sehingga mereka dapat lebih fokus pada tugas-tugas lain yang memerlukan perhatian khusus.
</p>

<!-- <div align="center">
  <img src="https://user-images.githubusercontent.com/95717485/225231893-e59de44d-0d3e-4e79-971b-a4d494565a74.png" alt="Dicoding AWS">
</div> -->

## 🚀 Tampilan Implementasi

### 1. Tampilan Home

<p align="justify">
Tampilan awal atau home dari sistem anjungan pendaftaran mandiri dirancang sederhana dan user-friendly, dengan elemen-elemen berikut:<br>
a. Header:<br>
Terletak di bagian atas halaman sebagai identitas utama sistem. Logo dirancang minimalis, sementara nama sistem ditampilkan dengan tipografi yang mudah dibaca untuk memberikan kesan profesional. Selain itu, header juga menampilkan informasi hari dan tanggal secara realtime yang diperbarui otomatis sesuai waktu pengguna.<br>
b. Bagian Main:<br>
Tombol Angka: Tombol numerik untuk memasukkan angka, biasanya digunakan untuk input nomor identitas pasien atau nomor antrian.<br>
Tombol Hapus Angka: Untuk menghapus angka terakhir yang dimasukkan.<br>
Tombol Bersihkan Angka: Untuk menghapus semua angka yang telah dimasukkan, memberikan opsi reset jika terjadi kesalahan input.<br>
Tombol Cari: Memproses input dan mengarahkan pengguna ke halaman hasil pencarian.(dalam implementasi kali ini klik Tombol Cari otomatis akan mengarah ke halaman identitas)<br>
c. Tombol Menu<br>
Informasi: akan mengarah ke halaman informasi<br>
Bahasa: akan mengarah ke halaman bahasa<br>
Jadwal Dokter: akan mengarah ke halaman jadwal dokter<br>
Feedback: akan mengarah ke halaman feedback<br>
d. Footer<br>
Bantuan: akan mengarah ke halaman bantuan<br>
Tentang: akan mengarah ke halaman tentang<br>
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/99e93081-a209-48ac-8cf7-b00aa7dfc3c0" alt="Gambar c1 tampilan home" width="500">
</div>

### 2. Tampilan Identitas

<p align="justify">
Tampilan Identitas pada sistem anjungan pendaftaran mandiri dirancang untuk memberikan informasi terkait pasien secara jelas dan terorganisir, dengan elemen-elemen berikut:<br>
a. Header:<br>
Terletak di bagian atas halaman sebagai elemen utama yang tetap konsisten di setiap tampilan. Logo sistem tetap tampil minimalis, dengan nama sistem yang menggunakan tipografi sederhana dan profesional. Informasi hari dan tanggal ditampilkan secara realtime untuk memastikan keakuratan waktu selama proses berlangsung.<br>
b. Bagian Utama:<br>
Identitas Pasien: Menampilkan informasi pribadi pasien, seperti nama lengkap, nomor identitas, dan data lainnya yang relevan.<br>
Kolom Histori Reservasi: Bagian ini memuat riwayat reservasi pasien, <br>
c. Footer:<br>
Tombol Kembali: Mengarahkan pengguna kembali ke tampilan home<br>
Tombol Reservasi Baru: Membawa pengguna langsung ke halaman Poli Reservasi Baru untuk melakukan pendaftaran pada layanan atau poli tertentu.<br>
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/e17a6bd6-461a-4289-850c-b66bfbd36f36" alt="Gambar C2 tampilan identitas" width="500">
</div>

### 3. Tampilan Poli Reservasi Baru

<p align="justify">
Tampilan poli reservasi baru dirancang untuk memudahkan pengguna dalam memilih poli tujuan dengan antarmuka yang sederhana dan efisien. Berikut adalah elemen-elemen pada halaman ini:<br>
a. Bagian Utama:<br>
Kolom Dropdown:<br>
Menampilkan daftar pilihan poli tujuan yang tersedia. Pengguna dapat memilih poli yang diinginkan dari daftar tersebut.<br>
Navigasi Otomatis:<br>
Setelah pengguna memilih poli, sistem akan secara otomatis mengarahkan mereka ke tampilan tanggal reservasi untuk langkah selanjutnya.<br>
b. Footer:<br>
Tombol Kembali:<br>
Terletak di bagian bawah halaman, tombol ini dirancang untuk memudahkan pengguna kembali ke tampilan identitas apabila diperlukan.<br>
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/6e9557a5-45ee-4c5d-a29b-173c923dec42" alt="Gambar C3 tampilan poli reservasi baru" width="500">
</div>

### 4. Tampilan Tanggal Reservasi Baru

<p align="justify">
Tampilan ini dirancang untuk mempermudah pengguna dalam memilih tanggal reservasi sesuai kebutuhan mereka, dengan elemen-elemen sebagai berikut:<br>
a. Header<br>
Terletak di bagian atas halaman sebagai identitas utama sistem. Logo dan nama sistem ditampilkan dengan desain minimalis dan tipografi yang mudah dibaca. Header tetap menampilkan informasi hari dan tanggal secara realtime, memperbarui data secara otomatis sesuai dengan waktu pengguna.<br>
b. Bagian Utama (Main)<br>
Kotak Pilihan Tanggal: Berisi opsi tanggal yang tersedia untuk reservasi hingga 7 hari ke depan. Pengguna dapat memilih salah satu tanggal yang ditampilkan.<br>
Aksi Setelah Pemilihan Tanggal: Ketika pengguna mengklik tanggal yang diinginkan, sistem akan otomatis mengarahkan mereka ke tampilan waktu reservasi baru untuk melanjutkan proses.<br>
c. Footer<br>
Tombol Kembali: Terdapat tombol kembali di bagian footer, yang berfungsi untuk mengarahkan pengguna kembali ke tampilan identitas.<br>
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/8f56e8ee-72d6-4f60-923e-0c8493f4fe05" alt="Gambar C4 tampilan tanggal reservasi baru" width="500">
</div>

### 5. Tampilan Waktu Reservasi Baru

<p align="justify">
Tampilan ini dirancang untuk mempermudah pengguna dalam memilih waktu reservasi dengan antarmuka yang sederhana dan intuitif. Elemen-elemen yang disertakan adalah:<br>
a. Tambahan Bagian Utama<br>
Kotak Pilihan Waktu: Menampilkan pilihan waktu yang tersedia untuk reservasi. Setiap kotak waktu dirancang sebagai tombol interaktif; ketika diklik, pengguna akan diarahkan ke tampilan berikutnya, yaitu halaman "Dokter Reservasi Baru" yang menampilkan daftar dokter yang tersedia waktu itu.<br>
b. Footer<br>
Tombol Kembali: Berfungsi untuk mengarahkan pengguna ke tampilan identitas,<br>
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/c26b970c-f7f8-40d6-897e-ed899cd27199" alt="Gambar C5 tampilan waktu reservasi baru" width="500">
</div>

### 6. Tampilan Dokter Reservasi Baru

<p align="justify">
Tampilan ini dirancang untuk memudahkan pengguna memilih dokter yang tersedia atau sedang praktik, dengan elemen-elemen berikut:<br>
a. Tambahan Bagian Utama (Main):<br>
Kotak Pilihan Dokter: Menampilkan daftar dokter yang sedang praktik pada hari tersebut. Setiap kotak dilengkapi dengan nama dokter.<br>
Interaktivitas: Jika salah satu kotak dokter diklik, pengguna akan diarahkan ke tampilan Jenis Penjamin Reservasi Baru untuk melanjutkan proses reservasi.<br>
b. Footer:<br>
Tombol Kembali: Berfungsi mengarahkan pengguna kembali ke tampilan identitas.<br>
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/005cd0c3-d540-46a8-aa05-51c1f6fbf8dc" alt="Gambar C6 tampilan dokter reservasi baru" width="500">
</div>

### 7. Tampilan Jenis Penjamin Reservasi Baru

<p align="justify">
Tampilan jenis penjamin untuk reservasi baru dirancang sederhana dan user-friendly dengan elemen-elemen berikut:<br>
a. Tambahan Bagian Main<br>
Kolom Dropdown: Kolom ini memungkinkan pengguna untuk memilih jenis penjamin, seperti BPJS PBI, NON-PBI, UMUM. Jika pengguna mengklik salah satu opsi, sistem akan otomatis mengarahkan ke halaman reservasi baru, di mana pengguna dapat melanjutkan proses pendaftaran.<br>
b. Footer<br>
Tombol Kembali: Terletak di bagian bawah halaman, tombol ini memungkinkan pengguna untuk kembali ke tampilan.<br>
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/40448131-ff2b-4d5f-90ec-ce0c80a2a64b" alt="Gambar C7 tampilan jenis penjamin reservasi baru" width="500">
</div>

### 8. Tampilan Reservasi Baru

<p align="justify">
Tampilan untuk melakukan reservasi baru dirancang sederhana dan intuitif agar mudah digunakan oleh pengguna. Elemen-elemen utama dalam tampilan ini meliputi:<br>
a. Tambahan Bagian Main:<br>
Tombol Reservasi Baru: Tombol ini berfungsi untuk memulai proses reservasi. Jika tombol ini diklik, pengguna akan diarahkan ke tampilan detail reservasi, di mana informasi lebih lanjut dapat diisi atau diproses.<br>
b. Footer:<br>
Tombol Kembali: Tombol ini memungkinkan pengguna kembali ke tampilan identitas .<br>
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/a2aea633-9b55-4b63-b34c-993d80f1d50b" alt="Gambar C8 tampilan reservasi baru" width="500">
</div>

### 9. Tampilan Detail Reservasi

<p align="justify">
Tampilan detail reservasi dirancang untuk menampilkan informasi hasil pendaftaran reservasi baru secara jelas dan terstruktur. Elemen-elemen utama pada halaman ini meliputi:<br>
a. Hasil Pendaftaran Reservasi:<br>
Menampilkan detail informasi reservasi yang baru saja didaftarkan, seperti:<br>
Nomor Reservasi<br>
nomor RM<br>
Nama Pasien<br>
Nomor Antrean<br>
Tanggal Registrasi<br>
Lokasi Poli yang Dipilih<br>
Jenis Penjamin<br>
Dokter <br>
Status Reservasi<br>
Informasi ini disusun secara rapi untuk memastikan pengguna dapat dengan mudah memahami hasil reservasi mereka.<br>
b. Footer:<br>
Tombol Kembali: Mengarahkan pengguna kembali ke tampilan identitas.<br>
Tombol Selesai: Mengarahkan pengguna kembali ke tampilan home sebagai akhir dari proses reservasi.<br>
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/a6912dbc-c6c6-4c84-b81d-363d9a525105" alt="Gambar C9 tampilan detail reservasi" width="500">
</div>

### 10. Tampilan Informasi

<p align="justify">
Tampilan informasi dirancang untuk memberikan detail mengenai rumah sakit, seperti layanan yang tersedia, fasilitas unggulan, serta kontak yang dapat dihubungi. Informasi ini disusun secara terstruktur untuk memudahkan pengguna memahami konten yang disampaikan.<br>
Footer:<br>
Bagian bawah halaman dilengkapi tombol Kembali, yang berfungsi mengarahkan pengguna kembali ke tampilan home<br>
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/3c35e783-de9a-4ef9-a0c2-f447c6ff2e24" alt="Gambar C10 tampilan informasi" width="500">
</div>

### 11. Tampilan Bahasa

<p align="justify">
Mengarahkan pengguna ke halaman pengaturan bahasa, di mana terdapat dua tombol untuk memilih bahasa, yaitu Indonesia dan Inggris, sesuai preferensi pengguna saat pendaftaran.<br>
Footer:<br>
Bagian bawah halaman dilengkapi tombol Kembali, yang berfungsi mengarahkan pengguna kembali ke tampilan home<br>
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/8de1eb11-5deb-4f0d-8ab4-b5b349c04138" alt="Gambar C11 tampilan bahasa" width="500">
</div>

### 12. Tampilan Jadwal Dokter

<p align="justify">
Halaman jadwal dokter menampilkan informasi jadwal dokter dalam format yang informatif dan menarik.<br>
Footer:<br>
Bagian bawah halaman dilengkapi tombol Kembali, yang berfungsi mengarahkan pengguna kembali ke tampilan home<br>
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/8ef9021d-9e42-4da9-89e6-29b6e8b7a8a0" alt="Gambar C12 tampilan jadwal dokter" width="500">
</div>

### 13. Tampilan Feedback

<p align="justify">
Pada halaman feedback, pengguna dapat memberikan masukan melalui elemen berikut:<br>
Kolom Nama: Untuk mengisi nama pengguna.<br>
Kolom Email: Untuk mengisi alamat email pengguna.<br>
Kolom Pesan: Untuk menuliskan masukan atau komentar pengguna.<br>
Tombol Kirim: Berfungsi untuk mengirimkan masukan yang telah diisi.<br>
Footer:<br>
Bagian bawah halaman dilengkapi tombol Kembali, yang berfungsi mengarahkan pengguna kembali ke tampilan home<br>
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/14567347-aea4-4bcd-b562-95bf37bac936" alt="Gambar C13 tampilan feedback" width="500">
</div>

### 14. Tampilan Bantuan

<p align="justify">
Pada halaman bantuan, pengguna disajikan beberapa pilihan bantuan untuk memandu mereka menggunakan sistem. Pilihan ini mencakup informasi tentang cara menggunakan fitur, mengatasi masalah umum<br>
Footer:<br>
Bagian bawah halaman dilengkapi tombol Kembali, yang berfungsi mengarahkan pengguna kembali ke tampilan home<br>
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/c676657f-b319-43e6-955e-828b258b8fce" alt="Gambar C14 tampilan bantuan" width="500">
</div>

### 15. Tampilan Tentang

<p align="justify">
Halaman "Tentang" dirancang untuk memberikan informasi singkat dan jelas mengenai sistem, meliputi:<br>
Nama Aplikasi Sistem: Nama resmi dari aplikasi yang digunakan.<br>
Versi Sistem: Informasi tentang versi aplikasi yang saat ini berjalan.<br>
Developer: Pihak atau tim pengembang sistem.<br>
Footer:<br>
Bagian bawah halaman dilengkapi tombol Kembali, yang berfungsi mengarahkan pengguna kembali ke tampilan home<br>
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/c2b13edb-5d79-4775-917b-db4eaeacdfb1" alt="Gambar C15 tampilan tentang" width="500">
</div>
