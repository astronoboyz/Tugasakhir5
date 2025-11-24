# 🔢 Kalkulator Interaktif (Web-Based Interactive Calculator)

## Deskripsi Proyek

**Kalkulator Interaktif** adalah aplikasi kalkulator berbasis web yang dirancang untuk melakukan perhitungan matematika dasar dengan antarmuka yang bersih, modern, dan sepenuhnya **responsif**.

Dibangun menggunakan **HTML, CSS, dan Vanilla JavaScript**, proyek ini berfokus pada fungsionalitas cerdas dan pengalaman pengguna (UX) yang ditingkatkan. Berbeda dengan kalkulator konvensional, kalkulator ini menggunakan logika *state management* dan *chain calculation* yang cerdas, dilengkapi dengan fitur riwayat dan memori lengkap.

> Proyek ini menunjukkan penguasaan JavaScript murni untuk manipulasi DOM dan implementasi logika perhitungan yang kompleks.

## 🛠️ Teknologi yang Digunakan

* **HTML5** (Struktur)
* **CSS3** (Styling & Media Queries untuk Responsivitas)
* **JavaScript (Vanilla)** (Logika Perhitungan)

---

## ✨ Fitur Unggulan

Proyek ini dilengkapi dengan fitur-fitur yang melampaui kalkulator web sederhana:

### 1. Desain & Responsivitas
* **Fully Responsive:** Tampilan dioptimalkan secara otomatis untuk perangkat **desktop** dan **mobile** (smartphone).
* **Modern UI:** Menggunakan *flat design* dan *Grid Layout* yang rapi untuk antarmuka yang intuitif.

### 2. Logika Perhitungan Cerdas
* **Chain Calculation:** Memungkinkan pengguna melanjutkan perhitungan dengan hasil sebelumnya secara otomatis.
* **Validasi Input Pintar:**
    * Mencegah *double decimal* (contoh: `5..5`).
    * Mengatasi pergantian operator secara otomatis (contoh: Menekan `+` lalu menekan `*` akan mengganti operator, bukan menumpuknya).

### 3. Fitur Lanjutan (Advanced)
* **Fungsi Memori Lengkap (M+, M-, MR, MC):** Mengelola nilai memori untuk perhitungan yang kompleks, termasuk logika MR yang cerdas.
* **Riwayat Perhitungan (History Panel):**
    * Menyimpan dan menampilkan **5 perhitungan terakhir** di panel terpisah.
* **Error Handling:** Mendeteksi dan mencegah **pembagian dengan nol** (`Error: Dibagi Nol`), memastikan stabilitas aplikasi.
* **Keyboard Support:** Mendukung input penuh dari keyboard fisik (angka, operator, `Enter` untuk `=`, `Backspace` untuk hapus karakter, `Esc/C` untuk reset).

---

## 🖼️ Tampilan Antarmuka Pengguna (Screenshots)

Berikut adalah beberapa tampilan utama yang menonjolkan fitur-fitur Kalkulator Interaktif:

### 1. Tampilan Utama



*Menampilkan layar utama kalkulator dengan riwayat perhitungan (history) dan nilai yang sedang diketik (current display). Panel Riwayat Perhitungan terlihat di bagian bawah.*

### 2. Error Handling (Dibagi Nol)



[Image of Tidak Bisaa Dibagi 0]


*Menunjukkan mekanisme Error Handling, di mana sistem akan menampilkan pesan peringatan **"Error: Dibagi Nol"** jika pengguna mencoba melakukan pembagian dengan angka nol, menjaga agar aplikasi tidak crash.*

### 3. Penggunaan Memori (M- / M+)



*Ilustrasi penggunaan tombol **M+** (Memory Plus) dan **M-** (Memory Minus) yang berfungsi menambahkan atau mengurangi angka saat ini dari nilai memori yang tersimpan.*

### 4. Reset Memori (MC)



*Tampilan yang menunjukkan saat tombol **MC** (Memory Clear) ditekan, mengembalikan nilai memori (**Memory (M): 0**) menjadi nol.*

### 5. Tampilan Responsif



*Menampilkan bagaimana desain kalkulator secara otomatis menyesuaikan (**responsive**) ketika diakses melalui perangkat **mobile** (smartphone), dengan elemen UI yang tetap terorganisir dan mudah diakses.*

---

## ⚙️ Panduan Instalasi dan Penggunaan

Karena proyek ini hanya menggunakan HTML, CSS, dan JavaScript murni tanpa *framework* atau *library* pihak ketiga, penggunaannya sangat mudah.

### 1. Instalasi Lokal
1.  **Clone Repository** (Jika menggunakan Git) atau unduh file `TugasAkhir5.html`.
2.  **Buka File:** Cukup buka file `TugasAkhir5.html` menggunakan *browser* web modern (Chrome, Firefox, Edge, dll.).

### 2. Penggunaan
* **Angka & Operator:** Klik tombol angka dan operator pada layar, atau gunakan tombol keyboard yang sesuai.
* **Reset:** Gunakan tombol **C** (Clear All) untuk mereset seluruh operasi dan riwayat.
* **Hapus Entri:** Gunakan tombol **CE** (Clear Entry) untuk mereset angka yang sedang diketik, atau gunakan tombol `Backspace` pada keyboard.
* **Memori:** Gunakan **M+, M-, MR, MC** untuk berinteraksi dengan nilai memori yang ditampilkan di bagian bawah kalkulator.

---

## 👨‍💻 Kontributor

* **Akso** (Mahasiswa Teknik Informatika, Angkatan 2023) - Ide dan Implementasi Proyek
