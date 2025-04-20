#  Real-Time Face Detection with OpenCV

Sebuah project sederhana untuk mendeteksi wajah secara real-time menggunakan **Python** dan **OpenCV**.

---

## 📸 Diagram Explanation

graph TD
    A[Start] --> B[Load Haar Cascade Classifier]
    B --> C[Capture Image from Camera]
    C --> D[Convert to Grayscale]
    D --> E[Detect Faces using Haar Cascade]
    E --> F{Any Face Detected?}
    F -- Yes --> G[Draw Rectangle on Detected Face]
    F -- No --> H[No Face Found]
    G --> I[Display Result]
    H --> I
    I --> J[Loop to Next Frame / End]

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
   git clone https://github.com/username/face-detection-opencv-python.git
   cd face-detection-opencv-python
   
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   
3. Jalankan program:
   ```bash
   python main.py
