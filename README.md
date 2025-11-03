# 🧠 Implementasi Arsitektur Convolutional Neural Network untuk Deteksi dan Klasifikasi Citra Aksara Sunda

Proyek ini merupakan implementasi dari penelitian tugas akhir dengan judul **"Implementasi Arsitektur Convolutional Neural Network untuk Deteksi dan Klasifikasi Citra Aksara Sunda"**.  
Penelitian ini berfokus pada pengembangan sistem berbasis **Deep Learning (CNN)** untuk mengenali dan mengklasifikasikan citra **Aksara Sunda**, sebagai bentuk kontribusi terhadap pelestarian aksara daerah melalui teknologi kecerdasan buatan.

---

## 📚 Deskripsi Proyek

Aksara Sunda merupakan salah satu warisan budaya Nusantara yang saat ini mulai jarang digunakan dalam kehidupan sehari-hari. Seiring berkembangnya teknologi, diperlukan inovasi digital untuk membantu pelestarian aksara tersebut.  
Proyek ini mengimplementasikan **Convolutional Neural Network (CNN)** untuk melakukan **deteksi dan klasifikasi citra aksara Sunda**, dengan hasil akhir berupa sistem yang mampu mengenali karakter dan menampilkannya dalam bentuk teks Latin.

---

## 🎯 Tujuan Penelitian

1. Mengimplementasikan arsitektur CNN dalam membangun model klasifikasi citra aksara Sunda.  
2. Menganalisis tingkat akurasi model CNN dalam mengklasifikasikan citra aksara Sunda.  
3. Mengembangkan prototipe aplikasi sederhana berbasis web untuk pengujian model.

---

## 🧩 Fitur Utama

- Preprocessing citra (resize, grayscaling, dan augmentasi).  
- Training dan evaluasi model CNN dengan berbagai parameter (filter, layer, optimizer, learning rate).  
- Visualisasi hasil pelatihan menggunakan matplotlib.  
- Implementasi model ke aplikasi web berbasis Flask.  
- Deteksi huruf tunggal dan penggabungan hasil deteksi menjadi kata sederhana.  

---

## 🏗️ Arsitektur CNN

Model CNN yang digunakan terdiri dari beberapa lapisan:
- **Convolutional Layer** untuk ekstraksi fitur citra.  
- **ReLU Activation** untuk menghilangkan nilai negatif dan mempercepat konvergensi.  
- **MaxPooling Layer** untuk mengurangi dimensi dan mencegah overfitting.  
- **Fully Connected Layer** untuk proses klasifikasi.  
- **Softmax Output** untuk menghasilkan probabilitas dari setiap kelas aksara Sunda.

---

## 🧮 Dataset

Dataset yang digunakan terdiri dari citra **Aksara Sunda Ngalagena dan Swara** dalam format `.png`.  
Data diperoleh dari hasil digitalisasi dan diproses melalui tahapan:
- Resize menjadi 64×64 piksel.  
- Konversi ke grayscale.  
- Data augmentation (rotasi, translasi, dan flipping).  

---

## ⚙️ Teknologi yang Digunakan

- **Python 3.10+**  
- **TensorFlow / Keras**  
- **OpenCV**  
- **NumPy & Pandas**  
- **Matplotlib**  
- **Flask**  

---
