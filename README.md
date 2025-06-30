# Abnormal Activity Detection 🚨🎥

A real-time Abnormal Activity Detection system using Deep Learning and Computer Vision to enhance public safety through automatic recognition of dangerous or suspicious activities such as burglary, assault, drowsiness, and theft from video streams.

## 📌 Project Overview

This project leverages advanced deep learning architectures—CNNs for spatial feature extraction, RNNs (LSTM/GRU) for temporal pattern recognition, and Vision Transformers for high-level feature understanding—to detect abnormal human activities in real-time surveillance feeds.

The system integrates a **PyQt-based Desktop GUI** and a **Flask Web Interface**, allowing easy monitoring and rapid alerting.

---

## ⚙️ Features

✅ Real-time abnormal activity detection from video streams
✅ Supports activities like: `Burglary`, `Abuse`, `Arrest`, `Drowsiness`, `Theft`, and more
✅ Deep Learning-based detection using CNN + RNN + Vision Transformers
✅ PyQt5 GUI for Desktop Monitoring
✅ Flask Web Server for Remote Access
✅ Lightweight model optimizations for faster inference
✅ Supports live webcam feeds or pre-recorded videos

---

## 🏗️ Tech Stack

* **Python 3.x**
* **TensorFlow / Keras**
* **OpenCV**
* **PyQt5**
* **Flask**
* **Vision Transformers (ViT)**
* **LSTM / GRU for sequence modeling**
* **NumPy, Pandas, Matplotlib**

---

## 📁 Project Structure

```
abnormal-activity-detection/
├── Main Model Training           
├── CNN & RNN output                 
├── ResNET50 Model                 
├── VGG16 Model                
├── requirements.txt       # Python dependencies
├── README.md              # Project documentation
```

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/abnormal-activity-detection.git
cd abnormal-activity-detection
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Real-Time Detection (PyQt GUI)

```bash
python gui/main.py
```

### 4️⃣ Run Web Server (Flask)

```bash
python web/app.py
```

---

## 🧠 Model Architecture

The detection pipeline combines:

* **CNN Backbone:** Extracts spatial features from video frames
* **RNN Layer (LSTM/GRU):** Captures temporal relationships and movement patterns
* **Vision Transformer:** Enhances contextual understanding for complex scenarios
* **Softmax Classifier:** Outputs probability scores for normal/abnormal activities

---

## 📹 Supported Activities

The current system is trained to detect:

✅ Burglary
✅ Assault / Abuse
✅ Theft
✅ Arrest situations
✅ Drowsiness or Inactivity

You can extend the model by adding new activity classes and retraining.

---

## 🛠️ Training the Model

Prepare the dataset in the following structure:

```
dataset/
├── normal/
│   ├── video1.mp4
│   └── video2.mp4
├── burglary/
├── abuse/
├── theft/
...
```

Then run:

```bash
python train.py
```

Training hyperparameters can be configured inside `train.py`.

---

## 📊 Performance

* Achieved high accuracy on benchmark datasets for abnormal activity recognition
* Real-time inference optimized for standard webcams
* Modular design for easy deployment across different platforms

---

## ⚡ Future Improvements

* Integrate alert notifications (SMS/Email)
* Deploy as an edge device solution (Jetson Nano/Raspberry Pi)
* Expand dataset diversity
* Improve lightweight model variants for faster response

---

## 🤝 Contributing

Pull requests are welcome! Please open an issue first to discuss improvements or bug fixes.

---

## 📄 License

[MIT License](LICENSE)

---

## 📬 Contact

For queries or collaborations:
**Arjun Goyal — [arjungoyal66796@gmail.com](mailto:arjungoyal66796@gmail.com)

---

**Real-Time Safety Powered by AI.** 🌐🛡️
