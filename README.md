# Gesture-Controlled-Virtual-Mouse
Gesture-Controlled-Virtual-Mouse

A computer vision–based virtual mouse system that enables users to control mouse operations using hand gestures captured through a webcam.

The project uses hand tracking and gesture recognition to perform real-time cursor movement and click operations without requiring a physical mouse. It is built using Python, OpenCV, MediaPipe, and PyAutoGUI.

Features
Real-time hand tracking using webcam
Cursor movement using finger gestures
Left click gesture recognition
Smooth hand-based interaction
Touchless human-computer interaction
Real-time gesture processing
Technologies Used
Python
OpenCV
MediaPipe
PyAutoGUI
Project Structure
Gesture-Controlled-Virtual-Mouse/
│
├── src/
│   └── main project files
│
├── README.md
├── requirements.txt
└── .gitignore
Installation

Clone the repository:

git clone https://github.com/AaryanJain1507/Gesture-Controlled-Virtual-Mouse.git

Move into the project directory:

cd Gesture-Controlled-Virtual-Mouse

Install dependencies:

pip install -r requirements.txt
Run the Project
python src/main.py
How It Works
The webcam captures live video frames.
MediaPipe detects and tracks hand landmarks in real time.
Finger positions are analyzed to recognize gestures.
Gestures are mapped to mouse actions such as:
Cursor movement
Left click operations
PyAutoGUI performs the corresponding mouse operations on the system.

Gesture-based virtual mouse systems commonly use MediaPipe hand landmark detection together with OpenCV-based frame processing for real-time interaction.

Future Improvements
Right click gesture support
Drag and drop functionality
Scroll gesture support
Gesture customization
Multi-hand tracking
Performance optimization
Applications
Touchless computer interaction
Accessibility support
Smart interaction systems
AI-based human-computer interaction
Gesture-controlled automation systems

Gesture-controlled interfaces are widely explored in computer vision and HCI systems for touchless interaction and accessibility use cases.

Author

Aaryan Jain

GitHub:
AaryanJain1507
