# DeepFace Emotion Detection

A beginner-friendly computer vision project that uses **Python, OpenCV, and DeepFace** to detect facial emotions through a live webcam feed.

## 📌 About

This project captures video from a webcam and uses DeepFace to analyze facial expressions and identify the dominant emotion of the detected face.

The detected emotion is displayed directly on the webcam window in real time.

## 🚀 Features

* Real-time webcam input
* Facial emotion analysis
* Emotion detection using DeepFace
* OpenCV-based video display
* Simple and beginner-friendly implementation

## 🛠️ Technologies Used

* **Python**
* **OpenCV**
* **DeepFace**

## 📂 Project Structure

```text
deepface-emotion-detection/
│
├── emotion_detection.py
├── README.md
├── requirements.txt
├── .gitignore
│
└── images/
    └── demo.png
```

## ⚙️ Installation

Make sure Python is installed on your computer.

Install the required libraries using:

```bash
pip install -r requirements.txt
```

Or install them individually:

```bash
pip install opencv-python deepface
```

## ▶️ How to Run

Run the Python program:

```bash
python emotion_detection.py
```

Make sure your computer has a working webcam.

The program will open a camera window and display the detected emotion.

Press **Q** to close the program.

## 🧠 How It Works

1. The webcam captures a live video stream.
2. OpenCV processes the video frames.
3. DeepFace analyzes the face in the frame.
4. The dominant emotion is identified.
5. The detected emotion is displayed on the video window.

## 📸 Demo

Add a screenshot of the project working here:

```markdown
![Emotion Detection Demo](images/demo.png)
```

## 🔮 Future Improvements

* Detect multiple faces at the same time
* Display emotion confidence percentages
* Improve the user interface
* Store detected emotions
* Create emotion statistics over time

## 📚 Learning Outcome

This project was created to explore basic computer vision and facial emotion analysis using Python libraries.

It helped me understand how to work with webcam input, OpenCV, and pre-built AI models through DeepFace.

## ⚠️ Note

This project is intended for learning and experimentation. Emotion detection from facial expressions is an automated inference and should not be treated as a definitive measure of a person's actual emotional state.
