# 🚀 Praktikum Pemrograman Fungsional

Repositori ini berisi kumpulan tugas, codelab, dan modul praktikum untuk mata kuliah **Praktikum Pemrograman Fungsional** (Semester 5).

---

## 👤 Identitas Mahasiswa

| Informasi | Keterangan |
| :--- | :--- |
| **Nama Lengkap** | Farid Al Farizi |
| **NIM** | 202410370110017 |
| **Mata Kuliah** | Praktikum Pemrograman Fungsional |
| **Semester** | 5 |

---

## 📁 Struktur Direktori

```text
.
├── Codelab 1/
│   ├── MODUL_1_FUNGSIO_26.ipynb      # Materi dan panduan modul 1
│   └── codelab1.ipynb                 # Pengerjaan latihan Codelab 1 (Exercise 1–8)
│
├── Codelab 2/
│   ├── MODUL_2_FUNGSIO_26.ipynb      # Materi dan panduan modul 2
│   └── codelab2.ipynb                 # Pengerjaan latihan Codelab 2 (Exercise 1–6)
│
├── Tugas 1/
│   ├── Assignment 1/
│   │   └── Assignment_1.ipynb         # Tugas 1: Dual Output, Tuple Conversion, Rekursi & Error Handling
│   └── Assignment 2/
│       └── Assignment_2.ipynb         # Tugas 1: Sistem Pencatatan Data Eksperimen Kecepatan Internet
│
├── .gitignore                         # Konfigurasi file yang diabaikan oleh Git
├── requirements.txt                   # Dependensi environment Python / Jupyter
└── README.md                          # Dokumentasi repositori
```

---

## 📚 Ringkasan Materi & Tugas

### 🔹 Modul 1 & Codelab 1: Dasar Pemrograman Fungsional Python
- **Topik Pembahasan:**
  - Tipe data dasar, variabel, dan immutability vs mutability.
  - Struktur data koleksi: *List*, *Tuple*, *Dictionary*, dan *Set*.
  - Slicing, indexing, dan kontrol alur (*control flow*).
  - Konsep fungsi dasar, dual output function, rekursi dasar, serta penanganan error (*exception handling*).
- **Codelab 1:** Implementasi latihan soal (Exercise 1 s/d Exercise 8) sesuai instruksi modul praktikum.

### 🔹 Modul 2 & Codelab 2: Pure Functions & Immutability
- **Topik Pembahasan:**
  - *Effect-Free Programming*: Menulis kode bebas dari efek samping (*side effects*).
  - *Pure Functions*: Fungsi deterministik yang menghasilkan output konsisten untuk input yang sama tanpa memodifikasi variabel di luar cakupannya.
  - *Immutability*: Menghindari mutasi data in-place dengan membuat salinan baru (*deep copy* / fungsi murni).
- **Codelab 2:** Implementasi penyelesaian latihan studi kasus (Exercise 1 s/d Exercise 6) mengenai fungsi murni dan manipulasi data immutable.

### 🔹 Tugas 1 (Assignments)
- **Assignment 1:**
  1. *Function 1 & Function 2*: Fungsi pemisah data dengan dual output.
  2. *Konversi ke Tuple*: Pemrosesan data mahasiswa kelulusan (NIM ganjil) menjadi struktur immutable *Tuple*.
  3. *Rekursi & Exception Handling*: Implementasi fungsi rekursif dengan mekanisme penanganan pengecualian (*try-except-else*).
- **Assignment 2 (Sistem Pencatatan Data Eksperimen Kecepatan Internet):**
  1. *Struktur Data & Mock Data*: Inisialisasi struktur dataset eksperimen kecepatan internet.
  2. *Validasi Input*: Validasi input interaktif menggunakan `while loop` dan `try-except`.
  3. *Navigasi Menu Slicing*: Menampilkan data secara modular menggunakan teknik slicing.
  4. *Autentikasi*: Fitur registrasi dan login dengan validasi kredensial.
  5. *Session Lock & Manipulasi Data*: Penguncian sesi pengguna saat manipulasi data dilakukan.
  6. *Program Utama*: Integrasi antarmuka terminal/interaktif secara menyeluruh.

---

## 🛠️ Prasyarat & Menjalankan Notebook

### 1. Prasyarat Sistem
- **Python 3.10+**
- Visual Studio Code (dengan ekstensi Jupyter) atau **JupyterLab** / **Google Colab**

### 2. Setup Virtual Environment (Opsional namun Disarankan)
```bash
# Buat virtual environment
python3 -m venv venv

# Aktifkan virtual environment (macOS / Linux)
source venv/bin/activate

# Atau aktifkan di Windows (PowerShell)
# .\venv\Scripts\Activate.ps1
```

### 3. Instalasi Dependensi
```bash
pip install -r requirements.txt
```

### 4. Menjalankan Jupyter Notebook
```bash
jupyter lab
# atau
jupyter notebook
```
Buka file `.ipynb` yang diinginkan melalui antarmuka Jupyter atau langsung lewat VS Code.

---

## 📤 Panduan Push ke GitHub

Jika repositori ini belum dihubungkan ke GitHub, ikuti langkah-langkah berikut:

### 1. Inisialisasi Git Lokal
Pastikan Anda berada di direktori utama folder tugas ini:
```bash
# Inisialisasi repositori Git
git init

# Buat branch utama dengan nama 'main'
git branch -M main
```

### 2. Tambahkan File ke Staging & Buat Commit Pertama
```bash
# Cek status file (pastikan file tersembunyi seperti .DS_Store sudah terabaikan)
git status

# Tambahkan semua file yang relevan
git add .

# Buat commit pertama
git commit -m "feat: inisialisasi repositori praktikum pemrograman fungsional"
```

### 3. Hubungkan ke Remote Repository GitHub
1. Buat repositori baru di [GitHub](https://github.com/new) (misalnya diberi nama `praktikum-pemrograman-fungsional`).
2. Jangan centang *Add a README file*, *Add .gitignore*, atau *Choose a license* (karena sudah dibuat secara lokal).
3. Salin URL repositori Anda, lalu jalankan:

```bash
# Ganti URL di bawah dengan URL repositori Anda
git remote add origin https://github.com/username/praktikum-pemrograman-fungsional.git

# Push ke GitHub
git push -u origin main
```

---

## 📄 Lisensi & Kontribusi
Repositori ini ditujukan untuk keperluan akademik perkuliahan pada mata kuliah Praktikum Pemrograman Fungsional. Silakan gunakan sebagai bahan referensi dan pembelajaran.
