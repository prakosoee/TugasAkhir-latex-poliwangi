# 📘 Template LaTeX Tugas Akhir Poliwangi

*Program Sarjana Terapan Teknologi Rekayasa Perangkat Lunak – Politeknik Negeri Banyuwangi*

Template LaTeX untuk penulisan **Proposal** dan **Laporan Tugas Akhir** bagi mahasiswa D3 dan D4 Politeknik Negeri Banyuwangi. Template ini memastikan keseragaman format sesuai Pedoman Mutu Tugas Akhir Poliwangi 2023.

---

## 📂 Struktur Repository

Repository ini terdiri dari **2 folder utama**:

### 1. 📁 `proposal/` - Template Proposal Tugas Akhir
Untuk penulisan **Proposal TA** yang terdiri dari:
- **BAB 1** - Pendahuluan
- **BAB 2** - Tinjauan Pustaka
- **BAB 3** - Metode Penelitian
- Cover, Abstrak, Daftar Pustaka

**File utama:** `proposal/proposal.tex`

### 2. 📁 `laporan/` - Template Laporan Tugas Akhir
Untuk penulisan **Laporan TA Lengkap** yang terdiri dari:
- **BAB 1** - Pendahuluan
- **BAB 2** - Tinjauan Pustaka
- **BAB 3** - Metode Penelitian
- **BAB 4** - Hasil dan Pembahasan
- **BAB 5** - Kesimpulan dan Saran
- Cover, Halaman Pengesahan, Abstrak, Kata Pengantar, dll.

**File utama:** `laporan/laporan.tex`

---

## 📁 Struktur Detail

### Folder `laporan/` (Laporan Tugas Akhir Lengkap)

```
laporan/
├── laporan.tex                       # File utama untuk kompilasi laporan
├── a0-identitas.tex                  # Isi identitas (WAJIB DIISI)
├── a1-database.hyphenate.tex         # Database hyphenation
├── a2-abstrak.tex                    # Abstrak Bahasa Indonesia  
├── a3-abstract.tex                   # Abstrak Bahasa Inggris
├── a4-persembahan.tex                # Halaman Persembahan
├── a5-katapengantar.tex              # Kata Pengantar
├── a6-daftarsingkatan.tex            # Daftar Singkatan
├── a7-pustaka.bib                    # Daftar Pustaka (BibTeX)
├── a8-lampiran.tex                   # Lampiran
├── a9-motto.tex                      # Motto (opsional)
├── b1-bab1.tex                       # BAB 1 - Pendahuluan
├── b2-bab2.tex                       # BAB 2 - Tinjauan Pustaka
├── b3-bab3.tex                       # BAB 3 - Metode Penelitian
├── b4-bab4.tex                       # BAB 4 - Hasil dan Pembahasan
├── b5-bab5.tex                       # BAB 5 - Kesimpulan dan Saran
├── b6-bab6.tex                       # BAB 6 - Tutorial LaTeX (opsional)
├── gambar/                           # Folder gambar
│   └── logo-poliwangi.png
├── kode/                             # Folder kode program
└── untouch/                          # File sistem (jangan diubah)
    ├── xx-daftar.tex
    ├── xx-daftarpustaka.tex
    ├── xx-pengesahan.tex
    ├── xx-pernyataan-poliwangi.tex
    ├── xx-persetujuan-ujian.tex
    ├── xx-preambles.tex
    ├── xx-sampul-laporan.tex
    └── xx-sampuldalam-laporan.tex
```

### Folder `proposal/` (Proposal Tugas Akhir)

