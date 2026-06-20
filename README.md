\# Manipulasi Citra Digital Menggunakan OpenCV



\## Identitas Mahasiswa



\- \*\*Nama\*\* : Zahra Arayanindra Arum Samudra

\- \*\*NIM\*\* : 452024618068

\- \*\*Program Studi\*\* : Teknik Informatika

\- \*\*Mata Kuliah\*\* : Pengolahan Sinyal Digital



\---



\## Deskripsi Project



Project ini merupakan implementasi berbagai teknik manipulasi citra digital menggunakan Python dan OpenCV. Eksperimen dilakukan pada dua citra yaitu gambar kucing dan gambar anjing untuk mempelajari proses pengolahan citra dasar seperti konversi warna, resize citra, image blending, image negative, transformasi logaritmik, dan transformasi gamma.



\---



\## Citra yang Digunakan



\### Image 1

\- Nama file : `image1.jpg`

\- Objek : Kucing



\### Image 2

\- Nama file : `image2.jpg`

\- Objek : Anjing



\---



\## Library yang Digunakan



Project ini menggunakan beberapa library Python sebagai berikut:



\- OpenCV (cv2)

\- NumPy

\- Matplotlib



\---



\## Cara Menjalankan Notebook



1\. Clone repository ini



```bash

git clone https://github.com/zhraarayaa/manipulasi-citra-digital.git

```



2\. Masuk ke folder project



```bash

cd manipulasi-citra-digital

```



3\. Install dependency



```bash

pip install -r requirements.txt

```



4\. Buka folder notebook



```bash

notebook/image\_manipulation.ipynb

```



5\. Jalankan seluruh cell secara berurutan.



\---



\## Struktur Folder Project



```text

manipulasi-citra-digital/

│

├── notebook/

│   └── Tugas\_Manipulasi\_Citra.ipynb

│

├── images/

│   ├── image1.jpg

│   └── image2.jpg

│

├── report/

│   └── Laporan\_Manipulasi Citra Digital Menggunakan OpenCV\_Zahra Araya\_452024618068\_C1.pdf

│

├── README.md

│

└── requirements.txt

```



\---



\## Ringkasan Hasil Eksperimen



\### 1. Membaca dan Menampilkan Citra

Dua citra berhasil dibaca menggunakan OpenCV dan ditampilkan menggunakan Matplotlib setelah dilakukan konversi warna dari BGR ke RGB.



\### 2. Resize Citra

Kedua citra berhasil diubah ukurannya menjadi dimensi yang sama sehingga dapat digunakan pada proses image blending.



\### 3. Image Blending

Eksperimen blending dilakukan menggunakan beberapa kombinasi bobot alpha dan beta. Hasil menunjukkan bahwa perubahan bobot memengaruhi dominasi masing-masing citra pada hasil akhir.



\### 4. Image Negative

Transformasi negatif berhasil membalik nilai intensitas pixel sehingga area terang berubah menjadi gelap dan area gelap berubah menjadi terang.



\### 5. Transformasi Logaritmik

Transformasi logaritmik mampu meningkatkan detail pada area gelap sehingga objek yang sebelumnya kurang terlihat menjadi lebih jelas.



\### 6. Transformasi Gamma

Transformasi gamma berhasil mengatur tingkat kecerahan citra. Nilai gamma kurang dari satu membuat citra lebih terang, sedangkan nilai gamma lebih dari satu membuat citra lebih gelap.



\---



\## Kesimpulan



Berdasarkan hasil eksperimen, setiap teknik manipulasi citra memiliki fungsi yang berbeda. Image blending digunakan untuk menggabungkan dua citra, image negative digunakan untuk membalik intensitas pixel, transformasi logaritmik digunakan untuk meningkatkan detail pada area gelap, dan transformasi gamma digunakan untuk mengatur tingkat kecerahan citra secara fleksibel.



Melalui project ini dapat dipahami bahwa manipulasi citra digital merupakan bagian penting dalam pengolahan citra karena dapat meningkatkan kualitas visual maupun mempersiapkan citra untuk proses analisis lebih lanjut.

