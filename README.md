# Proyek Klasifikasi Gambar: Cat & Dogs

## Deskripsi Proyek
Proyek ini adalah implementasi model **Klasifikasi Gambar** menggunakan **Deep Learning** (Jaringan Saraf Tiruan Konvolusional / CNN) dan teknik **Transfer Learning** untuk mengklasifikasikan gambar sebagai **Kucing (Cats)** atau **Anjing (Dogs)**.
link dataset: https://www.kaggle.com/datasets/d4rklucif3r/cat-and-dogs

Proyek ini bertujuan untuk membangun model dengan akurasi tinggi menggunakan arsitektur modern seperti MobileNetV2 atau EfficientNetB0.

## Fitur Utama
* **Klasifikasi Biner:** Membedakan antara dua kelas gambar: Kucing dan Anjing.
* **Dataset:** Menggunakan dataset publik "Cat and Dogs" yang diunduh dari Kaggle.
* **Arsitektur Model:** Menggunakan **Transfer Learning** dengan *backbone* **MobileNetV2** (atau model pre-trained lainnya) yang dimodifikasi dengan lapisan *fully connected* kustom.
* **Preprocessing:** Implementasi **Image Data Generator** untuk augmentasi data dan normalisasi gambar.
* **Penyimpanan Model:** Model dilatih dan disimpan dalam format **Keras (.h5)**. Model juga dikonversi ke format **TensorFlow Lite (.tflite)** (atau **TensorFlow.js**) untuk kemudahan deployment.

## Instalasi
Untuk menjalankan proyek ini, Anda memerlukan lingkungan Python 3.x.

### 1. Kloning Repositori
```bash
git clone [https://github.com/Izukunn/proyek-klasifikasi-gambar](https://github.com/Izukunn/proyek-klasifikasi-gambar)
cd proyek-klasifikasi-gambar
