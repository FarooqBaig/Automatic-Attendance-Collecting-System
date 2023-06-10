# Automatic Attendance Collecting System
The Automatic Attendance Collecting System is a Python-based project that automates the process of collecting attendance using ID card scanning and facial recognition. The system utilizes the following dependencies:

Python
OpenCV for face detection
Haarcascade frontal face detection
DeepFace for face recognition
Built-in Python packages for barcode scanning and data manipulation
Functionality
**ID Card Scanning:** The system prompts the user to provide their ID card. It scans the barcode on the ID card to extract the roll number.

**Roll Number Validation:** The system verifies the validity of the scanned roll number.

**Face Recognition:** The system uses OpenCV and Haarcascade to detect faces in real-time.

**Face Matching:** DeepFace is employed to compare the captured face with the stored face associated with the roll number.

**Attendance Recording:** If a match is found, the system records the attendance by saving the relevant information in an Excel file.

**Getting Started**
To use the Automatic Attendance Collecting System, follow these steps:

Clone this repository to your local machine.

Install the required dependencies by running the following command:

```
pip install opencv-python
pip install opencv-contrib-python
pip install deepface```

__Follow the instructions displayed by the system to scan the ID card and capture the face for attendance recording.__

The attendance data will be automatically saved in an Excel file.
