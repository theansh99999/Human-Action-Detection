# Human Action Recognition 🎥🧠

This project demonstrates **real-time human action recognition** using a pre-trained deep learning model (**ResNet-34 trained on Kinetics-400**) with **OpenCV**.  
It can process input from a **live webcam** (or video file) and predict the **human activity** being performed, such as walking, running, clapping, etc.

---

## ✨ Features
- 🎥 Real-time detection using **webcam feed** or pre-recorded video  
- 🧠 Powered by **ResNet-34 ONNX model** trained on **Kinetics-400 dataset**  
- ⚡ Fast & lightweight implementation with **Python + OpenCV + NumPy**  
- ⌨️ Simple controls → Press **`q`** to exit 

---


## 🛠️ Tech Stack
- **Python 3.6+**  
- **OpenCV (cv2)**  
- **NumPy**  
- **ONNX Runtime**  

---


## 🚀 How to Run

### 1. Clone the repository
bash
bash
git clone https://github.com/<your-username>/human-action-recognition.git <br>
cd human-action-recognition <br>
### 2. Install dependencies
pip install -r requirements.txt <br>
or manually install: pip install opencv-python numpy onnxruntime <br>
### 3. Download Model

Download the pre-trained model from: <br>
🔗 ResNet-34 Kinetics ONNX Model <br>

Place it inside the model/ directory like this: <br>
Bash <br>
model/resnet-34_kinetics.onnx <br>
model/action_recognition_kinetics.txt <br>

###4. Run recognise_human_activity.py
  ####If want to use webcam then :
    In recognise_human_activity.py select self.VIDEO_PATH = None
    
  #### If want to use vedio then:
    Insert vedio in test folder then 
      In recognise_human_activity.py select self.VIDEO_PATH = "test/example1.mp4"
      
### 📂 Project Structure
├── model/ <br>
│   ├── resnet-34_kinetics.onnx <br>
│   ├── action_recognition_kinetics.txt <br>
├── test/ <br>
│   ├── example1.mp4 <br>
├── recognise_human_activity.py <br>
└── README.md <br>
## 📌 Use Cases

🎯 Smart surveillance <br>
🖐️ Gesture & human-computer interaction <br>
🏃 Sports performance analysis <br>
🧑‍🤝‍🧑 Crowd behavior monitoring <br>

## 🔮 Future Improvements
### Add support for multiple persons in a frame <br>
### Improve FPS performance with GPU acceleration <br>
### Integrate with Flask/Streamlit for web dashboard <br>

## ⚡ Author

Project implemented and customized by Ansh kumar ✨<br>
git clone https://github.com/theansh99999/human-action-recognition.git <br>
cd human-action-recognition <br>
