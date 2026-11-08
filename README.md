# Tugas Kuliah Pemrograman Web 1 - Properti CSS (Modul XI)
**Program Studi Teknik Informatika S-1 | Fakultas Ilmu Komputer | Universitas Pamulang**

---

## Identitas Mahasiswa
- **Nama Mahasiswa:** Hadi Sulaiman
- **NIM:** 241011402572
- **Kelas:** 05TPLM003
- **Mata Kuliah:** Pemrograman Web 1
- **Topik:** Modul XI : Cascading Style Sheet (CSS) - Travel Wisata (*NusantaraVenture*)

---

## Parameter Penugasan Berdasarkan NIM: 241011402572

| Parameter | Nilai / Digit | Aturan Implementasi |
| :--- | :---: | :--- |
| **Digit Terakhir NIM** | **2** | **Tema:** Travel Wisata (*NusantaraVenture*)<br>**Tata Letak:** Dua Kolom (*Two-Column Layout*)<br>**Tantangan Tambahan:** Galeri Destinasi dengan Filter Kategori & Kartu Interaktif |
| **Digit ke-1 (dari 5 akhir)** | **0 &rarr; 5** | `font-size: 25px` (Judul Utama `h1.judul-utama`)<br>`margin: 25px auto` (Jarak Antarseksi Utama) |
| **Digit ke-2 (dari 5 akhir)** | **2** | Variasi Font Tambahan = 2 (Total 4 Font: *Poppins*, *Playfair Display*, *Segoe UI*, *Courier New*)<br>Ketebalan Border Utama = `2px` (Solid, Dashed, Dotted) |
| **Digit ke-3 (dari 5 akhir)** | **5** | Minimal 5 elemen teks bold (*Brand*, *Judul*, *Kartu Destinasi*, *Harga*, *Tombol Aksi*) |
| **Digit ke-4 (dari 5 akhir)** | **7** | Minimal 7 elemen teks italic (*Tagline Hero*, *Deskripsi Singkat*, *Kutipan Tur*, *Catatan Promo*, dsb.) |
| **Digit ke-5 (dari 5 akhir)** | **2** | Minimal 2 elemen perataan teks khusus (*Center* pada Hero & Heading, *Justify* pada Paragraf, *Right* pada Metadata) |
| **Penyematan CSS** | **3 Metode** | **Linking (External CSS):** `style.css`<br>**Embedding (Internal CSS):** `<style>` pada `destinasi.html`<br>**Inline CSS:** Atribut `style="..."` pada badge promo & styling spesifik |

---

## Struktur Berkas Proyek

```
Tugas-Kuliah-Pemrograman-Web-1_Properti-CSS/
├── index.html                      # Halaman Beranda Utama (2-Kolom Layout, Hero Banner)
├── destinasi.html                  # Halaman Galeri Destinasi (Embedding Internal CSS)
├── kontak.html                     # Halaman Formulir Reservasi & Kontak (2-Kolom Layout)
├── style.css                       # External CSS Global (Aturan Formula NIM 241011402572)
├── images/                         # Aset Fotografi Destinasi Wisata
│   ├── hero-marine.jpg
│   ├── raja-ampat.jpg
│   ├── bromo.jpg
│   ├── labuan-bajo.jpg
│   ├── kawah-ijen.jpg
│   ├── nusa-penida.jpg
│   ├── cappadocia.jpg
│   └── kyoto.jpg
├── laporan/                        # Dokumen Laporan Praktikum Resmi
│   ├── Laporan_Praktikum_Modul_11_241011402572.pdf  # PDF Resmi (Tepat 6 Halaman, Bebas Em-Dash)
│   ├── laporan_praktikum_modul11.html               # Sumber HTML Laporan
│   ├── logo_unpam.png                               # Logo UNPAM Resolusi Tinggi
│   ├── Modul_11_CSS.pdf                             # Panduan Modul Resmi UNPAM
│   └── screenshots/                                 # Tangkapan Layar Output Nyata
│       ├── ss_tugas_index.png
│       ├── ss_tugas_destinasi.png
│       └── ss_tugas_kontak.png
├── percobaan/                      # Latihan Modul XI (CSS Fundamentals)
│   ├── latihan1_font.html                           # Percobaan 1: Tipografi & Perataan Teks
│   ├── latihan2_box_border.html                     # Percobaan 2: Box Model Margin & Border
│   ├── latihan3_linking_embedding_inline.html       # Percobaan 3: Linking, Embedding & Inline
│   └── eksternal.css                                # Lembar Gaya Percobaan 3
└── README.md                       # Dokumentasi Komprehensif Proyek
```

---

## Cara Menjalankan Proyek
1. Clone repositori ini:
   ```bash
   git clone https://github.com/Xez0/Tugas-Kuliah-Pemrograman-Web-1_Properti-CSS.git
   ```
2. Buka berkas `index.html` pada peramban web modern (Google Chrome, Mozilla Firefox, Microsoft Edge, dll).
3. Untuk melihat berkas laporan praktikum siap cetak, buka berkas `laporan/Laporan_Praktikum_Modul_11_241011402572.pdf`.
