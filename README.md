# 📘 Portofolio Praktikum Git & GitHub – Pemrograman Web

Repositori ini merupakan hasil pengerjaan tugas praktikum *Pemrograman Web, dari **Modul 1 sampai 7, menggunakan sistem kontrol versi **Git* dan dikelola melalui platform *GitHub*.

Setiap modul dikerjakan secara terpisah menggunakan sistem *branch*, dengan struktur folder yang konsisten dan commit yang jelas untuk setiap tahapan.

---

## 📑 Daftar Isi

- [📂 Daftar Modul](#-daftar-modul)
- [🧱 Struktur Folder & Branch](#-struktur-folder--branch)
- [✅ Prasyarat](#-prasyarat)
- [⚙ Setup Proyek](#⚙-setup-proyek)
  - [📂 Clone Repository](#-clone-repository)
  - [📁 Setup Modul 1–3](#-setup-modul-13)
  - [🗂 Setup Modul 4](#-setup-modul-4)
  - [🗂 Setup Modul 5](#-setup-modul-5)
  - [🗂 Setup Modul 6](#-setup-modul-6)
- [🎬 Video Presentasi](#🎬-video-presentasi)
- [👨‍💻 Oleh](#👨‍💻-oleh)

---

## 📂 Daftar Modul

- [Modul 1](./Modul%201)

- [Modul 2](./Modul%202)

- [Modul 3](./Modul%203)

- [Modul 4](https://github.com/Vidimldyh/Portofolio-Pemrograman-Web-202312009/tree/tugas/modul-4-javascript/Modul%204)

- [Modul 5](https://github.com/Vidimldyh/Portofolio-Pemrograman-Web-202312009/tree/tugas/modul-5-php/Modul%205)

- [Modul 6](https://github.com/Vidimldyh/Portofolio-Pemrograman-Web-202312009/tree/tugas/modul-6-php-mysql/Modul%206)

---

## 🧱 Struktur Folder & Branch

### 📁 Struktur Folder

bash
Portofolio-Pemrograman-Web-202312013/
├── Modul 1/
├── Modul 2/
├── Modul 3/
├── Modul 4/
├── Modul 5/
└── Modul 6/

### 🌿 Struktur Branch

bash
main
├── tugas/modul-1-3
├── tugas/modul-4
├── tugas/modul-5
└── tugas/modul-6


---

## ✅ Prasyarat

Sebelum menjalankan proyek ini, pastikan Anda telah menginstal dan menyiapkan:

- ✔ [Git](https://git-scm.com/) – Untuk versi kontrol
- ✔ [GitHub](https://github.com/) – Akun aktif untuk menyimpan repo
- ✔ [Visual Studio Code](https://code.visualstudio.com/) – Code editor yang disarankan
- ✔ Browser modern (Chrome, Firefox, Edge)
- ✔ Koneksi internet stabil
- ✔ Pengetahuan dasar terminal / command line

---

## ⚙ Setup Proyek

Berikut adalah langkah-langkah setup dan pengerjaan proyek mulai dari clone repository, setup awal Git, hingga commit dan push setiap modul. Semua modul dikerjakan di branch terpisah sesuai instruksi dosen.

### 📂 Clone Repository

Pertama, clone repositori ke direktori lokal:

```bash
git clone https://github.com/Vidimldyh/Portofolio-Pemrograman-Web-202312009.git
cd Portofolio-Pemrograman-Web-202312013
```

### 📁 Setup Modul 1–3

*Langkah-langkah:*

1. Inisialisasi proyek Git di folder lokal
2. Tambahkan remote GitHub
3. Tambahkan file tugas Modul 1, 2, dan 3
4. Commit dan buat branch tugas/modul-1-3
5. Push branch ke GitHub
6. Buat branch main dari situ

```bash
git init
git remote add origin https://github.com/Vidimldyh/Portofolio-Pemrograman-Web-202312009.git

git add .
git commit -m "Menambahkan tugas Modul 1 sampai 3"

git checkout -b tugas/modul-1-3
git push origin tugas/modul-1-3

git checkout -b main
git push origin main
```

### 🗂 Setup Modul 4

*Langkah-langkah:*

1. Pastikan berada di branch main
2. Buat branch tugas/modul-4
3. Tambahkan folder Modul 4
4. Commit dan push ke GitHub

```bash
git checkout main
git pull

git checkout -b tugas/modul-4
mkdir Modul\ 4/
# (Pindahkan file tugas ke dalam folder Modul 4)

git add Modul\ 4/
git commit -m "Menambahkan tugas Modul 4"
git push origin tugas/modul-4
```

### 🗂 Setup Modul 5

*Langkah-langkah:*

1. Kembali ke branch main
2. Buat branch tugas/modul-5
3. Tambahkan folder Modul 5
4. Commit dan push ke GitHub

```bash
git checkout main
git checkout -b tugas/modul-5
mkdir Modul\ 5/
# (Pindahkan file tugas ke dalam folder Modul 5)

git add Modul\ 5/
git commit -m "Menambahkan tugas Modul 5"
git push origin tugas/modul-5
```

### 🗂 Setup Modul 6

*Langkah-langkah:*

1. Kembali ke branch main
2. Buat branch tugas/modul-6
3. Tambahkan folder Modul 6
4. Commit dan push ke GitHub

```bash
git checkout main
git checkout -b tugas/modul-6
mkdir Modul\ 6/
# (Pindahkan file tugas ke dalam folder Modul 6)

git add Modul\ 6/
git commit -m "Menambahkan tugas Modul 6"
git push origin tugas/modul-6
```


---

## 🎬 Video Presentasi

Berikut adalah video presentasi tugas praktikum Git & GitHub:

📹 [Klik untuk menonton video presentasi Git & GitHub](https://youtu.be/Hywb_uQSxow)

---

## 👨‍💻 Oleh

```yaml
Nama            : Siti Vidi Maulidiyah Sari Anas
NIM             : 202312009
Kelas           : Teknik Informatika – Pagi
Mata Kuliah     : Pemrograman Web
Dosen Pengampu  : Ir. ABADI NUGROHO, S.Kom., M.Kom