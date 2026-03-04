# 📌 Setup Environment Computer Vision

Nama: Alfadrian Januarsyah
NIM: 231001067
Kelas: Informatika C

# 🧠 Deskripsi

Tugas ini merupakan praktik setup environment Machine Learning menggunakan Anaconda sesuai tahap-tahap pada tutorial yang diberikan.

Fokus utama tugas ini adalah:

* Mengecek ketersediaan package OpenCV
* Membuat environment baru
* Mengaktifkan environment
* Melakukan pengujian import OpenCV

---

# 🛠 Tools yang Digunakan

* Anaconda
* Python 3.8
* OpenCV

---

# ⚙️ Langkah-Langkah Setup (Sesuai Tutorial)

## 1️⃣ Mengecek Package OpenCV

```bash
conda search opencv
```

Perintah ini digunakan untuk mencari dan memastikan package OpenCV tersedia pada repository Anaconda.

---

## 2️⃣ Melihat Informasi Conda

```bash
conda info
```

Perintah ini digunakan untuk melihat informasi konfigurasi dan environment yang tersedia.

---

## 3️⃣ Membuat Environment Baru

```bash
conda create --name TugasML_Tasri python=3.9
```

Environment ini dibuat untuk keperluan praktik Machine Learning.

---

## 4️⃣ Mengecek Daftar Environment

```bash
conda env list
```

Digunakan untuk memastikan environment `TugasML_Tasri` berhasil dibuat.

---

## 5️⃣ Melihat Daftar Package

```bash
conda list
```

Perintah ini digunakan untuk melihat package yang terinstall pada environment aktif.

---

## 6️⃣ Mengaktifkan Environment

```bash
conda activate TugasML_Tasri
```

Jika berhasil, maka akan muncul:

```
(TugasML_Tasri)
```

---

## 7️⃣ Test Python dan OpenCV

Masuk ke Python:

```bash
python
```

Kemudian lakukan pengujian:

```python
import cv2
cv2.__version__
```

Jika tidak terjadi error dan muncul versi OpenCV, maka instalasi berhasil.

---

# 📊 Analisis Singkat

## Analisis `conda search opencv`

Perintah ini digunakan untuk mengecek ketersediaan package OpenCV pada repository Anaconda. Dengan perintah ini, dapat dipastikan bahwa OpenCV tersedia dan dapat digunakan dalam environment yang akan dibuat.

---

## Analisis `conda info`

Perintah ini menampilkan informasi konfigurasi Conda, seperti lokasi instalasi, daftar environment, serta versi Conda yang digunakan. Hal ini memastikan bahwa Anaconda telah terpasang dengan benar.

---

## Analisis `conda create --name TugasML_Tasri python=3.9`

Perintah ini digunakan untuk membuat virtual environment baru dengan Python versi 3.9. Virtual environment berfungsi untuk memisahkan dependency project agar tidak terjadi konflik dengan environment lain.

---

## Analisis `conda env list`

Perintah ini digunakan untuk melihat daftar environment yang tersedia pada sistem. Jika `TugasML_Tasri` muncul, maka environment berhasil dibuat.

---

## Analisis `conda list`

Perintah ini digunakan untuk menampilkan daftar package yang terinstall pada environment aktif. Hal ini membantu memastikan library yang tersedia dalam environment.

---

## Analisis `conda activate TugasML_Tasri`

Perintah ini digunakan untuk mengaktifkan environment yang telah dibuat. Setelah aktif, seluruh proses instalasi dan eksekusi program akan berjalan dalam environment tersebut.

---

## Analisis `import cv2` dan `cv2.__version__`

Perintah `import cv2` digunakan untuk mengimpor library OpenCV ke dalam Python. Jika tidak terjadi error, berarti instalasi berhasil.

Perintah `cv2.__version__` digunakan untuk menampilkan versi OpenCV yang terpasang sebagai bukti bahwa library telah berhasil di-load dan siap digunakan.

---

# 📂 Struktur Repository

```
setup-computer-vision/
│
├── README.md
└── screenshot/
    ├── install_anaconda.png 
    ├── conda_search_opencv.png
    ├── conda_info.png
    ├── create_environment.png
    ├── env_list.png
    ├── conda_list.png
    ├── activate_environment.png
    └── test_import_cv2.png
```

---

# 🎯 Kesimpulan

Berdasarkan tahap-tahap yang telah dilakukan, environment `TugasML_Tasri` berhasil dibuat dan OpenCV dapat digunakan tanpa error.

Setup ini menjadi dasar untuk pengembangan program Computer Vision selanjutnya.

---

# Youtube Link : https://youtu.be/bVVCc6RrbNE?si=eZbwm9WQO5mwNAhi