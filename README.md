# Hand Gesture Controlled Virtual Mouse System

A real-time computer vision project that allows users to control the mouse cursor using hand gestures captured through a webcam. The system uses MediaPipe for hand tracking, OpenCV for video processing, and PyAutoGUI for mouse automation, enabling touchless human-computer interaction.

---

## 🚀 Features

* Real-time hand tracking using webcam
* Mouse cursor movement using index finger
* Left-click gesture
* Right-click gesture
* Double-click gesture
* Screenshot capture gesture
* Smooth and touchless computer control
* Single-hand gesture recognition

---

## 🛠️ Technologies Used

* Python
* OpenCV
* MediaPipe
* PyAutoGUI
* NumPy
* Pynput

---

## 📂 Project Structure

```text
Hand_Gesture_Control/
│
├── main.py              # Main application
├── util.py              # Utility functions for gesture calculations
├── requirements.txt     # Project dependencies
├── screenshots/         # Saved screenshots (generated)
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/hand-gesture-virtual-mouse.git
cd hand-gesture-virtual-mouse
```

### 2. Create Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate Virtual Environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/Mac**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 📦 Requirements

Create a `requirements.txt` file with:

```text
opencv-python
mediapipe
pyautogui
numpy
pynput
```

Install using:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

```bash
python main.py
```

Make sure your webcam is connected and accessible.

---

## 🎮 Gesture Controls

| Gesture                    | Action             |
| -------------------------- | ------------------ |
| Index Finger Up            | Move Cursor        |
| Index Finger Bent          | Left Click         |
| Middle Finger Bent         | Right Click        |
| Index + Middle Finger Bent | Double Click       |
| Screenshot Gesture         | Capture Screenshot |

---

## 📸 Screenshots

Add screenshots or GIFs of your project here.

```markdown
![Demo](images/demo.png)
```

---

## 🔍 How It Works

1. OpenCV captures real-time webcam video.
2. MediaPipe detects and tracks hand landmarks.
3. Finger positions and distances are calculated.
4. Gestures are recognized using predefined logic.
5. PyAutoGUI executes mouse actions based on detected gestures.

---

## 💡 Applications

* Touchless computer interaction
* Accessibility assistance
* Smart automation systems
* Gesture-based interfaces
* Human-computer interaction research

---

## 🔮 Future Enhancements

* Volume control using gestures
* Brightness control
* Multi-hand support
* Custom gesture mapping
* Drag and drop functionality
* AI-based gesture classification

---

## 👨‍💻 Author

**Vinay B K**

* GitHub: [https://github.com/bkvinay3115](https://github.com/bkvinay3115)
