# 🏹 Wayang Image Classification with CNN

![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow) 
![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![License](https://img.shields.io/badge/License-MIT-green)

Proyek ini mengembangkan model **Convolutional Neural Network (CNN)** untuk **mengklasifikasikan gambar wayang** ke dalam berbagai kategori.  
Model dilatih dan disiapkan untuk berbagai platform: web, mobile, dan server.

---

## 📁 Struktur Proyek
saved_model/        # Model tersimpan dalam format TensorFlow SavedModel </br>
  ├── fingerprint.pb </br>
  ├── saved_model.pb </br>
  └── variables.index </br>

tfjs_model/         # Model untuk TensorFlow.js </br>
  ├── group1-shard1of7.bin </br>
  ├── ... </br>
  └── model.json</br>

tflite/             # Model untuk TensorFlow Lite </br>
  ├── labels.txt </br>
  └── model.tflite </br>

notebook.ipynb      # Notebook untuk training dan eksperimen </br>
notebook.py         # Script Python untuk pipreqs </br>
Readme.md           # Dokumentasi proyek </br>
requirements.txt    # Daftar dependensi Python </br>


---

## ⚡ Instalasi Cepat

1. **Clone repository**
    ```bash
    git clone <my_repo>
    cd <nama-folder-repo>
    ```

2. **Buat environment virtual (opsional tapi direkomendasikan)**
    ```bash
    python -m venv env
    source env/bin/activate     # Linux/Mac
    env\Scripts\activate        # Windows
    ```

3. **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

---

## 🧠 Cara Menggunakan

### Training
- Buka dan jalankan `notebook.ipynb`

### Inferensi / Prediksi
- Gunakan model yang tersedia (`saved_model`, `tflite`, atau `tfjs_model`) sesuai kebutuhan:
  - **SavedModel**: untuk deployment server
  - **TFLite**: untuk deployment di mobile apps
  - **TFJS**: untuk deployment di web frontend

---

## 🏷️ Dataset

- Dataset berisi gambar karakter wayang dalam berbagai pose dan jenis.
- Label tersedia di file `labels.txt`.

---

## 📸 Contoh Prediksi

> Misal kamu punya gambar `gatotkaca.jpg`, prediksi output:

| Gambar Input            | Hasil Prediksi |
|:------------------------|:---------------|
| ![anoman](https://github.com/user-attachments/assets/40194634-0574-4e95-8340-06c813f94e83) | **Anoman** |

---

## 🛠️ Teknologi yang Digunakan

- **Python 3.x**
- **TensorFlow 2.x**
- **TensorFlow Lite**
- **TensorFlow.js**
- **NumPy**, **Pandas**, **Matplotlib**

---

## 🙋‍♂️ Author

- **[Rizki Rahman Maulana]**  
  📫 Kontak: [rrrizki2002@gmail.com] (opsional)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).


