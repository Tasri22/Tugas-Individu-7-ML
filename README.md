# OpenCV Python Tutorial — Image & Video Processing

Tutorial dasar **Computer Vision menggunakan OpenCV di Python**.

Project ini berisi notebook pembelajaran OpenCV dari dasar hingga dapat membaca gambar, memproses pixel, hingga menangkap video dari webcam.

---

## 📚 Materi yang Dipelajari

Pada notebook ini kita mempelajari:

- Pengenalan OpenCV
- Struktur citra digital
- Membaca gambar menggunakan OpenCV
- Menampilkan gambar dengan OpenCV dan Matplotlib
- Mengakses pixel dan channel warna
- Konversi warna BGR → RGB
- NumPy slicing pada citra
- Menyimpan gambar
- Membaca video
- Mengambil screenshot dari video
- Capture foto dari webcam
- Record video dari webcam

---

## 🧠 Konsep Dasar Citra Digital

Citra digital terdiri dari kumpulan **pixel** yang tersusun dalam bentuk matrix.

Contoh struktur citra:


(height, width, channel)


Contoh:


(512, 512, 3)


Artinya:

- Height = 512 pixel
- Width = 512 pixel
- Channel = 3 (BGR)

OpenCV menggunakan format warna **BGR (Blue, Green, Red)**.

---

## 🛠 Teknologi yang Digunakan

- Python
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📂 Struktur Project


Tugas-Individu-7-ML/
│
├── Python_Individu7.ipynb
├── results/
│ └── saved_lena.jpg
├── videos/
│ └── video.mp4
└── README.md


---

## 🚀 Cara Menjalankan Project

1. Install Python

2. Install dependency


pip install opencv-python numpy matplotlib


3. Jalankan Jupyter Notebook


jupyter notebook


4. Buka file notebook:


Python_Individu7.ipynb


---

## 🎥 Video Tutorial

Tutorial lengkap dapat ditonton di YouTube:


(https://youtu.be/xZxwv0G9EWI?si=Lb07i3mMXERpSxCQ)


---

## 📌 Topik yang Dibahas

| Topik | Fungsi |
|------|------|
| Baca gambar | `cv2.imread()` |
| Simpan gambar | `cv2.imwrite()` |
| Tampilkan gambar | `cv2.imshow()` |
| Konversi warna | `cv2.cvtColor()` |
| Akses pixel | `img[row, col]` |
| Akses channel | `img[:,:,0]` |
| Baca video | `cv2.VideoCapture()` |
| Simpan video | `cv2.VideoWriter()` |

---

## 🎯 Tujuan Project

Project ini dibuat untuk membantu:

- mahasiswa informatika
- pemula python
- pemula computer vision

agar dapat memahami dasar penggunaan **OpenCV secara praktis dan mudah dipahami**.

---

## ⭐ Support

Jika project ini membantu pembelajaran Anda:

⭐ Star repository ini  
👍 Subscribe channel YouTube  

---

## 👨‍💻 Author

Tasri Zulfitriyati (231001074)

---