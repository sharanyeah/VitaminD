Project Documentation: Vitamin Deficiency Detection System

  1. Introduction
This project is an AI-powered non-invasive vitamin deficiency detection system using a hybrid approach:
- **Image-based detection using CNN**
- **Symptom-based detection using MLP**

It identifies deficiencies by analyzing visible indicators on lips, eyes, tongue, and nails, and textual symptoms provided by users.

---

 2. Objectives
- Detect vitamin deficiencies using image analysis  
- Predict deficiencies using text/symptom-based classification  
- Provide precautions and recommendations  
- Ensure non-invasive, cost-effective screening  
- Develop a user-friendly web-based application  

---

 3. System Architecture

 Components:
- Frontend (HTML, CSS, JavaScript, Bootstrap)  
- Backend (Flask + Python)  
- ML Models (CNN + MLP)  
- Database (MySQL)  

 Workflow:
1. User uploads image or enters symptoms  
2. Backend preprocesses input  
3. CNN model → image prediction  
4. MLP model → symptom prediction  
5. Result stored in MySQL  
6. Display final deficiency + recommendations  

---

 4. Modules Implemented

Image-Based Module
- Input image collection  
- Preprocessing using OpenCV  
- CNN model training  
- Vitamin deficiency prediction  

Symptom-Based Module
- Dataset creation  
- Tokenization & preprocessing  
- MLP model training  
- Deficiency prediction  

Web Application Module
- Frontend UI  
- Backend API endpoints  
- Result rendering  
- Database integration  

---

5. Technologies Used

Programming Languages:
- Python  
- HTML, CSS, JavaScript  

Frameworks & Libraries:
- Flask  
- TensorFlow, Keras  
- OpenCV  
- Pandas, NumPy  

Database:
- MySQL  
- phpMyAdmin  

---

6. Results
(Add screenshots of your model accuracy graph, loss graph, and classification report here)

---

7. Conclusion
The system provides an effective, scalable method for detecting vitamin deficiencies using AI.  
It reduces dependency on invasive procedures and improves accessibility of early diagnosis.

---

8. Future Enhancements
- Add a mobile app version  
- Add voice-based symptom entry  
- Deploy on cloud (AWS / GCP)  
- Expand dataset for higher accuracy  

