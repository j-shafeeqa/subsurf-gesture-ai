# 🕹️ Hand Gesture Controlled Subway Surfers

Control Subway Surfers using just your hand gestures via webcam!  
This real-time AI-powered system lets you play the game touch-free using computer vision and Python automation.

## 🎯 Project Goal
Replace traditional keyboard controls with hand gestures so players can jump, roll, or move in the game using simple finger movements — no mouse, no keyboard, just your hand.

## 👋 How It Works
1. **Webcam** captures live video.
2. **MediaPipe** detects your hand and fingers.
3. **Custom gesture logic** recognizes finger patterns.
4. **PyAutoGUI** presses the appropriate keyboard key based on the gesture.

## ✨ Example Gestures

| Gesture Name | Fingers Raised          | Action Triggered |
|--------------|--------------------------|------------------|
| Jump         | Only index finger        | `Up` key         |
| Roll         | Thumb + Index            | `Down` key       |
| Move Left    | Only thumb               | `Left` key       |
| Move Right   | Index + Middle fingers   | `Right` key      |
| Hoverboard   | All fingers up           | `Space` key      |

## 🧠 Tech Stack
- **Python** – Main programming language
- **OpenCV** – Webcam access & image processing
- **MediaPipe** – Real-time hand landmark detection
- **PyAutoGUI** – Simulate key presses to control the game

## 🚀 Features
- Real-time AI hand tracking
- No external hardware – just a webcam!
- Touch-free game control
- Great for accessibility & fun demos
- Easily extendable to other games and gestures

