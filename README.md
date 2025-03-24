# Face_Recognition_Attendance_System
This Face Recognition Attendance System uses Python, OpenCV, Tkinter, and a KNN classifier for real-time attendance tracking. It features data collection, CSV-based logging, email automation, voice alerts, and a user-friendly GUI. Ideal for institutions and workplaces, it ensures efficient, automated attendance with minimal manual intervention.
Here is a complete README for your Face Recognition Attendance System project, licensed under the MIT License:

```markdown
# Face Recognition Attendance System

This project is a Face Recognition Attendance System built using Python and machine learning. It leverages OpenCV for real-time face detection, Tkinter for the graphical user interface (GUI), and a K-Nearest Neighbors (KNN) classifier for face recognition. The system collects user data, stores it securely, and marks attendance by recognizing faces in real-time.

## Features

- Data Collection: Captures and processes face images to build a dataset for recognition.
- Attendance Marking: Recognizes faces, logs attendance with timestamps, and stores data in CSV format.
- Email Integration: Automatically emails the attendance file to a predefined address daily.
- GUI Interface: A user-friendly graphical interface for managing operations.
- Voice Alerts: Provides real-time voice feedback for recognized and unknown faces.
- Automated Scheduling: Uses the `schedule` library to automate email sending.

## Installation

To install and run the Face Recognition Attendance System, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/face-recognition-attendance.git
   cd face-recognition-attendance
   ```

2. Install dependencies:
   You can use `pip` to install the required libraries. Make sure you have Python 3.x installed on your system.
   ```bash
   pip install -r requirements.txt
   ```

3. Run the system:
   To start the system, execute:
   ```bash
   python app.py
   ```

## Usage

1. Capture Faces: The system will prompt you to capture face images of users to build a dataset for recognition.
2. Attendance Logging: When the system detects a face, it logs the attendance with the timestamp.
3. Email Reports: The system will email the attendance records daily to the predefined address.
4. GUI Operations: Use the graphical interface to manage users, view attendance, and configure settings.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- OpenCV: For face detection and recognition.
- Tkinter: For the graphical user interface.
- K-Nearest Neighbors (KNN): For face recognition.
- schedule: For automating email scheduling.

## Contact

For any inquiries, please feel free to reach out to krishnavenin8192@gmail.com.
