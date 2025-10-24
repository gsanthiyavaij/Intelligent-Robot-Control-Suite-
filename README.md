🤖 Intelligent Robot Control Suite (Case Study)

🔍 Overview


This project presents a **multifunctional AI software suite** designed to control and enhance an educational service robot.  
Developed in **Python**, it integrates **voice, vision, and natural language capabilities** to enable intelligent and interactive behavior in real-world environments.

> ⚠️ **Note:** This is a case-study repository. The core source code and assets are confidential and cannot be shared publicly.  
> All screenshots and architecture diagrams are sanitized versions meant for demonstration only.

---

  Key Features

| Feature | Description |
|----------|-------------|
| 💬 **Chatbot Integration** | Uses **OpenRouter APIs** (ChatGPT, Gemini) for natural dialogue and context-based responses. |
| 📸 **Gesture-Based Photobooth** | Captures images when specific hand gestures are detected using **OpenCV** and **MediaPipe**. |
| 🌐 **Real-Time Translation** | Multi-language speech and text translation using **Google Translator APIs**. |
| 🎥 **Video Playback Module** | Displays promotional or informational videos through the GUI for event/advertisement purposes. |
| 🔊 **Text-to-Speech Welcome** | Converts text to speech (TTS) to greet and interact with guests dynamically. |
| 🧍‍♀️ **Face Recognition Attendance** | Detects and identifies students/employees, automatically marking attendance. |
| 😊 **Emotion Recognition** | Analyzes facial expressions in real time to gauge emotion and engagement level. |
| 📱 **Mobile Control via QR + Flask** | Integrated **Flask server** enables mobile connectivity — scanning a QR code from the robot’s GUI opens a control panel on mobile to operate robot functions remotely. |

---

⚙️ Tech Stack

- **Language:** Python  
- **Libraries/Frameworks:** OpenCV, customtkinter, pyttsx3, SpeechRecognition, DeepFace, Flask, MediaPipe  
- **AI Models:** YOLO, FaceNet/DeepFace, Emotion Detection CNN  
- **APIs:** OpenRouter (ChatGPT, Gemini), Google Translator  
- **Architecture:** Multi-threaded event-driven design with GUI + Flask backend integration  

---
```text
+-----------------------------+
|         Robot Camera        |
+--------------+--------------+
               |
               v
+--------------+--------------+
|     AI Vision Modules       |  ← Face Detection, Emotion Recognition, Gesture Detection
+--------------+--------------+
               |
               v
+--------------+--------------+
|     Main GUI (customtkinter)|
|   - Chatbot                 |
|   - Photobooth              |
|   - Translation             |
|   - Video Player            |
|   - Text-to-Speech          |
|   - Attendance              |
+--------------+--------------+
               |
               v
+--------------+--------------+
|  Flask Server + QR Access   |
|   - Generates QR             |
|   - Hosts Mobile Control     |
+--------------+--------------+
               |
               v
+--------------+--------------+
|     Mobile Browser Control  |
|  (Operate robot remotely)   |
+-----------------------------+

```

 🧾 Outcome

- Successfully deployed across multiple educational institutions.  
- Reduced manual configuration by 60% through mobile-based control.  
- Improved student engagement through emotion and face-based interaction.  
- Provided a modular, extensible AI system adaptable to new hardware modules.
