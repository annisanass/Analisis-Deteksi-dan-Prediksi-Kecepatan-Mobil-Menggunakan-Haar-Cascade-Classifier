🚗 Analisis Deteksi dan Prediksi Kecepatan Mobil dari Pemrosesan Video Menggunakan Haar Cascade Classifier (Google Colab)

Proyek ini merupakan implementasi sistem computer vision untuk mendeteksi kendaraan serta menganalisis dan memprediksi kecepatan mobil dari video menggunakan metode Haar Cascade Classifier. Seluruh proses pengolahan dilakukan secara praktis melalui Google Colab, sehingga tidak memerlukan instalasi lokal yang kompleks.

🔍 Latar Belakang

Dalam pengembangan Intelligent Transportation System (ITS), diperlukan solusi yang efisien untuk memantau kecepatan kendaraan. Dengan memanfaatkan video sebagai input, sistem ini mampu mendeteksi dan menghitung kecepatan kendaraan secara otomatis tanpa perangkat sensor tambahan.

⚙️ Metodologi

Input Video di Google Colab

Video diunggah melalui Colab atau diakses dari Google Drive.

Deteksi Kendaraan

Menggunakan Haar Cascade Classifier dari OpenCV untuk mendeteksi mobil pada setiap frame.

Tracking Pergerakan

Objek kendaraan yang terdeteksi dilacak berdasarkan posisi antar frame.

Perhitungan Kecepatan

Kecepatan dihitung dari perubahan posisi objek terhadap waktu (berdasarkan FPS video).

Prediksi Kecepatan

Data kecepatan dapat dianalisis lebih lanjut menggunakan metode statistik atau machine learning sederhana.

🧠 Tools & Library

Python

OpenCV

Google Colab

NumPy

Matplotlib 

Pandas

💻 Keunggulan Menggunakan Google Colab

Tidak perlu instalasi software tambahan

Dapat dijalankan di cloud

Mendukung GPU (opsional)

Mudah berbagi dan kolaborasi

🎯 Tujuan

Mendeteksi kendaraan secara otomatis dari video

Menghitung kecepatan kendaraan berbasis frame video

Mengimplementasikan sistem berbasis cloud menggunakan Google Colab

📊 Output

Video hasil deteksi dengan bounding box

Informasi kecepatan kendaraan

Grafik analisis kecepatan

🚀 Cara Menjalankan

Buka file notebook di Google Colab

Upload video atau hubungkan ke Google Drive

Jalankan setiap cell secara berurutan

Lihat hasil deteksi dan perhitungan kecepatan

🔮 Pengembangan Selanjutnya

Menggunakan metode deteksi berbasis deep learning (YOLO, SSD)

Peningkatan akurasi tracking

Implementasi real-time menggunakan CCTV

Integrasi dengan sistem smart city
