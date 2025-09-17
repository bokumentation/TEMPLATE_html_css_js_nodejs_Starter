## Basic HTML CSS JAVASCRIPT by using NPM and Node JS
Yang akan dipelajari.
- Frontend:
  - HTML
  - CSS
  - Javascript
- Server:
  - Node.js

Bahan:
- Node.js Windows with NPM ([link](https://nodejs.org/en/download)). Check pilihan `Or get a prebuild Node.js for...`. Pilih `Windows` running a `x64` kemudian klik `Windows Installer (.msi)`.
- Dirimu bisa menginstall beberapa ekstensi vscode yang berguna misal
  - HTML CSS Support (untuk autocompletion)
  - ESLint (untuk analisis kode)

## Langsung Mulai
1. Clone repositori dan navigasi.
  ```bash
  git clone https://github.com/bokumentation/TEMPLATE_html_css_js_nodejs_Starter.git
  ```
  ```bash
  cd TEMPLATE_html_css_js_nodejs_Starter
  ```
2. Jalankan server: jalankan `node index.js` di terminal.
  ```bash
  node index.js
  ```
3. Preview di browser. Buka browser dan pergi ke `http://localhost:3000`.


---
## Struktur Folder 
Proyek ini memiliki struktur folder yang sederhana dan terorganisir untuk memisahkan file backend dan frontend.

```
hello-world-app/
├── public/
│   ├── index.html
│   ├── style.css
│   └── script.js
├── index.js
└── package.json
```

### Penjelasan
- `public/`
  Folder ini berisi semua file yang akan diakses oleh browser (frontend). Ini adalah praktik standar dalam pengembangan web untuk menempatkan file statis seperti HTML, CSS, dan JavaScript di satu tempat.

    - `index.html`
    Ini adalah file HTML utama yang menjadi halaman web yang akan dilihat pengguna. File ini berisi struktur dasar halaman dan menghubungkan ke file CSS dan JavaScript.

    - `style.css`
    File CSS ini bertanggung jawab untuk mengatur tampilan visual halaman web, seperti warna, tata letak, dan tipografi.

  - `script.js`
    Ini adalah file JavaScript yang berjalan di sisi browser (frontend). File ini digunakan untuk menambahkan interaktivitas atau perilaku dinamis pada halaman web.

- `index.js`
  Ini adalah file utama (entry point) dari aplikasi Node.js. File ini berfungsi sebagai server yang melayani file-file statis dari folder public/ ke browser. File ini menjalankan server, menerima permintaan, dan mengirimkan respons.

- `package.json`
  File ini digunakan oleh npm untuk mengelola metadata proyek. Di dalamnya terdapat informasi seperti nama proyek, versi, skrip yang dapat dijalankan, dan daftar dependensi (library atau package) yang dibutuhkan oleh proyek ini.