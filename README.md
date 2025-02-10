# 🌟 Smart Office Light Control 🚪💡  
🔥 Smart Lighting System using IoT & Face Detection  

## 📌 Project Overview  
This project implements an **automatic office lighting system** using **IoT, PIR sensors, and face detection**.  
The system turns lights **ON/OFF** based on people entering or leaving a room, improving **energy efficiency** ⚡ and reducing power waste.  

## 🏗️ Features  
✅ **Motion Detection** using PIR Sensors 🎯  
✅ **Real-time Face Recognition** with OpenCV 🤖  
✅ **IoT Integration** for Smart Light Control 🌐  
✅ **Automatic Light Switching** based on occupancy 🏢  
✅ **Power Efficiency Optimization** ⚡  

## 🛠️ Tech Stack  
🔹 **Raspberry Pi** 🍓  
🔹 **Python** 🐍  
🔹 **OpenCV** 👀  
🔹 **IoT & Smart Bulbs** 💡  
🔹 **Machine Learning** (MTCNN, SVM, HMM, AdaBoost) 🤖  

## 📂 Project Structure  

```plaintext

📁 OfficeLightControl/
│-- 📂 src/                 # Source code for face detection & light control  
│-- 📂 models/              # Trained ML models  
│-- 📂 docs/                # Research & documentation  
│-- 📂 assets/              # Images & diagrams  
│-- README.md               # Project README (this file)

🚀 Installation & Setup

1️⃣ Clone the Repository

bash
Copy
Edit
git clone https://github.com/your-username/OfficeLightControl.git
cd OfficeLightControl

2️⃣ Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt

3️⃣ Run Face Detection & Light Control

bash
Copy
Edit
python main.py

🎯 How It Works

Person Enters 🚶‍♂️ → PIR Sensor detects motion → Face Recognition activates
Face is Verified ✅ → Light turns ON 💡
Person Leaves 🏃‍♂️ → System checks if the room is empty
If Empty for 5 mins ⏳ → Light turns OFF 🔴

📊 Power Efficiency Results

Year	Normal Lights (GWh)	Smart Lights (GWh)	Energy Saved ⚡
2017	149,320	110,229	✅ Yes
2018	148,700	120,035	✅ Yes
2019	162,343	125,563	✅ Yes
