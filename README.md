```markdown
# 🌐 Raditya's Portfolio

Personal portfolio website developed using HTML and Tailwind CSS framework to showcase projects and web development skills.

---

## 🛠️ Teknologi yang Digunakan

* **HTML5** - Struktur konten web
* **Tailwind CSS v4** - Styling dan desain responsif
* **Git & GitHub** - Version control dan hosting

---

## 📂 Struktur Folder

```text
├── gambar/             # Aset gambar dan media proyek
├── src/
│   ├── input.css       # File CSS utama (Tailwind configuration & directives)
│   └── output.css      # Hasil kompilasi CSS yang dipanggil di HTML
├── index.html          # Halaman utama portofolio
├── package.json        # Dependensi proyek (Node.js & Tailwind CLI)
├── package-lock.json   # Pengunci versi dependensi
├── .gitignore          # Daftar file/folder yang diabaikan Git
└── README.md           # Dokumentasi proyek

```

---

## 💻 Cara Menjalankan di Lokal

### 1. Clone Repository

Buka terminal di VS Code, lalu jalankan perintah:

```bash
git clone https://github.com/radityakusumaa/Raditya-s-Portfolio.git

```

Masuk ke folder proyek yang baru di-clone:

```bash
cd Raditya-s-Portfolio

```

### 2. Install Dependensi

Pastikan Node.js sudah terinstall di komputermu, lalu jalankan perintah:

```bash
npm install

```

### 3. Jalankan Tailwind CSS Watcher

Untuk mengompilasi CSS secara otomatis saat ada perubahan pada file HTML atau CSS:

```bash
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch

```

### 4. Buka di Browser

Buka file `index.html` langsung di browser atau gunakan ekstensi **Live Server** di VS Code.

```

---

### Perbaikan yang Dilakukan:
1. **Penomoran Rapi:** Urutan nomor pada langkah *Cara Menjalankan di Lokal* dipatenkan menjadi 1, 2, 3, 4 (sebelumnya melompat dari 1 ke 3).
2. **Duplikasi Link Dihapus:** Perintah `git clone` yang double/ganda sudah dibersihkan.
3. **Penyatuan Blok Kode (`Code Blocks`):** Semua perintah terminal (`cd`, `npm install`, `npx @tailwindcss...`) dibungkus rapi dalam blok kode ` ```bash ` agar muncul dalam kotak terpisah yang mudah dibaca di GitHub.

```
