# 🕹️ Pose-Controlled Gesture Detection using MediaPipe

A Python-based computer vision system that uses **MediaPipe Pose** to recognize body gestures like **jumping**, **crouching**, **hand-joining**, and **horizontal movement** to control games like **Subway Surfers** or **Temple Run** without touching a keyboard!

---

## 🎮 Use Case: Play Games with Your Body!

This project is designed to be extended to play endless runner games using your body:

| Game             | Gesture           | Action Triggered         |
|------------------|-------------------|---------------------------|
| Subway Surfers   | Jump               | Character jumps          |
|                  | Crouch             | Character rolls          |
|                  | Move Left/Right    | Character dodges         |
| Temple Run       | Hands Joined       | Start or pause the game  |

> 💡 With some automation via `pyautogui`, gestures can be mapped to keystrokes (e.g., jump = up arrow, crouch = down arrow).


---


## 📦 Features

- ✅ Real-time pose tracking using **MediaPipe**
- 👐 Hand gesture detection (joined / not joined)
- ↔️ Horizontal movement detection (left / center / right)
- 🦵 Posture classification (jump / stand / crouch)
- 📸 Webcam-based gesture recognition
- 🧠 Easy integration with automation tools


---

## 🧰 Tech Stack

- Python 🐍
- OpenCV 🎥
- MediaPipe 📐
- Matplotlib 📊
- PyAutoGUI (optional for automation) ⌨️


---

## 🔧 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/pose-gesture-detection.git
   cd pose-gesture-detection
   ```
2. **Install required packages:**
   ```bash
     pip install opencv-python mediapipe matplotlib pyautogui
     ```
3. **Run the Program**
   ```bash
     python main.py
     ```
   This will:

   - Open your webcam

   - Detect pose and classify gestures

   - Optionally simulate key presses using gestures


---

## 📁 Project Structure

```bash
.
├── subwaySurfers.py       # Main script to run the real-time system
├── README.md              # Project documentation
```

---

## 📸 Screenshots
[Insert demo video or GIF link here once available]

---

## 🙌 Credits
Built using:

- MediaPipe Pose

- OpenCV

- PyAutoGUI
