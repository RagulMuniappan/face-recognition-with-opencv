## Face Recognition System using OpenCV

A real-time face recognition system that detects, trains, and recognizes human faces using a webcam and OpenCV.

---

### About the Project

This project demonstrates a computer vision–based face recognition system.  
It captures facial images through a webcam, creates a dataset, trains a recognition model, and identifies known or unknown faces in real time.

---

### Features

- Real-time face detection  
- Automatic dataset creation  
- Face recognition using FisherFace algorithm  
- Unknown person detection  
- Webcam-based live recognition  

---

### Technologies Used

- Python  
- OpenCV  
- NumPy  
- Haar Cascade Classifier  

---

### How to Run

1. Capture face images (create dataset):
   ```bash
   python create_data.py
   
2. Train the model and recognize faces:
   ```bash
   python main.py

3. Press ESC to exit the application.

---

### Project Folder Structure

face-recognition-with-opencv/
│
├── create_data.py                 # Script to capture face images
├── main.py                        # Training and face recognition script
├── haarcascade_frontalface_default.xml
├── datasets/                      # Stored face datasets
│   ├── Person_1/
│   ├── Person_2/
│   └── unknown/
├── README.md                      # Project documentation
└── requirements.txt               # Required libraries

---

### Working Principle

- Capture facial images using a webcam  
- Convert frames to grayscale for processing  
- Detect faces using Haar Cascade Classifier  
- Resize and store face images as dataset  
- Train FisherFace recognition model  
- Predict and recognize faces in real time  
- Label unknown faces when confidence is low  

---

### Applications

- Attendance management systems  
- Identity verification  
- Security and surveillance systems  
- Access control applications  
- Learning computer vision fundamentals  

---

### Output

- Real-time face detection with bounding boxes  
- Recognized faces labeled with names  
- Unknown faces detected and stored separately  

---

### License

This project is intended for educational purposes.
