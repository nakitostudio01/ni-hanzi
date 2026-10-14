# Kebijakan Privasi (Privacy Policy) - Nǐ Hànzì (你汉字)

**Terakhir Diperbarui:** 14 Oktober 2026  
**Pengembang:** Nakito Studio / Nǐ Hànzì Team  
**Kontak Email Dukungan:** nakitostudio01@gmail.com  
**Aplikasi:** Nǐ Hànzì (Belajar Bahasa Mandarin & HSK 1–6)  
**ID Paket (Package Name):** `com.nakito.nihanzi`

---

## 1. Pendahuluan

Selamat datang di **Nǐ Hànzì** ("Aplikasi"). Kami sangat menghargai dan menghormati privasi Anda. Kebijakan Privasi ini menjelaskan bagaimana kami mengumpulkan, menggunakan, menyimpan, dan melindungi informasi Anda saat Anda menggunakan aplikasi seluler kami.

Dengan mengunduh, memasang, atau menggunakan Nǐ Hànzì, Anda menyetujui praktik yang dijelaskan dalam Kebijakan Privasi ini. Jika Anda tidak menyetujui kebijakan ini, harap untuk tidak menggunakan aplikasi kami.

---

## 2. Informasi yang Kami Kumpulkan

### A. Informasi yang Diberikan Pengguna Secara Sukarela

- **Akun Google (Google Sign-In):** Jika Anda memilih untuk masuk menggunakan akun Google, kami menerima informasi dasar profil publik Anda dari Google, termasuk:
  - Alamat email
  - Nama tampilan (_Display Name_)
  - ID Pengguna Google (_User ID/UID_)
  - Foto profil publik (hanya untuk ditampilkan pada antarmuka aplikasi)
- **Status Pembelian Dalam Aplikasi (In-App Purchases):** Jika Anda melakukan pembelian lisensi (Master Pro atau Starter) melalui Google Play Billing, sistem mencatat data audit transaksi:
  - Nomor Pesanan (_Order ID_) dari Google Play
  - Token Pembelian (_Purchase Token_)
  - Waktu dan tanggal transaksi
  - Versi aplikasi saat transaksi dilakukan
  - _Catatan:_ Kami **TIDAK PERNAH** mengumpulkan atau menyimpan data kartu kredit, rekening bank, atau informasi penagihan keuangan Anda. Semua pemrosesan pembayaran dilakukan secara aman dan langsung oleh **Google Play Store**.

### B. Data Progres Belajar & Pencadangan (Google Drive)

- **Progres Lokal:** Data kosakata yang telah dihafal, status stempel (_known / learning_), dan riwayat belajar disimpan secara lokal di perangkat Anda menggunakan database SQLite internal.
- **Cadangan Google Drive (Opsional):** Jika Anda menggunakan fitur pencadangan cloud, aplikasi akan menyimpan salinan berkas data progres belajar ke Google Drive pribadi Anda.
  - **Ruang Lingkup Terbatas (_drive.appdata_):** Aplikasi hanya memiliki izin untuk mengakses folder khusus aplikasi (_Application Data Folder_).
  - **Jaminan Privasi:** Aplikasi **TIDAK MEMILIKI AKSES** dan **TIDAK BISA** melihat, membaca, mengedit, atau menghapus foto, dokumen, berkas spreadsheet, atau file pribadi lainnya yang ada di Google Drive Anda.

### C. Data Teknis & Jaringan yang Dikumpulkan Otomatis

- **Layanan Iklan (Google AdMob):** Untuk pengguna versi gratis, aplikasi dapat menampilkan iklan melalui Google AdMob SDK. Google AdMob dapat mengumpulkan pengidentifikasi perangkat (seperti _Google Advertising ID_), data diagnostik performa iklan, dan lokasi umum kasar (tingkat negara/kota) sesuai dengan kebijakan privasi Google.
- **Sintesis Suara (Text-to-Speech / TTS):** Pengucapan audio kosakata Mandarin diproses menggunakan mesin TTS bawaan sistem Android (Google TTS). Tidak ada data rekaman suara pengguna yang diambil atau dikirim ke server kami.

---

## 3. Cara Kami Menggunakan Informasi Anda

Kami menggunakan informasi yang dikumpulkan semata-mata untuk:

1. Menyediakan, mengoperasikan, dan memelihara fitur pembelajaran kartu flashcard HSK.
2. Memvalidasi dan memulihkan hak akses lisensi berbayar (Master Pro / Bebas Iklan) antar-perangkat menggunakan akun Google Anda.
3. Memungkinkan Anda mencadangkan dan memulihkan riwayat progres belajar pribadi.
4. Menampilkan iklan yang relevan pada versi gratis guna mendukung pemeliharaan aplikasi.
5. Memberikan layanan bantuan pelanggan (_customer support_) jika Anda mengalami kendala transaksi atau bug.

