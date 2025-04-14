# 🖼️ Natural Image Classification

Dataset: [Natural Images](https://www.kaggle.com/datasets/prasunroy/natural-images) dari Kaggle. 

Dataset ini terdiri dari 8 kelas gambar:

- 🛫 Airplane  
- 🚗 Car  
- 🐱 Cat  
- 🐶 Dog  
- 🌸 Flower  
- 🍎 Fruit  
- 🏍️ Motorbike  
- 🧍 Person  

Total terdapat sekitar 6.899 gambar dengan resolusi dan ukuran bervariasi.


---

## 🚀 Cara Instalasi & Setup

1. Clone repositori:
```bash
git clone https://github.com/username/natural-image-classification.git
```

2. Unggah Dataset ke Google Drive
   Pastikan dataset ZIP (natural.zip) berada di direktori Google Drive kamu, misalnya:
  ```/content/drive/MyDrive/Colab Notebooks/Klasifikasi Gambar/natural.zip```

3. Jalankan Kode di Google Colab
running file notebook.ipynb 

4. Menyimpan dan Mengekspor Model
Model disimpan dalam 3 format:

TensorFlow.js (tfjs_model)
TensorFlow Lite (tflite)
SavedModel (saved_model)
Model bisa digunakan untuk keperluan web, Android, atau inference lanjutan.

5. Inference (Prediksi Gambar Baru)
Gunakan fungsi predict_disease(img_path, model, class_labels) untuk melakukan prediksi terhadap gambar daun baru. Hasil prediksi akan menampilkan label serta confidence-nya dalam bentuk persen.

---

## 🧠 Hasil Model

Model klasifikasi ini bekerja dengan akurat dengan tingkat prediksi mencapai 98% akurasi! 🎯
Beberapa poin penting dari hasil pengujian:

✅ Prediksi Akurat — Gambar motor dikenali dengan tepat sebagai Motorbike 🏍️.

💯 Confidence Tinggi — Model memberikan keyakinan hingga 98%, menunjukkan keputusan yang sangat pasti!

📊 Probabilitas Lengkap — Tidak hanya menebak kelas, tapi juga menilai semua kemungkinan dengan cermat.

🔍 Transparansi Keputusan — Kita bisa memahami bagaimana model “berpikir” dan menyimpulkan jawaban.

📈 Evaluasi Kinerja — Confidence tinggi = keputusan andal. Confidence rendah? Saatnya perbaikan dan tuning!

🎉 Dengan performa sebaik ini, model sangat cocok digunakan untuk berbagai kebutuhan klasifikasi gambar di dunia nyata!
