# Pemrograman Fungsional (Functional Programming with Python)

Kumpulan notebook praktikum dan tugas mata kuliah **Pemrograman Fungsional** berbasis **Python 3** (Lab-IT Universitas Muhammadiyah Malang, 2026) yang mencakup dasar pemrograman fungsional Python hingga *First-Class Functions*, *Higher-Order Functions*, *Lambda Expressions*, *Closures*, *Currying*, dan *Decorators*.

---

## Daftar Isi Notebook

| No | File Notebook | Modul & Topik Utama | Total Sel (Code Sel) | Ringkasan Tugas / Praktikum |
|---:|---|---|---:|---|
| 1 | [`assignment_FP1.ipynb`](assignment_FP1.ipynb) | **Module 1** — *Functional Programming using Python* | 172 (62) | Tipe data Python (`str`, `list`, `tuple`, `range`, `dict`, `bool`), *type casting*, fungsi, percabangan, perulangan, rekursi, *exception handling*, serta Assignment 1 (pengolahan nilai mahasiswa) & Assignment 2 (pengelolaan dataset berbasis `tuple`/`dict`). |
| 2 | [`assignment_FP2.ipynb`](assignment_FP2.ipynb) | **Module 1–2** — *Immutable State & Deep Copy Pipeline* | 173 (63) | Kelanjutan dasar Python dengan penekanan pada *immutability* data menggunakan `copy.deepcopy` agar pembaruan dataset (`update_passengers`) tidak memutasi data asli. |
| 3 | [`assignment_FP3.ipynb`](assignment_FP3.ipynb) | **Module 1–3 Bridge** — *Immutable Data + `functools.reduce`* | 173 (63) | Integrasi `functools.reduce` ke dalam pipeline pemrosesan record berbasis fungsi tanpa mutasi state asal. |
| 4 | [`Modul 3 assignment 1.ipynb`](Modul%203%20assignment%201.ipynb) | **Module 3** — *First-Class Functions & Higher-Order Functions* | 189 (62) | Fungsi sebagai *first-class values*, parameter & return value, fungsi dalam struktur data, `map()`, `filter()`, `reduce()`, fungsi rekursif, serta **Hotel Booking Revenue System** (Assignment 1 & 2 tanpa `lambda`). |
| 5 | [`Modul 4 assignment 1.ipynb`](Modul%204%20assignment%201.ipynb) | **Module 4** — *Lambda, Closure, Currying & Decorator* | 184 (58) | *Lambda expressions* (`map`/`filter`/`reduce`), *closures*, *currying* vs *partial application*, komposisi fungsi, serta multi-*decorator* (`@` syntax), diikuti Code Analysis & Assignment 1–2. |

---

## Struktur Direktori

```text
Pemrograman_Fungsional/
├── .gitignore
├── README.md
├── assignment_FP1.ipynb
├── assignment_FP2.ipynb
├── assignment_FP3.ipynb
├── Modul 3 assignment 1.ipynb
└── Modul 4 assignment 1.ipynb
```

---

## Persyaratan & Cara Menjalankan

### Prasyarat
- **Python 3.10+** (pustaka standar Python sudah mencukupi seluruh notebook, tidak perlu package eksternal khusus).
- Salah satu dari lingkungan berikut:
  - **JupyterLab / Jupyter Notebook**
  - **Visual Studio Code** (ekstensi *Jupyter* + *Python*)
  - **Google Colab** (unggah / buka file `.ipynb`)

### Menjalankan Secara Lokal dengan Jupyter

```bash
# Opsional: buat virtual environment
python -m venv .venv

# Aktifkan di Windows (PowerShell)
.\.venv\Scripts\Activate.ps1

# Install Jupyter Notebook / JupyterLab jika belum tersedia
pip install notebook

# Jalankan Jupyter pada folder repository
jupyter notebook
```

Setelah browser terbuka, pilih file `.ipynb` pada daftar isi di atas dan jalankan sel secara berurutan dari atas ke bawah.
