## 🎓 Attendance System with Face Recognition
## https://rohit-joshi-01.github.io/Attendance-System-with-Face-Recognition/

A browser-based smart attendance system that uses facial recognition to automatically detect and mark student attendance in real-time.

This project integrates computer vision, AI-based face matching, and a modern UI dashboard to replace traditional manual attendance systems.

## 🚀 Features
## 🎥 Face Recognition System
- Real-time face detection using webcam
- Facial landmark mapping & descriptor matching
- Accurate identity recognition using stored face data
  
## 🧾 Attendance Management
- Automatically marks attendance per lecture/session
- Stores attendance records with date and time
- Prevents duplicate marking

## 👨‍🎓 Student Management
- Add students (Name + Roll Number)
- Maintain student database
- Link biometric data with identities

## 🧠 AI-Powered Insights (if included)
- Analyze attendance trends
- Detect irregular attendance patterns
- Generate smart summaries
  
## 💬 Interactive UI
- Futuristic dashboard interface
- Real-time status indicators
- Toast notifications and activity logs
  
## 📊 Export Data
Export attendance records in Excel (.xlsx) format

## 🏗️ Tech Stack
- Frontend: HTML, CSS, Tailwind CSS
- JavaScript: Vanilla JS
- Face Recognition: face-api.js
- Data Storage: Browser LocalStorage
- Excel Export: SheetJS
  
## 📂 Project Structure
Attendance-System-with-Face-Recognition/
- <b>│── index.html   </b>              # Main application UI
- <b>│── /models  </b>                  # Face-api models (if included/downloaded)
- <b>│── /assets  </b>                  # UI assets (icons/images if present)
- <b>│── /scripts or inline JS  </b>    # Core logic (face recognition + attendance)
- <b>│── README.md   </b>               # Documentation

## ⚙️ Setup & Installation
- Clone the repository:
- git clone https://github.com/rohit-joshi-01/Attendance-System-with-Face-Recognition.git
- cd Attendance-System-with-Face-Recognition
  
Open the project:
- Simply open index.html in your browser
- Allow permissions:
- Enable camera access when prompted
  
## ▶️ How to Use
1. Start Camera
Click Initialize / Start Camera
Webcam feed will begin
2. Enroll Students
Enter student name & roll number
Capture face data
3. Run Recognition
System detects faces automatically
Matches with stored biometric data
4. Attendance Marking
Marks student as Present
Updates attendance dashboard in real-time
5. Export Data
Download attendance as Excel file

## 📊 Attendance Format
{
  "roll": 240070800037,
  "name": "Student Name",
  "date": "DD/MM/YYYY",
  "L1": "P",
  "L2": "A",
  "L3": "P"
}
## ⚠️ Requirements
- Modern browser (Chrome recommended)
- Webcam access
- Internet connection (for CDN libraries)
  
## ⚠️ Limitations
- Performance depends on lighting conditions
- Face recognition accuracy may drop with:
- Masks
- Extreme angles
- Poor camera quality
- Data stored locally (no cloud sync)
  
## 🔮 Future Enhancements
- Backend integration (MongoDB / Firebase)
- Multi-user authentication (Admin/Teacher)
- Mobile responsiveness
- Liveness detection (anti-spoofing)
- Cloud-based face storage
  
## 🤝 Contributing

Contributions are welcome!

Fork the repo
Create a feature branch
Submit a pull request
📄 License

This project is open-source and available under the MIT License.

## 👨‍💻 Author

<h4 align = "center"> Rohit Joshi </h4>
<h6 align = "center"> GitHub: https://github.com/rohit-joshi-01 </h6>
