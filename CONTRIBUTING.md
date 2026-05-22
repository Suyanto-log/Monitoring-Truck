# Panduan Berkontribusi
Terima kasih sudah tertarik untuk berkontribusi pada proyek **Sistem Monitoring & Pelaporan Gudang** ini! Panduan ini berisi aturan dan langkah-langkah agar kita bisa bekerja sama dengan rapi, aman, dan efisien.

## 📂 Tentang Proyek
Proyek ini adalah sistem berbasis web untuk memantau operasional gudang, meliputi:
- Pencatatan kendaraan masuk (inbound) dan keluar (outbound)
- Manajemen stok dan penempatan barang (palet/rak)
- Pembuatan laporan ringkasan harian dan per shift
- Pencatatan data kontainer, jumlah karton, dan pergerakan barang

File utama sistem: `index.html`, `report.html`, `pallet.html`, `putaway.html`, `register.html`, `status.html`, `tat.html`, `user.html`

---

## 🚀 Cara Berkontribusi
Ada 3 cara utama yang bisa kamu lakukan:

### 1. Melaporkan Masalah / Fitur Baru (Buat Issue)
Jika kamu menemukan kesalahan, ketidaksesuaian data, atau punya ide fitur baru, silakan buat **Issue** baru dengan aturan:
- Gunakan judul yang jelas dan singkat
- Contoh: *"Report: Belum bisa tampilkan ringkasan inbound/outbound per kategori"*
- Isi deskripsi lengkap:
  - Apa yang terjadi / apa yang dibutuhkan
  - Langkah mengulangi masalah (jika ada kesalahan)
  - Hasil yang diharapkan
  - Sertakan tangkapan layar jika perlu

### 2. Memperbaiki Kode atau Menambah Fitur (Pull Request)
1. **Ambil salinan proyek ini** ke akun kamu
2. Buat cabang baru (`branch`) dengan nama jelas:
   - `fitur/laporan-ringkasan` → untuk fitur baru
   - `perbaikan/data-stok` → untuk perbaikan kesalahan
3. Lakukan perubahan kode sesuai kebutuhan
4. Pastikan sistem masih berjalan normal:
   - Cek tampilan di semua halaman (`report.html`, `pallet.html`, dll)
   - Pastikan perhitungan angka dan data akurat
5. Kirimkan **Pull Request** ke cabang utama (`main` / `master`)
6. Tunggu peninjauan dan umpan balik dari pengelola proyek

### 3. Meningkatkan Dokumentasi
Kamu juga bisa membantu melengkapi atau memperjelas isi `README.md` maupun panduan ini agar lebih mudah dipahami tim lain.

---

## ✅ Aturan Penulisan & Kode
- **Nama File**: Gunakan huruf kecil semua, tanpa spasi, gunakan tanda hubung jika perlu (contoh: `data-laporan.html`)
- **Struktur Halaman**: Pertahankan keseragaman tampilan antar halaman
- **Komentar**: Berikan keterangan singkat pada bagian kode yang rumit atau rumus perhitungan
- **Data**: Pastikan semua perhitungan jumlah barang, kontainer, dan palet sesuai logika operasional gudang

---

## ⚠️ Hal yang Perlu Diperhatikan
- Jangan mengubah struktur nama file yang sudah ada kecuali sudah disepakati bersama
- Jangan menghapus fitur yang masih digunakan tim operasional
- Selalu tes hasil perubahan sebelum dikirimkan

---

Terima kasih atas kontribusimu untuk membuat sistem ini semakin baik dan bermanfaat! 🚛📦
