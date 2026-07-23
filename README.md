# Raditya-s-Portfolio
Personal portfolio website developed using HTML and Tailwind CSS framework

# Teknologi yang Digunakan
  - HTML - Struktur konten web
  - Tailwind CSS v4 - Styling 

# Struktur Folder
  ├── gambar/             # Aset gambar
  ├── src/
  │   ├── input.css       # File CSS utama (Tailwind configuration & directives)
  │   └── output.css      # Hasil kompilasi CSS yang dipanggil di HTML
  ├── index.html          # Halaman utama portofolio
  ├── package-lock.json   # Dependensi proyek (Node.js & Tailwind CLI)
  ├── package.json        # Dependensi proyek (Node.js & Tailwind CLI)
  ├── .gitignore          # Daftar file/folder yang diabaikan Git
  └── README.md           # Dokumentasi proyek

# Cara Menjalankan di Lokal
  1. Clone Repository
     Buka terminal di VSCode
     Jalankan perintah: git clone https://github.com/radityakusumaa/Raditya-s-Portfolio.git
     Masuk ke folder proyek yang baru di clone
     
  3. Install Dependensi
     Pastikan Node.js sudah terinstall di komputermu
     Jalankan perintah install: npm install
     
  4. Jalankan Tailwind CSS Watcher
     Untuk mengompilasi CSS secara otomatis saat ada perubahan pada file HTML atau CSS:
       npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
     
  5. Buka di Browser
     Buka file index.html langsung di browser atau gunakan ekstensi Live Server di VS Code.
