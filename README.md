# Rencana Belajar Pemrograman Web untuk Pemula

Selamat datang di dunia pemrograman! Dokumen ini adalah panduan belajar yang disusun secara sistematis untuk membantu Anda memahami dasar-dasar pengembangan web, mulai dari tingkat paling dasar hingga ke tingkat yang lebih lanjut.

Setiap tahap dirancang sebagai checklist. Anda dapat menandai setiap poin yang telah Anda pelajari dan pahami.

---

### Tahap 1: Memahami Struktur Dasar Website dengan HTML

**Tujuan:** Memahami bagaimana halaman web disusun menggunakan HTML (HyperText Markup Language). HTML adalah fondasi dari semua situs web.

- [ ] **Mempelajari Konsep Fundamental HTML**
    - **Apa itu HTML?** Pahami bahwa HTML bukanlah bahasa pemrograman, melainkan bahasa *markup* yang digunakan untuk menstrukturkan konten.
    - **Apa itu Tag?** Pelajari tentang tag, yaitu instruksi yang diapit oleh kurung sudut (contoh: `<p>`). Sebagian besar tag memiliki pasangan pembuka (`<p>`) dan penutup (`</p>`).
    - **Apa itu Elemen?** Pahami bahwa elemen adalah gabungan dari tag pembuka, konten di dalamnya, dan tag penutup. Contoh: `<p>Ini adalah sebuah paragraf.</p>`.
    - **Apa itu Atribut?** Pelajari tentang atribut, yaitu informasi tambahan yang diberikan pada tag pembuka untuk memodifikasi elemen. Contoh: `<a href="https://www.google.com">`. Di sini, `href` adalah atribut.

- [ ] **Membuat Halaman Web Pertama Anda**
    - [ ] Buka file `index.html` yang ada di repositori ini menggunakan teks editor (seperti VS Code, Notepad++, atau Sublime Text).
    - [ ] Amati strukturnya: `<!DOCTYPE html>`, `<html>`, `<head>`, dan `<body>`. Baca komentar di dalam file tersebut untuk memahami fungsi masing-masing bagian.
    - [ ] Coba ubah konten di dalam tag `<h1>`. Ganti "Hello, World!" dengan teks lain dan simpan filenya. Buka file tersebut di browser untuk melihat perubahannya.

- [ ] **Bereksperimen dengan Elemen HTML Umum**
    - [ ] **Teks:** Coba gunakan `<h1>` sampai `<h6>` untuk judul, `<p>` untuk paragraf, `<strong>` untuk teks tebal, dan `<em>` untuk teks miring.
    - [ ] **Tautan (Link):** Gunakan tag `<a>` dengan atribut `href` untuk membuat tautan ke situs web lain.
    - [ ] **Gambar:** Gunakan tag `<img>` dengan atribut `src` (sumber gambar) dan `alt` (teks alternatif jika gambar gagal dimuat).
    - [ ] **Daftar (List):** Buat daftar tidak berurutan dengan `<ul>` dan `<li>`, serta daftar berurutan dengan `<ol>` dan `<li>`.

---

### Tahap 2: Menghias Halaman Web dengan CSS

**Tujuan:** Mempelajari cara menggunakan CSS (Cascading Style Sheets) untuk mengatur tampilan visual halaman web, termasuk warna, tata letak, dan tipografi.

- [ ] **Mempelajari Konsep Dasar CSS**
    - **Apa itu CSS?** Pahami bahwa CSS digunakan untuk memisahkan presentasi (tampilan) dari struktur (HTML), membuat kode lebih rapi dan mudah dikelola.
    - **Selector, Property, dan Value:** Pelajari sintaks dasar CSS. **Selector** menargetkan elemen HTML yang ingin dihias (misalnya, `p`). **Property** adalah aspek yang ingin diubah (misalnya, `color`). **Value** adalah nilai dari properti tersebut (misalnya, `blue`). Contoh: `p { color: blue; }`.

