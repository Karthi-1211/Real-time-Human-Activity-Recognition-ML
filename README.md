# 🏃‍♂️ Real-time Human Detection & Counting using OpenCV 🎯

## 📌 Project Overview  
This Python project implements **real-time human detection and counting** using **HOG (Histogram of Oriented Gradients) with SVM (Support Vector Machine)** in **OpenCV**. It can detect and count people in:  
- **Live webcam feed** 🎥  
- **Video files** 📹  
- **Images** 🖼️
  
---

## 🔥 Features  
📹 Real-time human detection via webcam.

🎥 Detect & count people in videos.

🖼️ Process static images for human detection.

🏆 Uses HOG + SVM, a powerful combination for human recognition.

📂 Saves processed videos/images with bounding boxes.

🖥️ Command-line interface for flexible input.

---

## 🛠️ Tech Stack  
- **Python** 🐍  
- **OpenCV** 🖼️  
- **NumPy** 🔢  
- **imutils** 🛠️  
- **argparse** 📜  

---

## 📥 Installation  

Clone the repository:  
```sh
git clone https://github.com/yourusername/Human-Detection-Counting.git
cd Human-Detection-Counting

```
Ensure you have Python installed. Then, install the required dependencies:
```
pip install opencv-python imutils numpy argparse
```


 ## Running the Detector

🔴 Detect from a Video File

```
python main.py -v "path_to_video.mp4"
```
🟢 Detect from an Image

```
python main.py -i "path_to_image.jpg"
```

🔵 Detect in Real-Time using Webcam

```
python main.py -c True
```

🟠 Save Output Video
```
python main.py -c True -o "output.avi"
```



## 🏆 Results

The system efficiently detects and counts humans in real-time and video/image inputs. It provides:

- Accurate bounding boxes around detected individuals.

- Efficient processing with optimized HOG + SVM.

- Real-time frame-by-frame visualization.

## 🛠️ To-Do List

- ✅ Improve detection accuracy using deep learning (YOLO or SSD).
- ✅ Add GUI-based interface for ease of use.
- ✅ Optimize performance for large-scale video processing.
