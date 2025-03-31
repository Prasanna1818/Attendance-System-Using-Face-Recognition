

## 🏆 Attendance System Using Face Recognition

### 📖 Introduction
Attendance Management keeps track of **employees' or students'** presence/absence details. It documents their **working hours and leaves**.

In this digital era, **face recognition** plays a crucial role in various sectors. It is a widely used **biometric technology** for **security, authentication, and identification**.

This AI-based **Attendance Management System** leverages **face recognition technology** to **automate attendance tracking using computer vision**.

---

## ✨ Features
✅ **Automated attendance marking** with timestamps (Entry & Exit).  
✅ **Touchless system** using face recognition.  
✅ **One-click AI model training** for facial recognition.  
✅ **Dataset creation module** for capturing new employee images.  
✅ **User-friendly** management panel for administration.  
✅ **Unauthorized access detection & prevention**.  
✅ **Voice output for status confirmation**.  
✅ **Blink detection** to prevent fake digital image attacks.  

---

## 🛠️ Setup Management Panel (C#)

### 📌 Step 1: Create a MySQL Database
- Create an **empty database** in MySQL with the name **"management_auto_attendance_system"**.

### 📌 Step 2: Import the SQL Database
- Import the SQL database found in the following repository folder:  
  📂 `attendance-system-with-face-recognition/1-database`

---

## 🖥️ Setup Attendance Receiver - Face Scanner (Python)
To connect the **management panel (C#)** and **attendance receiver (Python)** correctly, install all dependencies in a **Python virtual environment**.  

The **virtual environment name must be** `ai_attendance_system_env`.

---

## 🏗️ Create a Python Virtual Environment

### 🛠️ Step 1: Install Anaconda  
🔗 Download and install **[Anaconda](https://www.anaconda.com/products/individual)**.  
📺 Watch the **[installation guide](https://www.youtube.com/watch?v=RYSNnp5V7ps&t)**.  

### ⚙️ Step 2: Create the Virtual Environment  
Run the following command in **Terminal/CMD**:  
```cmd
conda create -n ai_attendance_system_env python=3.6
```

### 🚀 Step 3: Activate the Environment  
Run the following command:  
```cmd
conda activate ai_attendance_system_env
```

### 📦 Step 4: Install Required Dependencies  
Run the following commands to install all required packages:  
```cmd
pip install opencv-python pyttsx3 cmake face_recognition imutils playsound==1.2.2 mysql-connector-python qrcode
```

---

## 📸 Screenshots

### 🏁 Splash Screen  
![Splash Screen](https://github.com/user-attachments/assets/5caebaca-11e4-4b35-aea1-e2ea960e9e0b)  

### 🔑 Login Screen  
![Login Screen](https://github.com/user-attachments/assets/c4170c8c-cb4f-4e39-acd9-6fe2e3c9fcf8)  

### 📊 Dashboard  
![Dashboard](https://github.com/user-attachments/assets/6c8fc6fe-84df-4acf-ae8d-3050c0d03937)  

### 👨‍💼 Manage Employees (Insert Employees Module)  
![Manage Employees](https://github.com/user-attachments/assets/26c38530-2a68-43d4-a94c-addc246dffcd)  

### 📷 Create Dataset  
![Create Dataset](https://github.com/user-attachments/assets/1565e1ad-3b22-4a6e-b643-143c20f6186c)  

### 🏋️ Training  
![Training](https://github.com/user-attachments/assets/dd82a1c6-5c04-4dce-9a40-b99a0c6f84a0)  

### 🔲 Generate QR Code  
![QR Code](https://github.com/user-attachments/assets/6ae34a66-1986-4c74-a1ba-bb5775f4ac53)  

### 📜 Attendance Report  
![Attendance Report](https://github.com/user-attachments/assets/9a6368a8-f71d-4150-94bd-f2228e07f869)  

### 🆔 Face Verification  
![Face Verification](https://github.com/user-attachments/assets/bb7c564f-8848-4130-b73b-38854ac87116)  

---

## 🤖 Training Algorithm
We use **128D FaceNet embeddings** for model training. During training, it collects and organizes **128D face embeddings** into a vector, which is stored in **pickle format**. This trained model is used later in the **attendance receiver module** for face verification.

---

## 📢 Note
💡 If setting up this project in a **virtual environment**, install all dependencies using the `environment.yml` file:  
```cmd
conda env create -f environment.yml
```

---

## 🎯 Conclusion
This AI-based **Face Recognition Attendance System** is a smart, contactless, and efficient solution for attendance management across industries. 🚀

