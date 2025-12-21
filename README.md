# 📘 Template LaTeX Laporan Tugas Akhir

*Program Sarjana Terapan Teknologi Rekayasa Perangkat Lunak – Politeknik Negeri Banyuwangi*

Template ini dirancang untuk mempermudah penulisan Proposal dan Laporan Tugas Akhir bagi mahasiswa D3 dan D4 Politeknik Negeri Banyuwangi. Template ini memastikan keseragaman format sesuai Pedoman Mutu Tugas Akhir Poliwangi 2023, efisiensi penulisan, serta kemudahan kolaborasi dan pengelolaan dokumen melalui Git atau Overleaf.

---

## 📁 Struktur Proyek

```
Template-LaTeX-Laporan-Tugas-Akhir
├── CHANGELOG                         # Catatan perubahan
├── LICENSE                           # Lisensi proyek        
├── Project                           # Folder proyek    
│   ├── a0-identitas.tex              # Isi identitas laporan (WAJIB DIISI)
│   ├── a1-database.hyphenate.tex     # Database untuk hyphenation
│   ├── a2-abstrak.tex                # Abstrak dalam Bahasa Indonesia  
│   ├── a3-abstract.tex               # Abstrak dalam Bahasa Inggris
│   ├── a4-persembahan.tex            # Persembahan
│   ├── a5-katapengantar.tex          # Kata Pengantar
│   ├── a6-daftarsingkatan.tex        # Daftar Singkatan
│   ├── a7-pustaka.bib                # Daftar pustaka dalam format BibTeX
│   ├── a8-lampiran.tex               # Lampiran
│   ├── a9-motto.tex                  # Motto (opsional)
│   ├── b1-bab1.tex                   # BAB 1 - Pendahuluan
│   ├── b2-bab2.tex                   # BAB 2 - Tinjauan Pustaka
│   ├── b3-bab3.tex                   # BAB 3 - Metode Penelitian
│   ├── b4-bab4.tex                   # BAB 4 - Hasil dan Pembahasan
│   ├── b5-bab5.tex                   # BAB 5 - Kesimpulan dan Saran
│   ├── b6-bab6.tex                   # BAB 6 - Tutorial LaTeX (opsional)
│   ├── gambar                        # Folder untuk menyimpan gambar
│   ├── kode                          # Folder untuk menyimpan kode program
│   ├── laporan.pdf                   # Hasil kompilasi laporan
│   ├── laporan.tex                   # File utama untuk kompilasi laporan
│   └── untouch                       # Folder untuk menyimpan file yang tidak perlu diubah
│       ├── xx-daftar.tex
│       ├── xx-daftarpustaka.tex
│       ├── xx-pengesahan.tex
│       ├── xx-pernyataan.tex
│       ├── xx-pernyataan-poliwangi.tex
│       ├── xx-persetujuan-proposal.tex
│       ├── xx-persetujuan-ujian.tex
│       ├── xx-preambles.tex
│       ├── xx-sampul-laporan.tex
│       ├── xx-sampul-proposal.tex
│       ├── xx-sampuldalam-laporan.tex
│       └── xx-sampuldalam-proposal.tex
└── README.md                         # Dokumen ini
```

---

## 🧩 Fitur Utama

✅ Format sesuai **Pedoman Mutu Tugas Akhir Poliwangi 2023**

✅ Mendukung kompilasi proposal & laporan akhir

✅ **Warna cover otomatis** sesuai program studi

✅ Contoh gambar, kode program, persamaan, tabel, dan sitasi

✅ Dukungan referensi otomatis (BibTeX dengan APA Style)

✅ Dokumentasi & tutorial lengkap

✅ Kompatibel dengan TexStudio dan Overleaf

---

## 🎨 Warna Cover Per Program Studi

Template ini mendukung warna cover yang berbeda sesuai program studi Poliwangi. Edit file `a0-identitas.tex` dan ubah nilai `\covercolor`:

| Program Studi | Warna Cover | Kode RGB |
|--------------|-------------|----------|
| Teknik Informatika | Kuning | 255,215,0 |
| **Teknologi Rekayasa Perangkat Lunak** | **Kuning** | **255,215,0** |
| Teknik Sipil | Biru Tua | 0,0,128 |
| Teknik Mesin | Merah | 255,0,0 |
| Manajemen Bisnis Pariwisata | Orange | 255,127,0 |
| Agribisnis | Hijau Tua | 0,159,60 |
| Teknologi Pengolahan Hasil Ternak | Coklat Tua | 150,75,0 |
| Teknik Manufaktur Kapal | Biru Muda | 0,128,255 |

