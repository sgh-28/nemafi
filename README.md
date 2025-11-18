# NEMA NET

NEMA NET adalah aplikasi web yang menyediakan layanan internet. Aplikasi ini memungkinkan pengguna untuk mendaftar, memilih paket internet, dan mengelola akun mereka. Selain itu, aplikasi ini juga memiliki dasbor untuk admin dan teknisi untuk mengelola pengguna, paket, dan tugas.

## Apa yang Telah Dikerjakan

* **Struktur Proyek**: Membangun proyek Next.js dengan struktur folder yang terorganisir, termasuk komponen, halaman, dan logika backend.
* **UI/UX**: Mendesain antarmuka pengguna yang bersih dan modern menggunakan `shadcn/ui` dan `tailwindcss`, dengan dukungan untuk mode terang dan gelap.
* **Fitur Multi-bahasa**: Mengimplementasikan dukungan untuk bahasa Inggris dan Indonesia.
* **Rekomendasi Paket AI**: Mengintegrasikan model AI untuk merekomendasikan paket internet kepada pengguna berdasarkan kebutuhan mereka.
* **Dasbor Berbasis Peran**: Membuat dasbor terpisah untuk pelanggan, admin, dan teknisi, masing-masing dengan fungsionalitas yang relevan.
* **Halaman Responsif**: Memastikan aplikasi berfungsi dengan baik di berbagai ukuran layar, dari desktop hingga seluler.

## Instalasi

1.  ***Clone* Repositori**:
    ```bash
    git clone git@github.com:janbu12/nemanet-fe.git
    cd nemanet-fe
    ```

2.  **Instal Dependensi**:
    ```bash
    npm install
    ```

3.  **Jalankan Aplikasi**:
    ```bash
    npm run dev
    ```

## Perintah yang Tersedia

* `npm run dev`: Menjalankan *server* pengembangan.
* `npm run build`: Membuat *build* aplikasi untuk produksi.
* `npm run start`: Menjalankan *build* produksi.
* `npm run lint`: Menjalankan *linter* untuk memeriksa kesalahan kode.