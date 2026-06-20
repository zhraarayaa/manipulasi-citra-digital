# 📸 Manipulasi Citra Digital Menggunakan OpenCV

---

## 👩‍🎓 Identitas Mahasiswa

| Keterangan | Data |
|------------|------|
| **Nama** | Zahra Arayanindra Arum Samudra |
| **NIM** | 452024618068 |
| **Program Studi** | Teknik Informatika |
| **Mata Kuliah** | Pengolahan Sinyal Digital |

---

## 📖 Deskripsi Project

Project ini merupakan implementasi berbagai teknik **manipulasi citra digital menggunakan OpenCV** pada dua citra berbeda, yaitu gambar **kucing** dan **anjing**.

Beberapa teknik yang diterapkan meliputi:

- Membaca dan menampilkan citra
- Konversi warna BGR ke RGB
- Resize citra
- Image Blending
- Image Negative
- Transformasi Logaritmik
- Transformasi Gamma

---

## 🖼️ Citra yang Digunakan

| File | Objek |
|------|--------|
| image1.jpg | 🐱 Kucing |
| image2.jpg | 🐶 Anjing |

---

## 📚 Library yang Digunakan

```python
import cv2
import numpy as np
import matplotlib.pyplot as plt
```

- OpenCV
- NumPy
- Matplotlib

---

## 🚀 Cara Menjalankan Project

### 1. Clone Repository

```bash
git clone https://github.com/zhraarayaa/manipulasi-citra-digital.git
```

### 2. Masuk ke Folder Project

```bash
cd manipulasi-citra-digital
```

### 3. Install Dependency

```bash
pip install -r requirements.txt
```

### 4. Jalankan Notebook

Buka file:

```text
notebook/image_manipulation.ipynb
```

Kemudian jalankan seluruh cell secara berurutan.

---

## 📂 Struktur Folder

```text
manipulasi-citra-digital/
│
├── notebook/
│   └── Tugas_Manipulasi_Citra.ipynb
│
├── images/
│   ├── image1.jpg
│   └── image2.jpg
│
├── report/
│   └── Laporan_Manipulasi Citra Digital Menggunakan OpenCV_Zahra Araya_452024618068_C1.pdf
│
├── README.md
│
└── requirements.txt
```

---

## 🧪 Ringkasan Hasil Eksperimen

### 🔹 Membaca dan Menampilkan Citra

Dua citra berhasil dibaca menggunakan OpenCV dan ditampilkan menggunakan Matplotlib setelah dilakukan konversi warna dari format BGR ke RGB.

### 🔹 Resize Citra

Ukuran kedua citra berhasil diseragamkan sehingga dapat digunakan pada proses image blending.

### 🔹 Image Blending

Eksperimen blending dilakukan menggunakan tiga kombinasi bobot:

| Alpha | Beta |
|---------|---------|
| 0.2 | 0.8 |
| 0.5 | 0.5 |
| 0.8 | 0.2 |

Perubahan bobot memengaruhi dominasi masing-masing citra pada hasil akhir.

### 🔹 Image Negative

Operasi negatif berhasil membalik nilai intensitas pixel sehingga area terang berubah menjadi gelap dan area gelap berubah menjadi terang.

### 🔹 Transformasi Logaritmik

Transformasi logaritmik mampu meningkatkan detail pada area gelap dan memperjelas objek yang sebelumnya kurang terlihat.

### 🔹 Transformasi Gamma

Gamma correction berhasil mengatur tingkat kecerahan citra.

| Gamma | Efek |
|--------|--------|
| 0.5 | Lebih terang |
| 1 | Tidak berubah |
| 2 | Lebih gelap |
| 2.5 | Semakin gelap |

---

## 📌 Kesimpulan

Setiap teknik manipulasi citra memiliki fungsi yang berbeda:

- **Image Blending** → Menggabungkan dua citra.
- **Image Negative** → Membalik intensitas pixel.
- **Transformasi Logaritmik** → Memperjelas area gelap.
- **Transformasi Gamma** → Mengatur tingkat kecerahan citra.

Melalui project ini dapat dipahami bahwa manipulasi citra digital berperan penting dalam meningkatkan kualitas visual serta mendukung proses analisis citra pada berbagai bidang aplikasi.

---

⭐ Repository dibuat untuk memenuhi tugas mata kuliah **Pengolahan Sinyal Digital**.
