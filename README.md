#### This Readme file is AI generated based on the project Description ####


# 🤟 AI Sign Language Translator 🤖🧠

Welcome to the AI Sign Language Translator project! This research-based project focuses on building a real-time gesture recognition system to help bridge the communication gap for hearing-impaired individuals. 🌍✨

---

## 📜 Project Overview
This project captures sign language gestures via a webcam, extracts keypoints using Mediapipe, and uses an LSTM model to predict and translate the gestures into text in real time. The focus is on **experimental model training**, **performance evaluation**, and **accessibility research**.

---

## 🎯 Goals
- Recognize sign language gestures in real-time 🎥
- Translate recognized gestures into readable text ✍️
- Assist hearing-impaired individuals in communicating effectively with others 🤝

---

## 🛠️ Technologies Used
- **Python** 🐍
- **TensorFlow / Keras** 🔥
- **Mediapipe** 📷
- **OpenCV** 🖼️
- **Matplotlib** 📊
- **NumPy** 📚

---

## 📦 Project Structure
```
├── MP_Data/                  # Stored Keypoints Data
├── Model/                    # Trained LSTM Model (.h5)
├── RealTimeTest/             # Real-time Prediction Scripts
├── Logs/                     # TensorBoard Training Logs
├── utils/                    # Helper Functions (Landmarks, Drawing)
├── main.py                   # Data Collection Script
├── train.py                  # Model Training Script
├── README.md                 # Project Documentation
```

---

## 🚀 How to Run the Project

1. **Clone this Repository** 📂
```bash
git clone https://github.com/APRO-75/sign-language-translator-ai.git
cd sign-language-translator-ai
```

2. **Install Required Libraries** 🛠️
```bash
pip install -r requirements.txt
```

3. **Collect Gesture Data** ✋
```bash
python main.py
```

4. **Train the Model** 🧠
```bash
python train.py
```

5. **Run Real-Time Prediction** 🎥
```bash
python realtime_test.py
```

---

## 📈 Results
- Final Model Accuracy: **~88%**
- Real-time prediction latency: **~0.2 seconds**
- 6 Gestures Recognized: `Hello`, `Thanks`, `I Love You`, `How Are You`, `So-so`, `Good`

---

## 🧠 Future Work
- Improve model generalization with more data 📈
- Deploy model on mobile or browser 📱
- Integrate Text-to-Speech for complete communication 🔊

---

## ✨ Acknowledgements
- Inspired by open-source learning materials and tutorials on YouTube and GitHub.
- Sign Language Dataset was self-generated using Mediapipe.

---

## 📜 License
This project is licensed for **educational and research purposes** only.

