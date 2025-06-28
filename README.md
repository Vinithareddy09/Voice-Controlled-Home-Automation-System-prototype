# Voice-Controlled Home Automation System Prototype 🎙️🏠

A prototype system that demonstrates voice-controlled home automation using speech recognition and Python. This project allows users to control home appliances (e.g., lights, fan) through voice commands, providing a hands-free and intelligent interface for smart living.

## 🚀 Features

- Voice command recognition using SpeechRecognition and Pyttsx3
- Simulated control of home appliances (ON/OFF)
- Real-time voice feedback
- Beginner-friendly and modular Python code

## 🛠 Tech Stack

- **Programming Language**: Python
- **Libraries**: 
  - `speech_recognition` – for capturing and interpreting voice
  - `pyttsx3` – for text-to-speech feedback
  - `pyaudio` – for microphone access
  - `datetime` (optional) – for scheduling or logging
- **Platform**: Desktop (CLI-based prototype)

## 📦 How to Run

```bash
# Clone the repository
git clone https://github.com/Vinithareddy09/Voice-Controlled-Home-Automation-System-prototype.git
cd Voice-Controlled-Home-Automation-System-prototype

# Install dependencies
pip install speechrecognition pyttsx3 pyaudio

# Run the assistant
python voice_control.py
