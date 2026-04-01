# 🏅 SportSpace - Integrated Sports Equipment Management

<p align="center">
  <img src="https://img.shields.io/github/languages/top/alfianwidhi-web/sportspace?style=for-the-badge&color=blue" alt="Top Language">
  <img src="https://img.shields.io/github/last-commit/alfianwidhi-web/sportspace?style=for-the-badge&color=green" alt="Last Commit">
  <img src="https://img.shields.io/github/repo-size/alfianwidhi-web/sportspace?style=for-the-badge&color=orange" alt="Repo Size">
  <img src="https://img.shields.io/github/license/alfianwidhi-web/sportspace?style=for-the-badge&color=red" alt="License">
</p>

<p align="center">
  <strong>Solusi manajemen peminjaman alat olahraga yang efisien, transparan, dan modern.</strong>
  <br />
  <a href="#-fitur-utama">Fitur Utama</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-instalasi">Instalasi</a> •
  <a href="#-kontribusi">Kontribusi</a>
</p>

---

## 📖 Deskripsi Proyek

**SportSpace** adalah platform *Single Page Application* (SPA) yang dirancang untuk mengelola ekosistem peminjaman peralatan olahraga. Dibangun dengan fokus pada pengalaman pengguna (UX) yang bersih dan fungsionalitas admin yang lengkap. 

Aplikasi ini tidak hanya menangani peminjaman, tetapi juga otomatisasi perhitungan denda, manajemen stok alat, hingga sistem pelaporan yang siap cetak (print-ready).

---

## ✨ Fitur Utama

### 🛠️ Untuk Administrator (Admin Panel)
* **Real-time Statistics:** Pantau total alat, alat yang sedang dipinjam, dan status keterlambatan melalui Dashboard.
* **Inventory Management:** Kelola (Tambah, Edit, Hapus) stok peralatan olahraga.
* **Approval System:** Terima atau tolak permintaan peminjaman anggota dalam satu klik.
* **Automatic Fine System:** Sistem otomatis menghitung denda berdasarkan aturan:
    $$Denda = Hari \space Terlambat \times Tarif \space Denda$$
* **Exportable Reports:** Halaman laporan yang dioptimalkan untuk cetak fisik (Cetak Bukti).

### 👤 Untuk Anggota (Member Area)
* **Interactive Search:** Cari alat olahraga berdasarkan kategori dengan cepat.
* **Borrowing History:** Pantau status peminjaman (Menunggu, Disetujui, Kembali).
* **User Profile:** Manajemen akun pribadi yang aman.

---

## 📸 Preview Tampilan

| Landing Page | Dashboard Stats |
|---|---|
| <img src="https://via.placeholder.com/600x300?text=SportSpace+Landing+Page" width="100%"> | <img src="https://via.placeholder.com/600x300?text=Dashboard+Visuals" width="100%"> |

| Admin Management | Print-Ready Report |
|---|---|
| <img src="https://via.placeholder.com/600x300?text=Inventory+Control" width="100%"> | <img src="https://via.placeholder.com/600x300?text=Print+Invoice+Preview" width="100%"> |

---

## 💻 Tech Stack

Proyek ini menggunakan kombinasi teknologi modern untuk performa maksimal:

* **Frontend:** [Tailwind CSS](https://tailwindcss.com/) (Utility-first CSS framework untuk UI yang responsif).
* **Icons:** [Font Awesome 6.4.0](https://fontawesome.com/) (Set ikon premium untuk navigasi).
* **Fonts:** [Inter](https://fonts.google.com/specimen/Inter) (Tipografi modern untuk keterbacaan tinggi).
* **Logic:** Vanilla JavaScript (ES6+) untuk manajemen state dan navigasi halaman.

---

## ⚙️ Instalasi

Ikuti langkah-langkah berikut untuk menjalankan proyek di komputer lokal Anda:

1.  **Clone Repositori**
    ```bash
    git clone [https://github.com/alfianwidhi-web/sportspace.git](https://github.com/alfianwidhi-web/sportspace.git)
    ```
2.  **Masuk ke Direktori**
    ```bash
    cd sportspace
    ```
3.  **Jalankan Aplikasi**
    Karena menggunakan Tailwind CDN, Anda tidak perlu `npm install`. Cukup buka `index.html` di browser Anda:
    ```bash
    # Jika menggunakan VS Code (Live Server)
    code .
    ```

---

## 🗺️ Roadmap Pengembangan
- [x] Desain UI Responsif dengan Tailwind.
- [x] Sistem Navigasi Single Page (SPA).
- [ ] Integrasi Database (Firebase/Supabase/MySQL).
- [ ] Fitur Notifikasi WhatsApp untuk pengingat pengembalian.
- [ ] Support Multi-language (Indonesia/Inggris).

---

## 🤝 Kontribusi

Kontribusi adalah hal yang membuat komunitas open source menjadi luar biasa.
1. Fork Proyek ini.
2. Buat Fitur Branch (`git checkout -b fitur/FiturKeren`).
3. Commit Perubahan (`git commit -m 'Menambahkan fitur keren'`).
4. Push ke Branch (`git push origin fitur/FiturKeren`).
5. Buka Pull Request.

---

## 📄 Lisensi
Didistribusikan di bawah Lisensi **MIT**. Lihat file `LICENSE` untuk detail lebih lanjut.

---

<p align="center">
  Dibuat dengan semangat oleh <a href="https://github.com/alfianwidhi-web">Alfian Widhi</a> 🇮🇩
</p>
