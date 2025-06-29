# Kalkulator PPh21 TER (Tarif Efektif Rata-rata)

Kalkulator sederhana untuk menghitung PPh21 TER (Tarif Efektif Rata-rata) berdasarkan status, jumlah tanggungan, dan penghasilan bruto bulanan.  
Dibangun dengan **HTML, Tailwind CSS, dan JavaScript**. Input penghasilan otomatis terformat rupiah.

## ✨ Fitur

- Input status pegawai: **K (Kawin)** & **TK (Tidak Kawin)**
- Input jumlah tanggungan (0-3)
- Input penghasilan bruto bulanan dengan format rupiah otomatis
- Perhitungan otomatis kategori TER, bracket, tarif, dan pajak terutang
- Hasil tampil dalam format rupiah
- Penjelasan status K/TK dan tanggungan
- Tampilan responsif dan modern (Tailwind CSS)
- Tidak perlu backend/server

## 🚀 Demo

Cukup buka file `index.html` di browser!

## 📦 Cara Pakai

1. **Clone atau download repo ini**
2. Buka file `index.html` di browser
3. Isi data:
   - Pilih status (**TK** = Tidak Kawin, **K** = Kawin)
   - Pilih jumlah tanggungan (0-3)
   - Masukkan penghasilan bruto bulanan (otomatis terformat rupiah)
4. Klik **Hitung**
5. Hasil perhitungan akan muncul di bawah form

## 📋 Contoh

<img width="591" alt="image" src="https://github.com/user-attachments/assets/548add78-b626-43c8-8b06-340884728c8b" />


## 📖 Penjelasan Status

- **K (Kawin):** Pegawai yang sudah menikah
- **TK (Tidak Kawin):** Pegawai yang belum menikah
- **Tanggungan:** Jumlah anak/keluarga yang menjadi beban pajak (maksimal 3)

## 🛠️ Teknologi

- [Tailwind CSS](https://tailwindcss.com/) (CDN)
- JavaScript Vanilla (tanpa framework)
- HTML5

## 📄 Lisensi

MIT License

> Dibuat untuk memudahkan simulasi perhitungan PPh21 TER bagi karyawan, HR, dan siapa saja yang ingin belajar pajak Indonesia.
