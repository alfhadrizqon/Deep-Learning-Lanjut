# Tugas 2: Deep Learning Lanjut - Neural Style Transfer dengan VGG19

Proyek ini adalah implementasi **Neural Style Transfer** (NST) menggunakan **TensorFlow** dan **Keras** pada notebook Google Colab. NST adalah teknik yang menggabungkan konten (struktur) dari satu gambar dengan gaya (tekstur, warna) dari gambar lainnya.

Notebook utama yang digunakan adalah `Tugas2_DeepLearningLanjut.ipynb`.

---

## 🚀 Fitur Utama

* **Model VGG19:** Menggunakan model VGG19 yang sudah dilatih (pretrained) sebagai *feature extractor*.
* **Loss Function Hybrid:** Implementasi *loss function* yang menggabungkan **Content Loss**, **Style Loss** (menggunakan Gram Matrix), dan **Total Variation Loss**.
* **Optimasi Gambar:** Menggunakan teknik optimasi iteratif untuk memodifikasi gambar output sampai *loss* diminimalkan.
* **Integrasi Colab:** Dirancang untuk dijalankan di Google Colab dengan integrasi Google Drive.

---

## 🛠️ Persyaratan dan Instalasi

Proyek ini memerlukan *library* Deep Learning dan *image processing*.

1.  **Lingkungan:** Disarankan menggunakan **Google Colab** dengan akselerator **GPU** (Runtime > Change runtime type > Pilih GPU).
2.  **Kebutuhan Python:**
    ```bash
    pip install tensorflow
    pip install numpy
    pip install pillow
    ```

### **Langkah-Langkah Menjalankan:**

1.  **Kloning Repositori:**
    ```bash
    git clone [https://github.com/](https://github.com/)[Username Anda]/[Nama Repositori Anda].git
    cd [Nama Repositori Anda]
    ```
2.  **Siapkan Gambar:** Letakkan gambar konten (`content.jpg`) dan gambar gaya (`style.jpg`) Anda di folder `/images` atau sesuaikan path di dalam *notebook*.
3.  **Buka di Colab:** Buka `Tugas2_DeepLearningLanjut.ipynb` di Google Colab.
4.  **Jalankan Cell:** Pastikan Anda menjalankan *cell* **Koneksi ke Google Drive** dan memberikan otorisasi akses agar *notebook* dapat membaca dan menyimpan file.
    ```python
    from google.colab import drive
    drive.mount('/content/drive')
    ```
5.  Jalankan semua *cell* secara berurutan.

---

## 🖼️ Hasil Neural Style Transfer

Berikut adalah hasil dari proses *Style Transfer* yang dilakukan:

| Gambar Konten | Gambar Gaya | Gambar Hasil |
| :---: | :---: | :---: |
| ![Gambar Konten](images/content.jpg) | ![Gambar Gaya](images/style.jpg) | ![Gambar Hasil](images/output.jpg) |

**Catatan:** Pastikan Anda telah membuat folder `images/` dan menempatkan file gambar di sana. Anda juga bisa menautkan ke gambar yang diunggah di GitHub secara langsung.

---

## 👤 Kontributor

Nama : Alfhad Rizqon Awalludin
NIM : 41236598

---
