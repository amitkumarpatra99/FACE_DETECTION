# FACE_DETECTION 👤

A **Face Detection project** built using **Python and OpenCV** that detects human faces from images and real-time webcam video.  
This project demonstrates the use of computer vision techniques for face detection using a pre-trained Haar Cascade classifier.

---

## 🚀 Features

- Detects human faces accurately
- Works with **images** and **live webcam feed**
- Uses OpenCV Haar Cascade classifier
- Draws bounding boxes around detected faces
- Simple, beginner-friendly implementation

---

## 🛠️ Tech Stack

- **Python**
- **OpenCV (cv2)**
- **Haar Cascade Classifier**

---

## 📁 Project Structure

```
FACE_DETECTION/
├── Face Recognaition # Main Python script
├── haarcascade_frontalface_default.xml
├── requirements.txt
├── .gitignore
└── README.md
```

> ⚠️ If your file names or folders differ, update the structure accordingly.

---

## 🧠 How Face Detection Works

This project uses **Haar Cascade**, a machine learning-based approach where a cascade function is trained using positive and negative images.

### Steps:
1. Load Haar Cascade classifier
2. Read image or capture video from webcam
3. Convert frames to grayscale
4. Detect faces using `detectMultiScale`
5. Draw rectangles around detected faces

This method is fast and suitable for real-time applications.

---

## 🔧 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/amitkumarpatra99/FACE_DETECTION.git
cd FACE_DETECTION
```

### 2️⃣ Install Dependencies
If `requirements.txt` exists:

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install opencv-python
```

---

## ▶️ Usage

### 📸 Face Detection from Image
```bash
python "Face Recognaition" --image path/to/image.jpg
```
The program will display the image with detected faces highlighted.

### 🎥 Real-Time Face Detection (Webcam)
```bash
python "Face Recognaition"
```
- Webcam will start automatically
- Faces will be detected in real time
- Press `q` to exit

### 📷 Sample Output
```
+----------------------+
|  [ Face Detected ]   |
|  ████████████████    |
|                      |
+----------------------+
```
*(Add screenshots here if available)*

---

## 📦 Dependencies

| Package | Description |
| :--- | :--- |
| `opencv-python` | Computer vision & face detection |

---

## 🔮 Future Improvements

- [ ] Face recognition (identify person)
- [ ] Multiple face tracking
- [ ] Save detected faces to files
- [ ] GUI interface using Tkinter / PyQt
- [ ] Deep learning-based detection (CNN / DNN)

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Submit a Pull Request

---

## 📄 License

This project is open-source and free to use for learning and development purposes.

*(Add license if applicable – MIT recommended)*

---

## 👨‍💻 Author

**Amit Kumar Patra**  
GitHub: [amitkumarpatra99](https://github.com/amitkumarpatra99)
Website: [mrpatra](https://mrpatra.vercel.app)
