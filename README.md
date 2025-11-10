# Driver Drowsiness Detection System 👁️😴  
*A Machine Learning & Computer Vision-Based Safety System*

The **Driver Drowsiness Detection System** helps prevent accidents by continuously tracking the driver’s eye activity using **Python**, **OpenCV**, and **Machine Learning** techniques. When the system detects that the driver appears sleepy, it triggers an audio alert to ensure safety.

---

## 🚗 Why This Project?

Drowsy driving causes thousands of accidents every year. This system provides a **real-time alert** when the driver’s eyes remain closed beyond a safe duration — reducing risk on the road.

---

## 🧠 Technologies Used

| Category | Tools |
|---------|-------|
| Programming | Python |
| Computer Vision | OpenCV, Dlib |
| ML Technique | Eye Aspect Ratio (EAR) |
| Audio Alert | playsound / winsound |
| Hardware | Webcam / Laptop Camera |

---

## ✨ Key Features

✔ Real-time eye detection  
✔ EAR-based fatigue classification  
✔ Alarm alert for drowsiness  
✔ Simple & lightweight system  
✔ Works on any standard webcam  

---

## 🔧 How It Works

1️⃣ Webcam captures live feed  
2️⃣ Detect facial landmarks using Dlib  
3️⃣ Calculate Eye Aspect Ratio (EAR)  
4️⃣ If EAR < threshold for multiple frames → Driver is sleepy  
5️⃣ Alarm is activated 🚨  

---

## 📦 Installation & Setup

🔹 Prerequisite: Python 3.7+ installed on your system

```bash
# Clone the repository
git clone https://github.com/<your-username>/Driver-Drowsiness-Detection.git
cd Driver-Drowsiness-Detection

# Install required packages
pip install -r requirements.txt

