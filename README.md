# Gesture-Controlled-Virtual-Mouse

A computer vision–based virtual mouse system that enables users to control mouse operations using hand gestures captured through a webcam.

The project uses hand tracking and gesture recognition to perform real-time cursor movement and click operations without requiring a physical mouse.

---

## Features

- Real-time hand tracking using webcam
- Cursor movement using finger gestures
- Left click gesture recognition
- Smooth hand-based interaction
- Touchless human-computer interaction
- Real-time gesture processing

---

## Technologies Used

- Python
- OpenCV
- MediaPipe
- PyAutoGUI

---

## Project Structure

```bash
Gesture-Controlled-Virtual-Mouse/
│
├── src/
│   └── main project files
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/AaryanJain1507/Gesture-Controlled-Virtual-Mouse.git
```

Move into the project directory:

```bash
cd Gesture-Controlled-Virtual-Mouse
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run the Project

```bash
python src/main.py
```

---

## How It Works

1. The webcam captures live video frames.
2. MediaPipe detects and tracks hand landmarks in real time.
3. Finger positions are analyzed to recognize gestures.
4. Gestures are mapped to mouse actions such as:
   - Cursor movement
   - Left click operations
5. PyAutoGUI performs the corresponding mouse operations on the system.

---

## Future Improvements

- Right click gesture support
- Drag and drop functionality
- Scroll gesture support
- Gesture customization
- Multi-hand tracking
- Performance optimization

---

## Applications

- Touchless computer interaction
- Accessibility support
- Smart interaction systems
- AI-based human-computer interaction
- Gesture-controlled automation systems

---

## Author

Aaryan Jain

GitHub:  
[AaryanJain1507](https://github.com/AaryanJain1507)