```
proposal/
├── proposal.tex                      # File utama untuk kompilasi proposal
├── a0-identitas.tex                  # Isi identitas (WAJIB DIISI)
├── a2-abstrak.tex                    # Abstrak Bahasa Indonesia  
├── a3-abstract.tex                   # Abstrak Bahasa Inggris
├── a6-daftarsingkatan.tex            # Daftar Singkatan
├── a7-pustaka.bib                    # Daftar Pustaka (BibTeX)
├── b1-bab1.tex                       # BAB 1 - Pendahuluan
├── b2-bab2.tex                       # BAB 2 - Tinjauan Pustaka
├── b3-bab3.tex                       # BAB 3 - Metode Penelitian
├── gambar/                           # Folder gambar
│   └── logo-poliwangi.png
├── kode/                             # Folder kode program
└── untouch/                          # File sistem (jangan diubah)
    ├── xx-daftar.tex
    ├── xx-daftarpustaka.tex
    ├── xx-persetujuan-proposal.tex
    ├── xx-preambles.tex
    ├── xx-sampul-proposal.tex
    └── xx-sampuldalam-proposal.tex
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

## 🖥️ Panduan Instalasi dan Penggunaan

### Opsi 1: Overleaf (Direkomendasikan - Mudah & Online) ☁️

**Keuntungan:** Tidak perlu install apapun, langsung bisa dipakai online, kolaborasi mudah.

#### Cara Upload ke Overleaf:

1. **Daftar/Login Overleaf**:
   - Buka [Overleaf](https://www.overleaf.com/)
   - Buat akun gratis atau login

2. **Upload Project**:
   - Klik **New Project** → **Upload Project**
   - Download repository ini sebagai ZIP dari GitHub
   - Upload file ZIP ke Overleaf
   
   **ATAU** import langsung dari GitHub:
   - Klik **New Project** → **Import from GitHub**
   - Pilih repository: `template-TugasAkhir-latex-poliwangi`
   - Pilih folder `laporan` atau `proposal` sesuai kebutuhan

3. **Set Main File & Compile**:
   - Klik menu di kiri atas (☰)
   - Pilih **Main document** → pilih `laporan.tex` (untuk laporan) atau `proposal.tex` (untuk proposal)
   - Compiler akan otomatis: **pdfLaTeX**
   - Klik **Recompile** untuk generate PDF

4. **Edit dan Preview**:
   - Edit file `.tex` di panel kiri
   - Preview PDF akan muncul di panel kanan
   - Auto-compile saat save (jika diaktifkan)

---

### Opsi 2: Instalasi Lokal Windows 🪟

#### Langkah 1: Install MikTeX (LaTeX Distribution)

1. **Download MikTeX**:
   - Buka [https://miktex.org/download](https://miktex.org/download)
   - Download **MikTeX Installer** untuk Windows

2. **Install MikTeX**:
   - Jalankan installer
   - Pilih **Install for All Users** (recommended)
   - **PENTING:** Centang opsi **"Always install missing packages on-the-fly"**
   - Ikuti wizard instalasi sampai selesai
   - Install size: ~300-400 MB

3. **Update MikTeX** (Penting!):
   - Buka **MikTeX Console** dari Start Menu
   - Klik **Check for updates**
   - Klik **Update now** untuk update semua packages
   - Tunggu sampai selesai (~10-30 menit tergantung internet)

#### Langkah 2: Install TeXstudio (Editor)

1. **Download TeXstudio**:
   - Buka [https://www.texstudio.org/](https://www.texstudio.org/)
   - Download versi terbaru untuk Windows

2. **Install TeXstudio**:
   - Jalankan installer
   - Ikuti wizard instalasi (Next → Next → Install)
   - Install size: ~100 MB

#### Langkah 3: Gunakan Template

1. **Download/Clone Repository**:
   - Clone repository atau download sebagai ZIP
   - Extract ke folder pilihan Anda

2. **Buka di TeXstudio**:
   - Buka TeXstudio
   - Klik **File** → **Open**
   - Navigate ke folder `laporan/` dan buka `laporan.tex`
   - ATAU ke folder `proposal/` dan buka `proposal.tex`

3. **Compile**:
   - Klik tombol **Build & View** (F5) atau tombol ▶️ hijau
   - PDF akan muncul di panel sebelah kanan
   - Jika ada error package missing, MikTeX akan auto-download

4. **Tips TeXstudio**:
   - **Auto-complete:** Ketik `\` untuk melihat suggestions
   - **Spell check:** Aktifkan di Options → Configure TeXstudio → Language Checking
   - **Split View:** View → Split View Vertically untuk lihat code & PDF bersamaan

---

### Opsi 3: MacOS dengan MacTeX 🍎

#### Langkah 1: Install MacTeX (LaTeX Distribution)

**Via Homebrew (Recommended):**

```bash
# Install Homebrew dulu jika belum ada
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# Install MacTeX (Full version ~4.5 GB)
brew install --cask mactex

