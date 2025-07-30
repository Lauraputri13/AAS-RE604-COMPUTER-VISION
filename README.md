# AAS_RE604_COMPUTER_VISION

# OCR License Plate Evaluation with LMStudio & using Gemma 3 4b Models

Proyek ini merupakan pengembangan sistem OCR (Optical Character Recognition) untuk membaca plat nomor kendaraan dari gambar, dengan memanfaatkan model Visual Language Model (VLM) terbaru bernama Gemma 3 4b yang dijalankan secara lokal melalui LMStudio API.

Sistem ini dirancang untuk secara otomatis:

* Membaca kumpulan gambar plat nomor dari sebuah folder.

* Melakukan inferensi atau prediksi teks plat nomor menggunakan model VLM.

* Menghitung Character Error Rate (CER) untuk mengevaluasi sejauh mana hasil prediksi mendekati label sebenarnya (ground truth).

* Menyimpan seluruh hasil evaluasi dalam format file CSV agar dapat dianalisis lebih lanjut secara statistik atau visualisasi.

Dengan kemudahan integrasi dari LMStudio, pengguna tidak perlu menjalankan model secara manual melalui command line. Semua proses inferensi dapat dipanggil langsung dari skrip Python menggunakan LMStudio API, sehingga lebih efisien dan mudah diotomatisasi.

## Fitur Utama yang digunakan
1. Inferensi OCR Berbasis VLM dengan LMStudio API
2. Ground Truth Otomatis dari Nama File Gambar
3. Perhitungan Character Error Rate (CER) Lengkap
4. Penyimpanan Hasil Evaluasi ke Format CSV
