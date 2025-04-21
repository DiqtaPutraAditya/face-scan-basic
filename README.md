#  Real-Time Face Detection with OpenCV

Sebuah project sederhana untuk mendeteksi wajah secara real-time menggunakan **Python** dan **OpenCV**.

---

## 📸 Deskripsi

### 1. Start  
Memulai program dan inisialisasi.
### 2. Load Haar Cascade  
Mengimpor model pre-trained (`haarcascade_frontalface_default.xml`) untuk deteksi wajah.
### 3. Capture Image  
Mengambil gambar dari webcam secara real-time.
### 4. Convert to Grayscale  
Mengubah gambar ke skala abu-abu agar lebih ringan untuk diproses.
### 5. Face Detection  
Mendeteksi wajah pada gambar dengan memindai area menggunakan Haar-like features.
### 6. Deteksi Berhasil?  
Jika ada wajah terdeteksi, lanjut; jika tidak, ulangi.
### 7. Gambar Kotak di Wajah  
Menggambar kotak di sekitar wajah yang terdeteksi.
### 8. Tampilkan Gambar  
Menampilkan hasil gambar dengan kotak wajah ke layar.
### 9. Loop  
Proses diulang untuk frame berikutnya.

---

## 🧠 Fitur

- Deteksi wajah secara real-time via webcam
- Menampilkan bounding box di sekitar wajah
- Menggunakan Haar Cascade dari OpenCV

---

## 🛠️ Tools & Library

- Python 3.10+
- OpenCV
- Haar Cascade Classifier

---

## 🧪 Cara Menjalankan

1. Clone repo ini:
   ```bash
   git clone https://github.com/DiqtaPutraAditya/face-scan-basic.git
   cd face-scan-basic
   
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   
3. Jalankan program:
   ```bash
   python main.py

## License

This project uses a Haar Cascade classifier file (`haarcascade_frontalface_default.xml`) provided by [OpenCV](https://opencv.org/) under the Intel Open Source Computer Vision Library License.