# Atau install BasicTeX (Minimal version ~100 MB)
brew install --cask basictex
```

**Via Download Manual:**
- Buka [https://www.tug.org/mactex/](https://www.tug.org/mactex/)
- Download **MacTeX.pkg** (~4.5 GB)
- Install dengan double-click file .pkg
- Ikuti wizard instalasi

**Setelah Install:**
```bash
# Update TeX Live Manager
sudo tlmgr update --self
sudo tlmgr update --all
```

#### Langkah 2: Install Editor (Pilih Salah Satu)

**A. Texifier (Recommended untuk Mac - Berbayar tapi bagus)**
- Download dari [Mac App Store](https://apps.apple.com/app/texifier/id458609333)
- Harga: ~$30 (one-time purchase)
- Live Preview, iCloud sync, dark mode support

**B. TeXstudio (Gratis & Open Source)**
```bash
brew install --cask texstudio
```

**C. Visual Studio Code + LaTeX Workshop (Gratis)**
```bash
# Install VS Code
brew install --cask visual-studio-code

# Buka VS Code, install extension "LaTeX Workshop"
```

#### Langkah 3: Gunakan Template

1. **Download/Clone Repository**:
   ```bash
   cd ~/Documents
   git clone https://github.com/codelabs-poliwangi/template-TugasAkhir-latex-poliwangi.git
   cd template-TugasAkhir-latex-poliwangi
   ```

2. **Buka dengan Editor**:
   - **Texifier:** File → Open → pilih `laporan/laporan.tex` atau `proposal/proposal.tex`
   - **TeXstudio:** Same as Windows
   - **VS Code:** Open folder, lalu buka file `.tex`, tekan `Cmd+S` untuk compile

3. **Compile**:
   - **Texifier:** Otomatis compile saat save
   - **TeXstudio:** Klik Build & View (⌘+B)
   - **VS Code:** Auto-build saat save, atau klik "Build LaTeX project"

---

### Opsi 4: Linux (Ubuntu/Debian) 🐧

#### Install TeX Live dan TeXstudio:

```bash
# Update package list
sudo apt update

# Install TeX Live Full
sudo apt install texlive-full

# Install TeXstudio
sudo apt install texstudio

# Atau install packages minimal
sudo apt install texlive-latex-base texlive-latex-extra texlive-fonts-recommended texlive-bibtex-extra
```

#### Gunakan Template:
```bash
# Clone repository
git clone https://github.com/codelabs-poliwangi/template-TugasAkhir-latex-poliwangi.git
cd template-TugasAkhir-latex-poliwangi/laporan

# Compile via command line
pdflatex laporan.tex
bibtex laporan
pdflatex laporan.tex
pdflatex laporan.tex

# Atau buka di TeXstudio
texstudio laporan.tex
```

---

### 📋 Troubleshooting

#### Missing Packages Error:
- **MikTeX (Windows):** Pastikan "install packages on-the-fly" aktif di MikTeX Console
- **MacTeX:** Jalankan `sudo tlmgr install <package-name>`
- **Linux:** Jalankan `sudo apt install texlive-<package-name>`

#### Error "Command not found":
- Restart terminal/computer setelah install
- Tambahkan ke PATH: 
  - Windows: MikTeX biasanya auto-add
  - Mac: `/Library/TeX/texbin`
  - Linux: `/usr/bin`

#### PDF Tidak Muncul:
- Compile 2-3 kali untuk references & table of contents
- Check error log di bagian bawah editor
- Pastikan tidak ada syntax error di file .tex

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

**Repository:** [github.com/codelabs-poliwangi/template-TugasAkhir-latex-poliwangi](https://github.com/codelabs-poliwangi/template-TugasAkhir-latex-poliwangi)

Saran, kontribusi, dan perbaikan sangat terbuka.
Silakan buat **Pull Request** atau buka **Issue** melalui GitHub.

**Kontak:**
📧 sepyan@poliwangi.ac.id

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