- [ ] **Mengaplikasikan CSS ke HTML**
    - [ ] **Inline CSS:** Coba tambahkan atribut `style` langsung ke elemen HTML. (Contoh: `<p style="color: red;">`). Ini tidak direkomendasikan untuk penggunaan luas, tetapi baik untuk diketahui.
    - [ ] **Internal CSS:** Tulis kode CSS di dalam tag `<style>` yang ditempatkan di dalam `<head>` dokumen HTML.
    - [ ] **External CSS:** Buat file baru bernama `style.css`. Tulis semua aturan CSS Anda di file ini. Kemudian, hubungkan ke file HTML menggunakan tag `<link>` di dalam `<head>`. Ini adalah praktik terbaik.

- [ ] **Eksplorasi Properti CSS Umum**
    - [ ] **Warna dan Latar:** `color`, `background-color`.
    - [ ] **Teks dan Font:** `font-family`, `font-size`, `font-weight`, `text-align`.
    - [ ] **Model Kotak (Box Model):** Pahami konsep `margin` (jarak di luar elemen), `padding` (jarak di dalam elemen), `border` (garis tepi), `width`, dan `height`.

---

### Tahap 3: Menambahkan Interaktivitas dengan JavaScript

**Tujuan:** Mempelajari dasar-dasar JavaScript (JS) untuk membuat halaman web menjadi dinamis dan interaktif.

- [ ] **Mengenal JavaScript**
    - [ ] Pahami bahwa JavaScript adalah bahasa pemrograman *scripting* yang berjalan di sisi klien (browser) untuk memanipulasi konten halaman secara dinamis.
    - [ ] Pelajari cara menambahkan JavaScript ke HTML, baik secara internal menggunakan tag `<script>` maupun eksternal dengan file `.js`.

- [ ] **Fundamental Pemrograman dalam JavaScript**
    - [ ] **Variabel:** Belajar menyimpan data menggunakan `let` dan `const`.
    - [ ] **Tipe Data:** Mengenal tipe data dasar seperti `String`, `Number`, dan `Boolean`.
    - [ ] **Logika Kondisional:** Menggunakan `if`, `else if`, dan `else` untuk membuat program mengambil keputusan.
    - [ ] **Fungsi (Functions):** Belajar menulis blok kode yang dapat digunakan kembali.

- [ ] **Manipulasi DOM (Document Object Model)**
    - [ ] Pahami bahwa DOM adalah representasi struktur HTML dalam bentuk objek yang bisa dimanipulasi oleh JavaScript.
    - [ ] Coba gunakan metode seperti `document.getElementById()` atau `document.querySelector()` untuk memilih elemen HTML.
    - [ ] Setelah memilih elemen, coba ubah kontennya (menggunakan `.innerHTML` atau `.textContent`) atau gayanya (menggunakan `.style`).

---

### Tahap Lanjutan: Menjadi Pengembang Web Profesional

Setelah menguasai dasar-dasar di atas, Anda dapat melanjutkan perjalanan belajar Anda ke area yang lebih terspesialisasi.

- [ ] **Mempelajari Git dan GitHub:** Sistem kontrol versi yang esensial untuk mengelola kode dan berkolaborasi dengan tim.
- [ ] **Mendalami Framework/Library:**
    - **Frontend:** Pelajari *framework* seperti React, Vue, atau Angular untuk membangun antarmuka pengguna yang kompleks dengan lebih efisien.
    - **Backend:** Jika tertarik dengan sisi server, pelajari bahasa seperti Node.js (JavaScript), Python (dengan Django/Flask), atau PHP, beserta cara mengelola database (misalnya, MySQL atau PostgreSQL).
- [ ] **Membangun Proyek Portofolio:** Cara terbaik untuk belajar adalah dengan praktik. Buatlah proyek-proyek kecil hingga besar untuk mengaplikasikan ilmu yang telah dipelajari.

Selamat belajar, dan nikmati prosesnya!
