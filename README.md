# Real-Time Face Detection using OpenCV

This project demonstrates a simple real-time face detection system using OpenCV and a webcam. It uses Haar Cascade Classifier to detect human faces in a video stream.

## 📸 Features

- Real-time face detection via webcam
- Uses Haar cascades (`haarcascade_frontalface_default.xml`)
- Draws a rectangle around detected faces
- Press `q` to exit the application

## 🧰 Requirements

- Python 3.x
- OpenCV

You can install OpenCV using pip:

```bash
pip install opencv-python
🚀 How to Run
Clone this repository:

bash
Copy code
git clone https://github.com/yourusername/face-detection-opencv.git
cd face-detection-opencv
Make sure you have the Haar cascade XML file in your directory. You can download it from the OpenCV GitHub repository or use the one provided.

Run the Python script:

bash
Copy code
python face_detect.py
A window will open showing your webcam feed. Detected faces will be highlighted with rectangles.

Press q to quit the program.

📂 File Structure
pgsql
Copy code
face-detection-opencv/
│
├── haarcascade_frontalface_default.xml
├── face_detect.py
└── README.md
📝 Notes
Make sure your webcam is enabled and not being used by another application.

The detection might not be perfect in low-light conditions or when the face is partially obscured.
