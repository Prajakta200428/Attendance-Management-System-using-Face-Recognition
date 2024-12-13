# Attendance-Management-System-using-face-recognition
# Attendance Management System

This project is a **Face Recognition-based Attendance Management System**. It allows users to register students, capture their images, and store their details for attendance tracking. The system also provides a graphical user interface (GUI) for ease of use.

## Features
- **Face Registration**: Capture and save images of students with unique IDs and names.
- **Face Training**: Train a facial recognition model to identify registered faces.
- **Attendance Tracking**: Mark attendance in real-time using facial recognition.
- **Password Protection**: Secure access to sensitive functionalities like training and attendance recording.
- **CSV Reports**: Save attendance records as CSV files for easy management.
- **GUI Interface**: User-friendly interface built using `tkinter`.

---


## Libraries Used
The following Python libraries are required for this project:
- `tkinter`: GUI creation
- `cv2` (OpenCV): Image processing and facial recognition
- `os`: File and directory handling
- `csv`: Handling CSV files
- `numpy`: Numerical operations
- `Pillow`: Image processing
- `pandas`: Data manipulation and analysis
- `datetime`: Handling date and time
- `time`: Time-related functions


#File Structure
Attendance-Management-System/
│
├── Attendance/               # Directory to store attendance CSVs
├── StudentDetails/           # Directory to store student details CSV
├── TrainingImage/            # Directory to save captured training images
├── TrainingImageLabel/       # Directory to save trained model and password file
├── haarcascade_frontalface_default.xml  # Haarcascade file for face detection
└── main.py                   # Main script file


#Usage Instructions
1. Prerequisites
Ensure Python 3.x is installed on your system.
Install the required libraries mentioned above.

2. Password Management
The system prompts for a password when accessing sensitive functionalities.
The password can be changed via the "Change Password" menu option.

3. Attendance Reports
Attendance records are saved as CSV files in the Attendance/ directory.
Each record includes the student ID, name, date, time, and subject.

#Dependencies
Ensure the following dependencies are installed:
Python 3.x
OpenCV
PIL (Pillow)
Pandas

#Acknowledgments
The facial recognition functionality is powered by OpenCV.
Haarcascade classifiers for face detection.

#Future Improvements
Enhance the UI for better user experience.
Add support for multiple camera inputs.
Implement notifications or reminders for attendance.
Integrate with databases for better scalability.
vbnet
Copy code