---

## 4. Berbagi Data kepada Pihak Ketiga

Kami **TIDAK AKAN PERNAH** menjual, menyewakan, atau memperdagangkan data pribadi Anda kepada pihak ketiga mana pun untuk tujuan pemasaran. Data Anda hanya diproses oleh penyedia layanan infrastruktur terpercaya berikut:

- **Google Play Services & Google Play Billing:** Untuk autentikasi dasar dan pemrosesan pembayaran lisensi resmi.
- **Google Firebase (Firebase Auth & Cloud Firestore):** Untuk manajemen akun pengguna dan pencatatan riwayat lisensi secara aman terenkripsi.
- **Google Drive API:** Untuk transmisi data cadangan langsung antara perangkat Anda dan akun Google Drive pribadi Anda.
- **Google AdMob:** Untuk penayangan iklan pada akun versi gratis.

Seluruh layanan pihak ketiga di atas beroperasi di bawah standar keamanan dan regulasi privasi global Google ([Kebijakan Privasi Google](https://policies.google.com/privacy)).

---

## 5. Penyimpanan & Keamanan Data

- Komunikasi antara aplikasi dengan layanan Google (Firebase, Drive, Play Store) selalu dilindungi dengan enkripsi standar industri **HTTPS / TLS 1.3**.
- Data progres belajar lokal disimpan dalam ruang penyimpanan privat aplikasi (_internal sandbox storage_) di perangkat Anda yang tidak dapat diakses oleh aplikasi lain tanpa izin root.

---

## 6. Hak Pengguna & Penghapusan Data (Data Deletion Policy)

Sesuai dengan ketentuan Google Play Store, kami memberikan kendali penuh kepada pengguna terhadap data mereka:

- **Menghapus Progres Belajar Lokal:** Anda dapat kapan saja mereset data hafalan langsung dari aplikasi melalui menu _Pengaturan > Keluar Akun > Pilih "Hapus & Keluar"_ atau tombol _Reset Progres Belajar_.
- **Menghapus Data Cadangan Google Drive:** Anda dapat menghapus data cadangan langsung dari aplikasi atau melalui setelan Google Drive Anda pada menu _Kelola Aplikasi yang Terhubung_.
- **Permohonan Penghapusan Akun & Data Cloud (Firestore):** Jika Anda ingin menghapus seluruh data akun dan riwayat catatan lisensi dari Cloud Firestore kami, Anda dapat mengirimkan email permohonan ke **nakitostudio01@gmail.com** dengan subjek _"Permohonan Penghapusan Data Akun Nǐ Hànzì"_. Kami akan memproses penghapusan data Anda dalam waktu 7 hari kerja.

---

## 7. Privasi Anak-Anak (Children's Privacy / COPPA)

Aplikasi kami dirancang untuk tujuan edukasi umum bagi siapa saja yang ingin belajar bahasa Mandarin. Kami tidak secara sadar mengumpulkan informasi identitas pribadi dari anak-anak di bawah usia 13 tahun. Jika Anda adalah orang tua atau wali dan mengetahui bahwa anak Anda telah memberikan data pribadi kepada kami tanpa persetujuan Anda, silakan hubungi kami agar kami dapat segera menghapus data tersebut.

---

## 8. Izin Perangkat Android yang Digunakan

- `android.permission.INTERNET`: Untuk memuat data lisensi Firebase, pencadangan Google Drive, dan iklan AdMob.
- `android.permission.ACCESS_NETWORK_STATE`: Untuk mendeteksi ketersediaan koneksi internet.
- `com.android.vending.BILLING`: Untuk memproses pembelian dalam aplikasi Google Play.
- `android.permission.WAKE_LOCK`: Untuk memastikan kelancaran pemutaran audio pelafalan TTS saat kartu flashcard dibuka.

---

## 9. Perubahan pada Kebijakan Privasi Ini

Kami dapat memperbarui Kebijakan Privasi ini dari waktu ke waktu untuk menyesuaikan dengan fitur baru atau regulasi hukum yang berlaku. Setiap perubahan akan diberitahukan dengan memperbarui tanggal "Terakhir Diperbarui" di bagian atas halaman ini.

---

## 10. Hubungi Kami

Jika Anda memiliki pertanyaan, saran, atau keluhan mengenai Kebijakan Privasi ini, silakan hubungi kami melalui:

- **Email Dukungan:** [nakitostudio01@gmail.com](mailto:nakitostudio01@gmail.com)
- **Pengembang:** Nakito Studio
- **Repositori Resmi:** [https://github.com/nakitostudio01/ni-hanzi](https://github.com/nakitostudio01/ni-hanzi)
