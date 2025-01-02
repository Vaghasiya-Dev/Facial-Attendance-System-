# 📸 Attendance Management System with Face Recognition  

---

## 🗂️ Table of Contents  
1. [Overview](#overview)  
2. [Features](#features)  
   - [User Management](#user-management)  
   - [Attendance Management](#attendance-management)  
3. [Technologies Used](#technologies-used)  
4. [How It Works](#how-it-works)   
5. [Installation and Setup](#installation-and-setup)  
6. [Future Enhancements](#future-enhancements)  
7. [Developer Info](#developer-info)  
8. [License](#license)  

---

## 📖 Overview  
This is a web-based **Attendance Management System** that leverages **Face Recognition** to streamline attendance tracking. The system uses **machine learning**, CSV data storage, and **OpenCV** to provide an intuitive, efficient, and secure solution for managing attendance records.  


## ✨ Features  

### 👤 User Management  
- **Add User**:  
  - Add users with their name and ID.  
  - The system captures **10 pictures** for facial recognition.  
  - Newly added users are unregistered by default.  

- **Register User**:  
  - Admin assigns a section to users for registration.  

- **Unregister/Remove User**:  
  - Admin can unregister or delete users from the system.  

---

### ✅ Attendance Management  
- **Mark Attendance**:  
  - Uses face recognition to mark attendance securely.  

- **View Attendance**:  
  - Admin can filter attendance by **date** or **user ID**.  

---

## 🛠️ Technologies Used  

### Programming Languages and Libraries  
- **Python**  
  - `Flask` - Backend web framework.  
  - `OpenCV` (`cv2`) - For image processing and face recognition.  
  - `numpy` - Numerical computations.  
  - `pandas` - Data manipulation.  
  - `joblib` - For model serialization.  
  - `csv` - CSV data handling.  

### Machine Learning  
- **scikit-learn**:  
  - **K-Nearest Neighbors (KNN)** algorithm for face recognition.  

---

## ⚙️ How It Works  

1. **Add User**:  
   - Enter the user's name and ID.  
   - The system captures 10 images and stores them for training.  

2. **Register User**:  
   - Admin assigns the user to a section.  

3. **Mark Attendance**:  
   - The user stands in front of the webcam.  
   - Face recognition is performed, and attendance is logged (only once an hour).  

4. **View Attendance**:  
   - Admin can filter attendance records by date or user ID.  


---

## 📜 License  

This project is licensed under the **MIT License**.  

---

## 🛡️ Acknowledgments  

This project was created during the **TechSaksham AI Internship Program**, a collaborative effort by **Microsoft**, **SAP**, and **AICTE**. Special thanks to the mentors for their guidance and support.  


