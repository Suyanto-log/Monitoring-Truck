# 🚛 Monitoring Truck
Bismillah
Pertaman-tama Saya masih newbie di web programming ini, dan ini adalah project pertama saya yg saya coba share, mohon bimbingannya dan masukannya.
Proyek sistem pemantauan dan pencatatan data truk untuk mempermudah proses pendataan, pelacakan status, dan pelaporan. Aplikasi ini berbasis web sederhana yang dirancang agar mudah diakses dan dioperasikan oleh tim lapangan maupun administrasi.

**🔗 Demo Aplikasi:** https://monitoring-truck.vercel.app

---

## 📋 Deskripsi Proyek
Proyek ini dikembangkan dalam 2 tahap utama penyimpanan data. Saat ini baru menyelesaikan uji coba Tahap 1, dan sedang bergerak menuju Tahap 2.

### 🚀 Tahap Pengembangan
#### ✅ Tahap 1: Koneksi ke Google Sheets (Sedang Berjalan)
Menggunakan Google Sheets sebagai basis data sementara. Sudah berhasil terhubung dan melakukan uji coba input data.
- **Fitur yang sudah berfungsi:**
  - Form Register ✅
  - Form TAT ✅
- **Status:** Koneksi berhasil, data masuk ke spreadsheet dengan benar.
- **Yang perlu disempurnakan:** Validasi input, tampilan, dan aturan pengisian pada kedua form tersebut.

#### ⏳ Tahap 2: Migrasi ke MySQL (Rencana Selanjutnya)
Mengubah penyimpanan data dari Google Sheets ke Database MySQL agar lebih aman, cepat, dan mampu menangani data dalam jumlah besar.
- **Rencana:** Menulis ulang logika koneksi, membuat struktur tabel database, dan mengubah metode pengiriman data.

---

## 📝 Daftar Fitur / Form
Berikut daftar fitur yang sudah ada, sedang disempurnakan, dan yang akan dibuat:

1. **Form Register** ✅ *(Sudah jadi) — Tahap Penyempurnaan*
   > Formulir pendaftaran data truk dan identitas pengemudi. Perlu diperbaiki tampilan dan validasi data.

2. **Form TAT** ✅ *(Sudah jadi) — Tahap Penyempurnaan*
   > Pencatatan waktu proses dan siklus layanan. Perlu dirapikan alur input datanya.

3. **Form Status** ⏳ *(Belum Dibuat)*
   > Memantau status terkini posisi atau kondisi truk.

4. **Form Putaway** ⏳ *(Belum Dibuat)*
   > Pencatatan proses penempatan barang di gudang/tujuan.

5. **Form Pallet** ⏳ *(Belum Dibuat)*
   > Pencatatan jumlah dan kondisi penggunaan pallet.

6. **Form Report** ⏳ *(Belum Dibuat)*
   > Halaman untuk menampilkan, menyaring, dan mencetak laporan data.

---

## 💻 Teknologi yang Digunakan
- **HTML5** — Struktur halaman
- **CSS** — Tampilan antarmuka
- **JavaScript** — Logika, pengambilan data, dan koneksi API
- **Google Sheets API** — Penyimpanan data tahap awal
- *(Akan datang)* **MySQL & PHP/Node.js** — Penyimpanan data tahap akhir

---

## 🤝 Cara Berkontribusi
Proyek ini terbuka untuk siapa saja yang ingin membantu pengembangan, baik itu memperbaiki kode, menambah fitur baru, maupun memperindah tampilan.

Hal yang paling kami butuhkan saat ini:
- Penyempurnaan validasi dan tampilan **Form Register & TAT**.
- Bantuan perancangan struktur database untuk migrasi ke **MySQL**.
- Pembuatan fitur baru: Status, Putaway, Pallet, dan Report.
- Perbaikan desain agar lebih responsif di HP maupun Komputer.

Silakan lihat daftar *Issues* untuk mengetahui apa saja yang sedang dikerjakan atau yang belum selesai.

---

## 📜 Lisensi
Proyek ini menggunakan Lisensi MIT — bebas digunakan, dimodifikasi, dan disebarluaskan selama mencantumkan sumber aslinya.

MIT License

Copyright (c) 2024 Monitoring Truck Project

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
