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
###2. Install dependencies
pip install -r requirements.txt
or manually install: pip install opencv-python numpy onnxruntime
###3. Download Model

Download the pre-trained model from:
🔗 ResNet-34 Kinetics ONNX Model

Place it inside the model/ directory like this:
Bash 
model/resnet-34_kinetics.onnx
model/action_recognition_kinetics.txt

###4. Run recognise_human_activity.py
  If want to use webcam then :
    In recognise_human_activity.py select self.VIDEO_PATH = None
    
  If want to use vedio then:
    Insert vedio in test folder then 
      In recognise_human_activity.py select self.VIDEO_PATH = "test/example1.mp4"
      
📂 Project Structure
├── model/
│   ├── resnet-34_kinetics.onnx
│   ├── action_recognition_kinetics.txt
├── test/
│   ├── example1.mp4
├── recognise_human_activity.py
└── README.md
📌 Use Cases

🎯 Smart surveillance
🖐️ Gesture & human-computer interaction
🏃 Sports performance analysis
🧑‍🤝‍🧑 Crowd behavior monitoring

🔮 Future Improvements
Add support for multiple persons in a frame
Improve FPS performance with GPU acceleration
Integrate with Flask/Streamlit for web dashboard

⚡ Author

Project implemented and customized by Ansh kumar ✨
git clone https://github.com/<your-username>/human-action-recognition.git
cd human-action-recognition
