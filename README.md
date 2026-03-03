# 🎯 Smart Attendance System using Face Recognition

An AI-based Smart Attendance System that uses Face Recognition to automatically mark student attendance in an Excel sheet.

This project captures live images from a webcam, identifies the student using facial recognition, and records attendance with date and time.

---

## 📌 Problem Statement

Manual attendance systems are time-consuming and prone to errors.  
This system automates attendance marking using computer vision and face recognition.

---

## 🛠 Tech Stack

- Python
- OpenCV
- face_recognition
- Pandas
- NumPy
- Excel (for attendance storage)

---

## 🚀 Features

✅ Real-time webcam face capture  
✅ Face recognition using encodings  
✅ Automatic attendance marking  
✅ Stores Date & Time  
✅ Creates Excel file if not available  
✅ Simple and efficient implementation  

---

## 📂 Project Structure


📦 Smart-Attendance-System
┣ 📂 Known_Faces
┃ ┣ 📜 student1.jpg
┃ ┣ 📜 student2.jpg
┃ ┗ 📜 ...
┣ 📜 attendance.xlsx
┣ 📜 main.py
┗ 📜 README.md


---

## ⚙ How It Works

1️⃣ The system loads known face images from the directory.  
2️⃣ It generates face encodings for each student.  
3️⃣ The webcam captures a live image.  
4️⃣ The captured face encoding is compared with known encodings.  
5️⃣ If matched, attendance is recorded in `attendance.xlsx` with date and time.

---

## 🖥 Installation & Setup

### 1️⃣ Clone the Repository


git clone https://github.com/your-username/smart-attendance-system.git

cd smart-attendance-system


### 2️⃣ Create Virtual Environment (Optional but Recommended)


python -m venv venv
venv\Scripts\activate


### 3️⃣ Install Dependencies


pip install opencv-python
pip install face-recognition
pip install pandas
pip install openpyxl


### 4️⃣ Add Known Faces

Place student images (.jpg / .png) inside the `Known_Faces` folder.  
The image filename should be the student name.

Example:

Shreya.jpg
Rahul.png


### 5️⃣ Run the Program


python main.py


Press **Spacebar** to capture the image.

---

## 📊 Output

Attendance will be stored in:


attendance.xlsx


| Name    | Date       | Time     |
|---------|-----------|----------|
| Shreya  | 2026-03-03 | 10:45:22 |

---

## 🧠 Key Concepts Used

- Face Encoding
- Face Matching
- Real-time Image Capture
- Excel File Handling
- Computer Vision

---

## 🔮 Future Improvements

- Add GUI interface
- Prevent duplicate attendance
- Add database (MySQL)
- Add cloud storage
- Multi-face detection
- Add admin dashboard

---

## 🏆 Learning Outcomes

- Practical implementation of Face Recognition
- OpenCV integration with Python
- Real-world automation project
- File handling using Pandas