**Contoh untuk Teknologi Rekayasa Perangkat Lunak:**
```latex
\providecommand{\covercolor}{255,215,0} % RGB untuk warna kuning
```

---

## 📐 Format Penulisan (Poliwangi 2023)

- **Margin:** Kiri 3cm, Atas 2cm, Kanan 2cm, Bawah 2cm
- **Font:** Times New Roman 12pt
- **Spasi:** 1.5 (isi), 1.0 (tabel/gambar)
- **Indentasi:** First Line 1.25cm
- **Penomoran Bab:** BAB 1, BAB 2, BAB 3 (angka, bukan romawi)
- **Section:** 1.1, 1.2, 2.1, 2.2 (sesuai bab)
- **Persamaan:** 2.3 (tanpa kurung)
- **Referensi:** APA Style, jurnal 10 tahun terakhir (D4)

---

## 🖥️ Panduan Penggunaan

### Opsi 1: Overleaf (Direkomendasikan - Mudah & Online)

1. **Upload ke Overleaf**:
   - Buka [Overleaf](https://www.overleaf.com/)
   - Klik **New Project** → **Upload Project**
   - Upload ZIP dari repository ini
   - Atau import langsung dari GitHub

2. **Compile**:
   - Overleaf akan otomatis compile
   - File utama: `Project/laporan.tex`
   - Compiler: pdfLaTeX

### Opsi 2: Instalasi Lokal (Windows)

1. **Install MikTeX**: [https://miktex.org/download](https://miktex.org/download)
   > Pilih *For All Users*, centang opsi *Always install missing packages*
2. **Install TeXstudio**: [https://www.texstudio.org/](https://www.texstudio.org/)
3. **Update MikTeX** melalui MikTeX Console
4. **Clone/unduh** repositori dan buka `laporan.tex` melalui TeXstudio
5. Klik **Build & View** untuk melihat hasil kompilasi (`laporan.pdf`)

### Opsi 3: MacOS dengan MacTeX

1. **Install MacTeX**: 
   ```bash
   brew install --cask mactex
   ```
2. **Install Texifier** atau **TeXstudio**
3. **Buka** `Project/laporan.tex`
4. **Compile** dengan pdfLaTeX

---

## ⚙️ Pengaturan Proposal / Laporan

Gunakan perintah berikut pada baris awal `laporan.tex`:

```latex
%\newcommand{\Jenis}{Proposal}   % Gunakan untuk Proposal
\newcommand{\Jenis}{Laporan}     % Gunakan untuk Laporan
```

> *Hanya aktifkan salah satu perintah (`%` artinya dikomentari)*

---

## ✍️ Langkah Pengerjaan Laporan

| File | Keterangan |
|------|-----------|
| `a0-identitas.tex` | **WAJIB:** Isi nama, NIM, judul TA, pembimbing, jurusan, warna cover prodi |
| `b1-bab1.tex` – `b5-bab5.tex` | Isi konten utama BAB 1–5 |
| `a7-pustaka.bib` | Tambah referensi dengan BibTeX (APA Style) |
| `a8-lampiran.tex` | Tambah daftar lampiran (max 10 halaman hardcopy) |
| `a9-motto.tex` | Motto (opsional, uncomment di `laporan.tex`) |
| `b6-bab6.tex` | *Tutorial LaTeX, opsional, dapat diabaikan* |
| `a2–a6-*.tex` | Abstrak, Kata Pengantar, Persembahan, dll. |

**Khusus untuk a0-identitas.tex, pastikan mengisi:**
- Nama dan NIM mahasiswa
- Judul TA (Indonesia & Inggris)
- Program Studi: Sarjana Terapan Teknologi Rekayasa Perangkat Lunak
- Jurusan: Jurusan Bisnis dan Informatika
- Warna cover sesuai prodi (kuning: 255,215,0)

---

## 📚 Manajemen Referensi

Gunakan:
* [Mendeley](https://www.mendeley.com/)
* [Zotero](https://www.zotero.org/)
* [JabRef](https://www.jabref.org/) *(direkomendasikan)*

Format ekspor: `.bib` (BibTeX), lalu tambahkan ke file `a7-pustaka.bib`.

**Penting:** Untuk D4/Sarjana Terapan, gunakan minimal 10 referensi jurnal/prosiding dari 10 tahun terakhir.

---

## 📝 Perbedaan D3 vs D4 (Sarjana Terapan)

| Aspek | D3 | D4/Sarjana Terapan |
|-------|----|--------------------|
| **Objek** | Sederhana (komponen) | Kompleks (sistem) |
| **Metode** | 1 metode | Minimal 2 metode, bandingkan |
| **Referensi** | Teori umum | Min. 10 jurnal 10 tahun terakhir |
| **Analisis** | Deskriptif | Statistik inferensi/simulasi |
| **Jenis TA** | Purwarupa, Desain, Pengembangan, Pengujian Lab | Semua D3 + Prosedur Baku, Analisa/Simulasi, Penyusunan Kebijakan |

---

## 📬 Kontak & Kontribusi

**Repository:** [github.com/codelabs-poliwangi/template-laporanTA-latex-poliwangi](https://github.com/codelabs-poliwangi/template-laporanTA-latex-poliwangi)

Saran, kontribusi, dan perbaikan sangat terbuka.
Silakan buat **Pull Request** atau buka **Issue** melalui GitHub.

---

## 📝 Informasi Template

- **Institusi:** Politeknik Negeri Banyuwangi
- **Program Studi:** Sarjana Terapan Teknologi Rekayasa Perangkat Lunak
- **Jurusan:** Jurusan Bisnis dan Informatika
- **Pedoman:** Pedoman Mutu Tugas Akhir Poliwangi 2023
- **Logo:** Politeknik Negeri Banyuwangi
- **Warna Cover Default:** Kuning (RGB: 255,215,0)

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

## 📁 Struktur Proyek

```
Template-LaTeX-Laporan-Tugas-Akhir
├── CHANGELOG                         # Catatan perubahan
├── LICENSE                           # Lisensi proyek        
├── Project                           # Folder proyek    
│   ├── a0-identitas.tex              # Isi identitas laporan 
│   ├── a1-database.hyphenate.tex     # Database untuk hyphenation
│   ├── a2-abstrak.tex                # Abstrak dalam Bahasa Indonesia  
│   ├── a3-abstract.tex               # Abstrak dalam Bahasa Inggris
│   ├── a4-persembahan.tex            # Persembahan
│   ├── a5-katapengantar.tex          # Kata Pengantar
│   ├── a6-daftarsingkatan.tex        # Daftar Singkatan
│   ├── a7-pustaka.bib                # Daftar pustaka dalam format BibTeX
│   ├── a8-lampiran.tex               # Lampiran
│   ├── b1-bab1.tex                   # BAB I - Pendahuluan
│   ├── b2-bab2.tex                   # BAB II - Tinjauan Pustaka
│   ├── b3-bab3.tex                   # BAB III - Metode Penelitian
│   ├── b4-bab4.tex                   # BAB IV - Hasil dan Pembahasan
│   ├── b5-bab5.tex                   # BAB V - Kesimpulan dan Saran
│   ├── b6-bab6.tex                   # BAB VI - Tutorial LaTeX (opsional)
│   ├── gambar                        # Folder untuk menyimpan gambar
│   │   ├── gambar-kucing.jpg
│   │   ├── logo-uny.png
│   │   ├── screenshot-miktex.png
│   │   ├── screenshot-overleaf.png
│   │   ├── screenshot-texstudio-macos.png
│   │   └── screenshot-texstudio-windows.png
│   ├── kode                          # Folder untuk menyimpan kode program
│   │   ├── code_sample.cpp
│   │   ├── code_sample.ino
│   │   ├── code_sample.java
│   │   └── code_sample.py
│   ├── laporan.pdf                   # Hasil kompilasi laporan
│   ├── laporan.tex                   # File utama untuk kompilasi laporan
│   └── untouch                       # Folder untuk menyimpan file yang tidak perlu diubah
│       ├── xx-daftar.tex
│       ├── xx-daftarpustaka.tex
│       ├── xx-pengesahan.tex
│       ├── xx-pernyataan.tex
│       ├── xx-persetujuan-proposal.tex
│       ├── xx-persetujuan-ujian.tex
│       ├── xx-preambles.tex
│       ├── xx-sampul-laporan.tex
│       ├── xx-sampul-proposal.tex
│       ├── xx-sampuldalam-laporan.tex
│       └── xx-sampuldalam-proposal.tex
└── README.md                         # Dokumen ini
```

---

## 🧩 Fitur Utama

✅ Format sesuai standar Prodi D4 Teknik Elektronika

✅ Mendukung kompilasi proposal & laporan akhir

✅ Contoh gambar, kode program, persamaan, tabel, dan sitasi

✅ Dukungan referensi otomatis (BibTeX)

✅ Dokumentasi & tutorial lengkap

✅ Kompatibel dengan TexStudio dan Overleaf


---

## 🖥️ Panduan Instalasi & Penggunaan Lokal (Windows)

1. **Install MikTeX**: [https://miktex.org/download](https://miktex.org/download)

   > Pilih *For All Users*, centang opsi *Always install missing packages*
2. **Install TeXstudio**: [https://www.texstudio.org/](https://www.texstudio.org/)
3. **Update MikTeX** melalui MikTeX Console
4. **Clone/unduh** repositori dan buka `laporan.tex` melalui TeXstudio
5. Klik **Build & View** untuk melihat hasil kompilasi (`laporan.pdf`)

---

## 🍎 Panduan Alternatif (MacOS - VS Code)

Lihat petunjuk lengkap instalasi dan konfigurasi pada dokumentasi berikut:
➡️ [Instalasi LaTeX di MacOS dengan VSCode](https://sudorealm.com/blog/how-to-write-latex-documents-with-visual-studio-code-on-mac)

---

## ⚙️ Pengaturan Proposal / Laporan

Gunakan perintah berikut pada baris awal `laporan.tex`:

```latex
%\newcommand{\Jenis}{Proposal}   % Gunakan untuk Proposal
\newcommand{\Jenis}{Laporan}     % Gunakan untuk Laporan
```

> *Hanya aktifkan salah satu perintah (`%` artinya dikomentari)*

---

## ✍️ Langkah Pengerjaan Laporan

| File                          | Keterangan                                         |
| ----------------------------- | -------------------------------------------------- |
| `a0-identitas.tex`            | Isi nama, NIM, judul TA, pembimbing, dll           |
| `b1-bab1.tex` – `b5-bab5.tex` | Isi konten utama BAB I–V                           |
| `a7-pustaka.bib`              | Tambah referensi dengan BibTeX                     |
| `a8-lampiran.tex`             | Tambah daftar lampiran                             |
| `b6-bab6.tex`                 | *Berisi tutorial LaTeX, opsional, dapat diabaikan* |
| `a2–a6-*.tex`                 | Abstrak, Kata Pengantar, Persembahan, dll.         |

---

## 📚 Manajemen Referensi

Gunakan:

* [Mendeley](https://www.mendeley.com/)
* [Zotero](https://www.zotero.org/)
* [JabRef](https://www.jabref.org/) *(direkomendasikan)*

Format ekspor: `.bib` (BibTeX), lalu tambahkan ke file `a7-pustaka.bib`.

---

## 🎬 Preview

![Cover Preview](Project/gambar/logo-poliwangi.png)

*Template ini sudah disesuaikan dengan format Politeknik Negeri Banyuwangi*

---

## 📝 Changelog

Catatan lengkap perubahan dan versi terbaru tersedia di file:
📄 [CHANGELOG](CHANGELOG)

---

## 🖼️ Screenshot

| MacOS                                                             | Windows                                                               |
| ----------------------------------------------------------------- | --------------------------------------------------------------------- |
| ![TexStudio MacOS](Project/gambar/screenshot-texstudio-macos.png) | ![TexStudio Windows](Project/gambar/screenshot-texstudio-windows.png) |

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

## 🤝 Kontribusi

Saran, kontribusi, dan perbaikan sangat terbuka.
Silakan buat **Pull Request** atau buka **Issue** melalui GitHub.

---

## 📬 Kontak

Jika Anda memiliki pertanyaan, hubungi:
📧 [ardyseto@uny.ac.id](mailto:ardyseto@uny.ac.id)
👤 [@2black0](https://github.com/2black0)

---