# Deteksi Rumah dan Bangunan (House & Building Detector)
**ID Grup: LAI25-RM116**

[![Python](https://img.shields.io/badge/Python-3.1%2B-blue)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)](https://www.tensorflow.org/)

<a href="https://colab.research.google.com/drive/1COYgc0WgMcnSstw6ELwNFKx2U6-A_L5P?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

---

## 📖 Tentang Proyek

Proyek ini memperkenalkan sebuah sistem yang mampu **mendeteksi rumah dan bangunan lain** pada citra udara dan satelit. Tujuan utamanya adalah untuk membantu tim survei lapangan dalam mengidentifikasi bangunan yang mungkin terlewat, terutama di area dengan **vegetasi yang lebat** atau halangan visual lainnya.

Dengan mengimplementasikan model **Convolutional Neural Network (CNN)**, sistem ini dapat menganalisis citra dan memberikan gambaran yang lebih detail mengenai target survei. Harapannya, proyek ini dapat mendukung upaya perencanaan pembangunan yang lebih berkelanjutan dan distribusi layanan publik yang lebih merata di Indonesia.

---

## ✨ Fitur Utama

* **Deteksi Otomatis**: Secara otomatis mengidentifikasi lokasi rumah dan bangunan dari citra udara.
* **Fokus pada Area Sulit**: Dirancang untuk dapat bekerja optimal di wilayah dengan tutupan vegetasi yang signifikan.
* **Alat Bantu Survei**: Menghasilkan output visual (peta dengan *bounding box*) yang dapat digunakan sebagai panduan awal oleh tim survei.
* **Model CNN**: Dibangun menggunakan arsitektur Convolutional Neural Network untuk tugas deteksi objek.

---

## 🚀 Memulai

Cara termudah untuk menjalankan proyek ini adalah melalui Google Colaboratory. Semua dependensi, kode, dan langkah-langkah eksekusi telah disiapkan dalam satu notebook.

### Buka di Google Colab

Cukup klik tautan di bawah ini untuk membuka notebook, dan ikuti petunjuk yang ada di dalamnya.

> **[Link Notebook: Building_Detection.ipynb](https://colab.research.google.com/drive/1COYgc0WgMcnSstw6ELwNFKx2U6-A_L5P?usp=sharing)**

### Langkah-langkah Umum:
1.  Klik link Colab di atas.
2.  Jalankan sel kode secara berurutan dari atas ke bawah.
3.  Notebook akan menangani proses instalasi dependensi, pemuatan dataset, pelatihan model, dan evaluasi.
4.  Pastikan untuk menghubungkan ke *runtime* yang menyediakan GPU untuk proses pelatihan yang lebih cepat.

---

## 📊 Dataset

Dataset yang digunakan untuk melatih model ini adalah **citra udara/satelit** yang telah diberi label. Setiap gambar memiliki anotasi berupa *bounding box* yang menandai lokasi bangunan. Dataset dibagi menjadi dua bagian utama yang terdapat dalam folder `data/`:
* `train`: Berisi data untuk melatih model.
* `val`: Berisi data untuk memvalidasi performa model selama pelatihan.

---

## 💻 Teknologi yang Digunakan

* **Python**: Bahasa pemrograman utama.
* **TensorFlow & Keras**: Kerangka kerja utama untuk membangun dan melatih model deep learning.
* **OpenCV**: Untuk pemrosesan gambar dan augmentasi data.
* **NumPy**: Untuk operasi numerik dan manipulasi array.
* **Matplotlib**: Untuk visualisasi data dan hasil deteksi.

---

## 👥 Tim Kami

Proyek ini dikerjakan oleh:

| Nama                    | NIM          | Universitas                     |
| ----------------------- | ------------ | ------------------------------- |
| **Ahmad Faisal** | A757YAM027   | Universitas Muhammadiyah Makassar |
| **Ahmed Diaz Ravan** | A008YBF037   | Universitas Gadjah Mada         |

---

## 👨‍🏫 Advisor

* Ariyadi

---
